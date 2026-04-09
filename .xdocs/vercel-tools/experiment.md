# Experiment: Asking Questions against Next.js docs

**Method:**

1. Ran `npx @next/codemod@latest agents-md --output nextjs-docs.md`
2. This created a dense index "nextjs-docs.md" (see [Vercel Study](https://vercel.com/blog/agents-md-outperforms-skills-in-our-agent-evals)) and a `.next-docs/` directory with 391 files organised into 4 main directories
3. Launch 4 parallel agents, same Next.js question, just different approaches
    - Agent 1 (search-first)
    - Agent 2 (tree-first)
    - Agent 3 (index-first)
    - Agent 4 (tree-first-then-grep)

**Results:**

The agent who was told to do `tree` first, then Grep for key terms, then loop if needed, gave the best answer. The one that used the "Vercel way" ("nextjs-docs.md") did not give the best answer, but used the most tokens.

**My Conclusion:** A tiny little litmus test, but even the smallest instruction change that isn't rocket science, changes a lot.

---

## Instructions Given

**Agent 1 (search-first):** *"Answer this Next.js question using local documentation files: 'How do I handle uncached data outside Suspense?' Search for relevant content in these directories: .next-docs/01-app/ and .next-docs/03-architecture/. Include file path references in your answer."*

**Agent 2 (tree-first):** *"Answer this Next.js question using local documentation files: 'How do I handle uncached data outside Suspense?' First, run tree on these directories to understand the structure: .next-docs/01-app/ and .next-docs/03-architecture/. Then identify candidate files, read them, and answer. Include file path references."*

**Agent 3 (index-first):** *"Answer this Next.js question using local documentation files: 'How do I handle uncached data outside Suspense?' Search for relevant content using this index `nextjs-docs.md`. Include file path references."*

**Agent 4 (tree-first-then-grep):** *"Answer this Next.js question using local documentation files: 'How do I handle uncached data outside Suspense?' First, run tree on these directories to understand the structure: .next-docs/01-app/ and .next-docs/03-architecture/. Then identify candidate files, Grep for likely key terms (case insensitive) to further narrow down, read them, and answer. If the read information is insufficient or you are unsure still, Grep the directories to identify files. Loop as needed. Include file path references."*

## Results

| Metric | Agent 1 (search) | Agent 2 (tree) | Agent 3 (index) | Agent 4 (tree+grep) |
|:---|:---|:---|:---|:---|
| **Tokens** | 31,096 | 38,017 | 43,696 | 37,362 |
| **Duration** | 49s | 51s | 42s | 66s |
| **Tool calls** | 11 | 8 | 7 | 14 |
| **Files cited** | 4 | 6 | 4 | 5 |
| **Topics covered (of 9)** | 4 | 6 | 6 | 8 |

### Topic Coverage

| Topic | A1 (search) | A2 (tree) | A3 (index) | A4 (tree+grep) |
|:---|:---:|:---:|:---:|:---:|
| `use cache` | Yes | Yes | Yes | Yes |
| `<Suspense>` streaming | Yes | Yes | Yes | Yes |
| Runtime APIs | Brief | Yes | Yes | Yes |
| Runtime values → cached fns | No | No | Yes | No |
| `connection()` | No | Yes | Brief | Yes |
| Opt-out static shell | Yes | Yes | No | Yes |
| `loading.js` | No | No | Yes | Yes |
| "Push dynamic down" pattern | No | Yes | No | Yes |
| Migration context | No | Brief | No | Yes |

## Answer Evaluation

**Agent 4 (tree+grep) produced the best answer.** It covered 8 of 9 ground-truth topics — more than any other agent — and was the only one to find `loading.js`, `connection()`, the opt-out escape hatch, the "push dynamic down" pattern, and migration context all in one answer. It also included a decision summary table that none of the others produced.

**Agent 2 (tree)** and **Agent 3 (index)** tied at 6 topics each but with different coverage gaps. Agent 2 found `connection()` and "push dynamic down" but missed `loading.js`; Agent 3 found `loading.js` and runtime-values-to-cached-functions but missed `connection()` and the opt-out pattern.

**Agent 1 (search)** was the weakest — only 4 topics, missing `connection()`, `loading.js`, the "push dynamic down" pattern, and migration context entirely. Pure grep without structural awareness led to narrow results.

## Conclusion

**Agent 4's instruction (tree-first-then-grep) produces the highest quality answer** at the cost of being the slowest (66s vs 42-51s) and most tool-call-heavy (14 vs 7-11). The tree→grep→read→loop pipeline gives the agent structural awareness, case-insensitive keyword filtering, and permission to iterate — resulting in the most comprehensive coverage.

If **quality is the priority**, use Agent 4's instruction. If **speed matters more** and a good-enough answer suffices, Agent 3 (index-first) is the best efficiency-to-quality ratio: fastest (42s), fewest tool calls (7), and still covered 6 of 9 topics.
