---
title: Vercel Documentation Sitemap
source: https://vercel.com/docs/sitemap.md
scrape-date: 2026-04-03
---

# Vercel Documentation Sitemap

## Purpose

This file is a high-level semantic index of the documentation.
It is intended for:

- LLM-assisted navigation (ChatGPT, Claude Code)
- Quick orientation for contributors
- Identifying relevant documentation areas during development

It is not intended to replace individual docs.

---

- [Getting Started](/docs/getting-started-with-vercel) | Type: Tutorial | Lastmod: 2025-09-24 | Summary: This step-by-step tutorial will help you get started with Vercel, an end-to-end platform for developers that allows you to create and deploy your web application. | Prerequisites: None | Topics: getting started with vercel
- [Fundamental Concepts](/docs/fundamentals) | Type: Conceptual | Summary: Learn about fundamental concepts on Vercel. | Prerequisites: None | Topics: fundamentals
  - [Request Lifecycle](/docs/fundamentals/infrastructure) | Type: Conceptual | Summary: Learn about request lifecycle on Vercel. | Prerequisites: Fundamental Concepts | Topics: fundamentals, infrastructure
  - [Build System](/docs/fundamentals/builds) | Type: Conceptual | Summary: Learn about build system on Vercel. | Prerequisites: Fundamental Concepts | Topics: fundamentals, builds
  - [What is Compute?](/docs/fundamentals/what-is-compute) | Type: Conceptual | Summary: Learn about what is compute? on Vercel. | Prerequisites: Fundamental Concepts | Topics: fundamentals, what is compute
- [Supported Frameworks](/docs/frameworks) | Type: Conceptual | Lastmod: 2025-09-24 | Summary: Vercel supports a wide range of the most popular frameworks, optimizing how your application builds and runs no matter what tool you use. | Prerequisites: None | Topics: frameworks
  - [Full-stack](/docs/frameworks/full-stack) | Type: Conceptual | Lastmod: 2025-09-24 | Summary: Vercel supports a wide range of the most popular backend frameworks, optimizing how your application builds and runs no matter what tooling you use. | Prerequisites: Supported Frameworks | Topics: frameworks, full stack
    - [Next.js](/docs/frameworks/full-stack/nextjs) | Type: Conceptual | Lastmod: 2026-03-02 | Summary: Vercel is the native Next.js platform, designed to enhance the Next.js experience. | Prerequisites: Supported Frameworks, Full-stack | Topics: frameworks, full stack
    - [SvelteKit](/docs/frameworks/full-stack/sveltekit) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how to use Vercel's features with SvelteKit | Prerequisites: Supported Frameworks, Full-stack | Topics: frameworks, full stack
    - [Nuxt](/docs/frameworks/full-stack/nuxt) | Type: Conceptual | Lastmod: 2026-03-17 | Summary: Learn how to use Vercel's features with Nuxt. | Prerequisites: Supported Frameworks, Full-stack | Topics: frameworks, full stack
    - [Remix](/docs/frameworks/full-stack/remix) | Type: Conceptual | Lastmod: 2026-03-10 | Summary: Learn how to use Vercel's features with Remix. | Prerequisites: Supported Frameworks, Full-stack | Topics: frameworks, full stack
    - [TanStack Start](/docs/frameworks/full-stack/tanstack-start) | Type: Conceptual | Lastmod: 2026-03-02 | Summary: Learn how to use Vercel's features with TanStack Start. | Prerequisites: Supported Frameworks, Full-stack | Topics: frameworks, full stack
    - [Vite + Nitro](/docs/frameworks/full-stack/vite-with-nitro) | Type: Conceptual | Lastmod: 2026-03-09 | Summary: Add a backend to any Vite app with Nitro and deploy to Vercel with zero configuration. | Prerequisites: Supported Frameworks, Full-stack | Topics: frameworks, full stack
  - [Frontends](/docs/frameworks/frontend) | Type: Conceptual | Lastmod: 2025-09-24 | Summary: Vercel supports a wide range of the most popular frontend frameworks, optimizing how your application builds and runs no matter what tooling you use. | Prerequisites: Supported Frameworks | Topics: frameworks, frontend
    - [Astro](/docs/frameworks/frontend/astro) | Type: Conceptual | Lastmod: 2026-03-17 | Summary: Learn how to use Vercel's features with Astro | Prerequisites: Supported Frameworks, Frontends | Topics: frameworks, frontend
    - [Vite](/docs/frameworks/frontend/vite) | Type: Conceptual | Lastmod: 2026-03-09 | Summary: Learn how to use Vercel's features with Vite. | Prerequisites: Supported Frameworks, Frontends | Topics: frameworks, frontend
    - [React Router](/docs/frameworks/frontend/react-router) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how to use Vercel's features with React Router as a framework. | Prerequisites: Supported Frameworks, Frontends | Topics: frameworks, frontend
    - [Create React App](/docs/frameworks/frontend/create-react-app) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how to use Vercel's features with Create React App | Prerequisites: Supported Frameworks, Frontends | Topics: frameworks, frontend
  - [Backends](/docs/frameworks/backend) | Type: Conceptual | Lastmod: 2025-10-21 | Summary: Vercel supports a wide range of the most popular backend frameworks, optimizing how your application builds and runs no matter what tooling you use. | Prerequisites: Supported Frameworks | Topics: frameworks, backend
    - [Nitro](/docs/frameworks/backend/nitro) | Type: How-to | Lastmod: 2026-03-09 | Summary: Deploy Nitro applications to Vercel with zero configuration. Learn about observability, ISR, and custom build configurations. | Prerequisites: Supported Frameworks, Backends | Topics: frameworks, backend
    - [Express](/docs/frameworks/backend/express) | Type: How-to | Lastmod: 2025-11-14 | Summary: Deploy Express applications to Vercel with zero configuration. Learn about middleware and Vercel Functions. | Prerequisites: Supported Frameworks, Backends | Topics: frameworks, backend
    - [Elysia](/docs/frameworks/backend/elysia) | Type: How-to | Lastmod: 2026-03-02 | Summary: Build fast TypeScript backends with Elysia and deploy to Vercel. Learn the project structure, plugins, middleware, and how to run locally and in production. | Prerequisites: Supported Frameworks, Backends | Topics: frameworks, backend
    - [FastAPI](/docs/frameworks/backend/fastapi) | Type: How-to | Lastmod: 2026-03-10 | Summary: Deploy FastAPI applications to Vercel with zero configuration. Learn about the Python runtime, ASGI, static assets, and Vercel Functions. | Prerequisites: Supported Frameworks, Backends | Topics: frameworks, backend
    - [Fastify](/docs/frameworks/backend/fastify) | Type: How-to | Lastmod: 2026-03-02 | Summary: Deploy Fastify applications to Vercel with zero configuration. | Prerequisites: Supported Frameworks, Backends | Topics: frameworks, backend
    - [Flask](/docs/frameworks/backend/flask) | Type: How-to | Lastmod: 2026-03-10 | Summary: Deploy Flask applications to Vercel with zero configuration. Learn about the Python runtime, WSGI, static assets, and Vercel Functions. | Prerequisites: Supported Frameworks, Backends | Topics: frameworks, backend
    - [Hono](/docs/frameworks/backend/hono) | Type: How-to | Lastmod: 2025-10-15 | Summary: Deploy Hono applications to Vercel with zero configuration. Learn about observability, ISR, and custom build configurations. | Prerequisites: Supported Frameworks, Backends | Topics: frameworks, backend
    - [Koa](/docs/frameworks/backend/koa) | Type: How-to | Lastmod: 2026-03-02 | Summary: Deploy Koa applications to Vercel with zero configuration. | Prerequisites: Supported Frameworks, Backends | Topics: frameworks, backend
    - [NestJS](/docs/frameworks/backend/nestjs) | Type: How-to | Lastmod: 2025-10-28 | Summary: Deploy NestJS applications to Vercel with zero configuration. | Prerequisites: Supported Frameworks, Backends | Topics: frameworks, backend
    - [xmcp](/docs/frameworks/backend/xmcp) | Type: How-to | Lastmod: 2025-11-19 | Summary: Build MCP-compatible backends with xmcp and deploy to Vercel. Learn the project structure, tool format, middleware, and how to run locally and in production. | Prerequisites: Supported Frameworks, Backends | Topics: frameworks, backend
  - [All Frameworks](/docs/frameworks/more-frameworks) | Type: Reference | Lastmod: 2025-07-31 | Summary: Learn about the frameworks that can be deployed to Vercel. | Prerequisites: Supported Frameworks | Topics: frameworks, more frameworks
- [Incremental Migration](/docs/incremental-migration) | Type: Conceptual | Lastmod: 2026-01-21 | Summary: Learn how to migrate your app or website to Vercel with minimal risk and high impact. | Prerequisites: None | Topics: incremental migration
- [Production Checklist](/docs/production-checklist) | Type: Reference | Lastmod: 2026-03-03 | Summary: Ensure your application is ready for launch with this comprehensive production checklist by the Vercel engineering team. Covering operational excellence, security, reliability, performance efficiency, and cost optimization. | Prerequisites: None | Topics: production checklist

## APIs & SDKs

- [Rest API](/docs/rest-api) | Type: Conceptual | Summary: Learn about rest api on Vercel. | Prerequisites: None | Topics: rest api
- [Vercel SDK](/docs/rest-api/sdk) | Type: Reference | Summary: Learn about vercel sdk on Vercel. | Prerequisites: None | Topics: rest api, sdk
- [Marketplace Partner API](/docs/integrations/create-integration/marketplace-api/reference/partner) | Type: Conceptual | Summary: Learn about marketplace partner api on Vercel. | Prerequisites: None | Topics: integrations, create integration
- [Marketplace Vercel API](/docs/integrations/create-integration/marketplace-api/reference/vercel) | Type: Conceptual | Summary: Learn about marketplace vercel api on Vercel. | Prerequisites: None | Topics: integrations, create integration

## Access

- [Account Management](/docs/accounts) | Type: Reference | Lastmod: 2026-03-12 | Summary: Learn how to manage your Vercel account and team members. | Prerequisites: None | Topics: access, accounts
- [Sign in with Vercel](/docs/sign-in-with-vercel) | Type: How-to | Lastmod: 2025-12-18 | Summary: Learn how to Sign in with Vercel | Prerequisites: None | Topics: access, sign in with vercel
  - [Getting Started](/docs/sign-in-with-vercel/getting-started) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to get started with Sign in with Vercel | Prerequisites: Sign in with Vercel | Topics: sign in with vercel, getting started
  - [Scopes & Permissions](/docs/sign-in-with-vercel/scopes-and-permissions) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to manage scopes and permissions for Sign in with Vercel | Prerequisites: Sign in with Vercel | Topics: sign in with vercel, scopes and permissions
  - [Tokens](/docs/sign-in-with-vercel/tokens) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to Sign in with Vercel | Prerequisites: Sign in with Vercel | Topics: sign in with vercel, tokens
  - [Authorization Server API](/docs/sign-in-with-vercel/authorization-server-api) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to use the Authorization Server API | Prerequisites: Sign in with Vercel | Topics: sign in with vercel, authorization server api
  - [Manage from Dashboard](/docs/sign-in-with-vercel/manage-from-dashboard) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to manage Sign in with Vercel from the Dashboard | Prerequisites: Sign in with Vercel | Topics: sign in with vercel, manage from dashboard
  - [Consent Page](/docs/sign-in-with-vercel/consent-page) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how the consent page works when users authorize your app | Prerequisites: Sign in with Vercel | Topics: sign in with vercel, consent page
  - [Troubleshooting](/docs/sign-in-with-vercel/troubleshooting) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to troubleshoot common errors with Sign in with Vercel | Prerequisites: Sign in with Vercel | Topics: sign in with vercel, troubleshooting
- [Activity Log](/docs/activity-log) | Type: Reference | Lastmod: 2026-03-13 | Summary: Learn how to use the Activity Log, which provides a list of all events on a team, chronologically organized since its creation. | Prerequisites: None | Topics: access, activity log
- [Deployment Protection](/docs/deployment-protection) | Type: Conceptual | Lastmod: 2026-03-04 | Summary: Learn how to control access to your Vercel project's preview and production URLs with Deployment Protection. Configure protection methods and scope at the project level. | Prerequisites: None | Topics: access, deployment protection
  - [Bypass Deployment Protection](/docs/deployment-protection/methods-to-bypass-deployment-protection) | Type: Conceptual | Lastmod: 2026-02-11 | Summary: Learn how to bypass Deployment Protection for specific domains, or for all deployments in a project. | Prerequisites: Deployment Protection | Topics: deployment protection, methods to bypass deployment protection
    - [Exceptions](/docs/deployment-protection/methods-to-bypass-deployment-protection/deployment-protection-exceptions) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to disable Deployment Protection for a list of preview domains. | Prerequisites: Deployment Protection, Bypass Deployment Protection | Topics: deployment protection, methods to bypass deployment protection
    - [OPTIONS Allowlist](/docs/deployment-protection/methods-to-bypass-deployment-protection/options-allowlist) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to disable Deployment Protection for CORS preflight requests for a list of paths. | Prerequisites: Deployment Protection, Bypass Deployment Protection | Topics: deployment protection, methods to bypass deployment protection
    - [Protection Bypass for Automation](/docs/deployment-protection/methods-to-bypass-deployment-protection/protection-bypass-automation) | Type: How-to | Lastmod: 2026-02-21 | Summary: Learn how to bypass Vercel Deployment Protection for automated tooling \(e.g. E2E testing\). | Prerequisites: Deployment Protection, Bypass Deployment Protection | Topics: deployment protection, methods to bypass deployment protection
    - [Sharable Links](/docs/deployment-protection/methods-to-bypass-deployment-protection/sharable-links) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to share your deployments with external users. | Prerequisites: Deployment Protection, Bypass Deployment Protection | Topics: deployment protection, methods to bypass deployment protection
  - [Protect Deployments](/docs/deployment-protection/methods-to-protect-deployments) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Learn about the different methods to protect your deployments on Vercel, including Vercel Authentication, Password Protection, and Trusted IPs. | Prerequisites: Deployment Protection | Topics: deployment protection, methods to protect deployments
    - [Password Protection](/docs/deployment-protection/methods-to-protect-deployments/password-protection) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to protect your deployments with a password. | Prerequisites: Deployment Protection, Protect Deployments | Topics: deployment protection, methods to protect deployments
    - [Restrict access to deployments with Vercel Authentication](/docs/deployment-protection/methods-to-protect-deployments/vercel-authentication) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to use Vercel Authentication to restrict access to your deployments. | Prerequisites: Deployment Protection, Protect Deployments | Topics: deployment protection, methods to protect deployments
    - [Trusted IPs](/docs/deployment-protection/methods-to-protect-deployments/trusted-ips) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to restrict access to your deployments to a list of trusted IP addresses. | Prerequisites: Deployment Protection, Protect Deployments | Topics: deployment protection, methods to protect deployments
  - [Automated & Agent Access](/docs/deployment-protection/automated-agent-access) | Type: Conceptual | Summary: Learn about automated & agent access on Vercel. | Prerequisites: Deployment Protection | Topics: deployment protection, automated agent access
- [Directory Sync](/docs/directory-sync) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how to configure Directory Sync for your Vercel Team. | Prerequisites: None | Topics: access, directory sync
- [SAML SSO](/docs/saml) | Type: Reference | Lastmod: 2026-02-27 | Summary: Learn how to configure SAML SSO for your organization on Vercel. | Prerequisites: None | Topics: access, saml
- [Two-factor \(2FA\)](/docs/two-factor-authentication) | Type: How-to | Lastmod: 2026-02-23 | Summary: Learn how to configure two-factor authentication for your Vercel account. | Prerequisites: None | Topics: access, two factor authentication

## AI

- [Vercel Agent](/docs/agent) | Type: Conceptual | Lastmod: 2026-03-17 | Summary: AI-powered development tools that speed up your workflow and help resolve issues faster | Prerequisites: None | Topics: ai, agent
  - [Code Review](/docs/agent/pr-review) | Type: How-to | Lastmod: 2026-03-17 | Summary: Get automatic AI-powered code reviews on your pull requests | Prerequisites: Vercel Agent | Topics: agent, pr review
    - [Managing Reviews](/docs/agent/pr-review/usage) | Type: Integration | Lastmod: 2026-02-26 | Summary: Customize which repositories get reviewed and track your review metrics and spending. | Prerequisites: Vercel Agent, Code Review | Topics: agent, pr review
  - [Investigation](/docs/agent/investigation) | Type: How-to | Lastmod: 2026-02-27 | Summary: Let AI investigate your error alerts to help you debug faster | Prerequisites: Vercel Agent | Topics: agent, investigation
  - [Installation](/docs/agent/installation) | Type: How-to | Lastmod: 2026-02-17 | Summary: Let AI automatically install Web Analytics and Speed Insights in your app | Prerequisites: Vercel Agent | Topics: agent, installation
  - [Pricing](/docs/agent/pricing) | Type: Reference | Lastmod: 2026-02-26 | Summary: Understand how Vercel Agent pricing works and how to manage your credits | Prerequisites: Vercel Agent | Topics: agent, pricing
- [AI SDK](/docs/ai-sdk) | Type: Integration | Lastmod: 2026-01-03 | Summary: TypeScript toolkit for building AI-powered applications with React, Next.js, Vue, Svelte and Node.js | Prerequisites: None | Topics: ai, ai sdk
- [AI Gateway](/docs/ai-gateway) | Type: Landing | Lastmod: 2026-03-17 | Summary: AI Gateway provides a unified API to access hundreds of AI models through a single endpoint, with built-in budgets, usage monitoring, and fallbacks. | Prerequisites: None | Topics: ai, ai gateway
  - [Getting Started](/docs/ai-gateway/getting-started) | Type: Tutorial | Lastmod: 2026-03-07 | Summary: Get started with AI Gateway by generating text, images, or video. | Prerequisites: AI Gateway | Topics: ai gateway, getting started
    - [Text](/docs/ai-gateway/getting-started/text) | Type: Tutorial | Lastmod: 2026-03-07 | Summary: Generate and stream text responses using AI Gateway. | Prerequisites: AI Gateway, Getting Started | Topics: ai gateway, getting started
    - [Image](/docs/ai-gateway/getting-started/image) | Type: Tutorial | Lastmod: 2026-02-26 | Summary: Generate images from text prompts using AI Gateway. | Prerequisites: AI Gateway, Getting Started | Topics: ai gateway, getting started
    - [Video](/docs/ai-gateway/getting-started/video) | Type: Tutorial | Lastmod: 2026-02-27 | Summary: Generate videos from text prompts, images, or video input using AI Gateway. | Prerequisites: AI Gateway, Getting Started | Topics: ai gateway, getting started
  - [Models & Providers](/docs/ai-gateway/models-and-providers) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Learn about models and providers for the AI Gateway. | Prerequisites: AI Gateway | Topics: ai gateway, models and providers
    - [Provider Options](/docs/ai-gateway/models-and-providers/provider-options) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Configure provider routing, ordering, and fallback behavior in Vercel AI Gateway | Prerequisites: AI Gateway, Models & Providers | Topics: ai gateway, models and providers
    - [Model Fallbacks](/docs/ai-gateway/models-and-providers/model-fallbacks) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Configure model-level failover to try backup models when the primary model is unavailable | Prerequisites: AI Gateway, Models & Providers | Topics: ai gateway, models and providers
    - [Provider Timeouts](/docs/ai-gateway/models-and-providers/provider-timeouts) | Type: Integration | Lastmod: 2026-03-04 | Summary: Configure per-provider timeouts for fast failover when a provider is slow to respond. | Prerequisites: AI Gateway, Models & Providers | Topics: ai, ai gateway, models and providers
    - [Automatic Caching](/docs/ai-gateway/models-and-providers/automatic-caching) | Type: Conceptual | Lastmod: 2026-03-16 | Summary: Enable automatic prompt caching across providers with AI Gateway to reduce costs and latency. | Prerequisites: AI Gateway, Models & Providers | Topics: ai gateway, models and providers
    - [Provider Filtering & Ordering](/docs/ai-gateway/models-and-providers/provider-filtering-and-ordering) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Control which providers handle your requests and in what order using the order and only options. | Prerequisites: AI Gateway, Models & Providers | Topics: ai gateway, models and providers
    - [Model Variants](/docs/ai-gateway/models-and-providers/model-variants) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Enable provider-specific capabilities via headers when calling models through AI Gateway. | Prerequisites: AI Gateway, Models & Providers | Topics: ai gateway, models and providers
  - [Capabilities](/docs/ai-gateway/capabilities) | Type: Conceptual | Lastmod: 2026-03-18 | Summary: Explore AI Gateway capabilities including reasoning, image generation, video generation, web search, observability, usage tracking, and data retention policies. | Prerequisites: AI Gateway | Topics: ai gateway, capabilities
    - [Custom Reporting](/docs/ai-gateway/capabilities/custom-reporting) | Type: Conceptual | Summary: Learn about custom reporting on Vercel. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
    - [Observability](/docs/ai-gateway/capabilities/observability) | Type: Reference | Lastmod: 2026-02-26 | Summary: Learn how to monitor and debug your AI Gateway requests. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
    - [Usage & Billing](/docs/ai-gateway/capabilities/usage) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Monitor your AI Gateway credit balance, usage, and generation details. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
    - [Image Generation](/docs/ai-gateway/capabilities/image-generation) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Generate and edit images using AI models through Vercel AI Gateway with support for multiple providers and modalities. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
      - [Using AI SDK](/docs/ai-gateway/capabilities/image-generation/ai-sdk) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Generate and edit images using AI models through Vercel AI Gateway with the AI SDK. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
      - [Using Chat Completions API](/docs/ai-gateway/capabilities/image-generation/openai) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Generate and edit images using AI models through Vercel AI Gateway with the Chat Completions API. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
    - [Video Generation](/docs/ai-gateway/capabilities/video-generation) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Generate videos from text prompts, images, or video input using AI models through Vercel AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
      - [Text-to-Video](/docs/ai-gateway/capabilities/video-generation/text-to-video) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Generate videos from text prompts using Google Veo, KlingAI, Wan, Grok Imagine Video, or ByteDance Seedance through AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
      - [Image-to-Video](/docs/ai-gateway/capabilities/video-generation/image-to-video) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Animate static images into videos using Google Veo, KlingAI, Wan, Grok Imagine Video, or ByteDance Seedance through AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
      - [Reference-to-Video](/docs/ai-gateway/capabilities/video-generation/reference-to-video) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Generate videos featuring characters from reference images or videos using Wan through AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
      - [Motion Control](/docs/ai-gateway/capabilities/video-generation/motion-control) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Transfer motion from a reference video to a character image using KlingAI through AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
      - [Video Editing](/docs/ai-gateway/capabilities/video-generation/video-editing) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Edit existing videos using text prompts with Grok Imagine Video through AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
    - [Web Search](/docs/ai-gateway/capabilities/web-search) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Enable AI models to search the web for current information using built-in tools through AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
    - [Reasoning](/docs/ai-gateway/capabilities/reasoning) | Type: Reference | Lastmod: 2026-03-07 | Summary: Enable reasoning and extended thinking across providers with the AI SDK and AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai, ai gateway, capabilities
      - [OpenAI](/docs/ai-gateway/capabilities/reasoning/openai) | Type: Reference | Lastmod: 2026-03-07 | Summary: Configure reasoning and thinking for OpenAI models with the AI SDK and AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai, ai gateway, capabilities
      - [Anthropic](/docs/ai-gateway/capabilities/reasoning/anthropic) | Type: Reference | Lastmod: 2026-03-07 | Summary: Configure extended thinking for Anthropic Claude models with the AI SDK and AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai, ai gateway, capabilities
      - [Google / Vertex](/docs/ai-gateway/capabilities/reasoning/google) | Type: Reference | Lastmod: 2026-03-07 | Summary: Configure thinking for Google Gemini models with the AI SDK and AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai, ai gateway, capabilities
      - [Amazon Bedrock](/docs/ai-gateway/capabilities/reasoning/amazon-bedrock) | Type: Reference | Lastmod: 2026-03-07 | Summary: Configure reasoning for models hosted on Amazon Bedrock with the AI SDK and AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai, ai gateway, capabilities
    - [Zero Data Retention](/docs/ai-gateway/capabilities/zdr) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Learn about zero data retention policies and how to enforce ZDR on a per-request basis with AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
    - [Disallow Prompt Training](/docs/ai-gateway/capabilities/disallow-prompt-training) | Type: Conceptual | Summary: Learn about disallow prompt training on Vercel. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
    - [Service Tiers](/docs/ai-gateway/capabilities/service-tiers) | Type: Reference | Lastmod: 2026-03-18 | Summary: Control processing priority and cost for OpenAI models using service tiers through AI Gateway. | Prerequisites: AI Gateway, Capabilities | Topics: ai gateway, capabilities
  - [SDKs & APIs](/docs/ai-gateway/sdks-and-apis) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Use the AI Gateway with various SDKs and API specifications including OpenAI, Anthropic, and OpenResponses. | Prerequisites: AI Gateway | Topics: ai gateway, sdks and apis
    - [AI SDK](/docs/ai-gateway/sdks-and-apis/ai-sdk) | Type: Integration | Lastmod: 2026-03-07 | Summary: Build AI-powered TypeScript applications using the AI SDK with AI Gateway for unified access to 200+ models. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai, ai gateway, sdks and apis
    - [OpenAI Responses API](/docs/ai-gateway/sdks-and-apis/responses) | Type: Reference | Lastmod: 2026-03-07 | Summary: Use the OpenAI Responses API with AI Gateway to generate text, call tools, stream tokens, and more across any supported provider. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai, ai gateway, sdks and apis
    - [OpenAI Chat Completions API](/docs/ai-gateway/sdks-and-apis/openai-chat-completions) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Use the OpenAI Chat Completions API with AI Gateway for seamless integration with existing tools and libraries. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Chat Completions](/docs/ai-gateway/sdks-and-apis/openai-chat-completions/chat-completions) | Type: Reference | Lastmod: 2026-03-07 | Summary: Create chat completions using the Chat Completions API with support for streaming, image attachments, and PDF documents. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Tool Calls](/docs/ai-gateway/sdks-and-apis/openai-chat-completions/tool-calls) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Use function calling with the Chat Completions API to enable models to call tools and functions through AI Gateway. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Structured Outputs](/docs/ai-gateway/sdks-and-apis/openai-chat-completions/structured-outputs) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Generate structured JSON responses that conform to a specific schema using the Chat Completions API. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Advanced](/docs/ai-gateway/sdks-and-apis/openai-chat-completions/advanced) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Configure reasoning, provider options, model fallbacks, BYOK credentials, and prompt caching. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Embeddings](/docs/ai-gateway/sdks-and-apis/openai-chat-completions/embeddings) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Generate vector embeddings from input text for semantic search, similarity matching, and RAG applications. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Image Generation](/docs/ai-gateway/sdks-and-apis/openai-chat-completions/image-generation) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Generate images using AI models that support multimodal output through the Chat Completions API. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [REST API](/docs/ai-gateway/sdks-and-apis/openai-chat-completions/rest-api) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Use the AI Gateway API directly without client libraries using curl and fetch. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
    - [Anthropic Messages API](/docs/ai-gateway/sdks-and-apis/anthropic-messages-api) | Type: Conceptual | Lastmod: 2026-03-16 | Summary: Use the Anthropic Messages API with AI Gateway for seamless integration with Anthropic SDK tools. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Messages](/docs/ai-gateway/sdks-and-apis/anthropic-messages-api/messages) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Create messages using the Anthropic Messages API format with support for streaming. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Tool Calls](/docs/ai-gateway/sdks-and-apis/anthropic-messages-api/tool-calls) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Use function calling with the Anthropic Messages API to allow models to call tools and functions. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Advanced](/docs/ai-gateway/sdks-and-apis/anthropic-messages-api/advanced) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Advanced Anthropic API features including extended thinking, web search, and automatic caching. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [File Attachments](/docs/ai-gateway/sdks-and-apis/anthropic-messages-api/file-attachments) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Send images and PDF documents as part of your Anthropic API message requests. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Structured Outputs](/docs/ai-gateway/sdks-and-apis/anthropic-messages-api/structured-outputs) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Get JSON responses conforming to a JSON Schema from Anthropic models through AI Gateway. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
    - [OpenResponses API](/docs/ai-gateway/sdks-and-apis/openresponses) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Use the OpenResponses API specification with AI Gateway for a unified, provider-agnostic interface. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Text Generation](/docs/ai-gateway/sdks-and-apis/openresponses/text-generation) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Generate text responses using the OpenResponses API. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Streaming](/docs/ai-gateway/sdks-and-apis/openresponses/streaming) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Stream responses token by token using the OpenResponses API. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Image Input](/docs/ai-gateway/sdks-and-apis/openresponses/image-input) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Send images for analysis using the OpenResponses API. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Tool Calling](/docs/ai-gateway/sdks-and-apis/openresponses/tool-calling) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Define tools the model can call using the OpenResponses API. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
      - [Provider Options](/docs/ai-gateway/sdks-and-apis/openresponses/provider-options) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Configure provider routing, fallbacks, and restrictions using the OpenResponses API. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
    - [Python](/docs/ai-gateway/sdks-and-apis/python) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Use the AI Gateway with Python through OpenAI or Anthropic SDKs with full streaming, tool calling, and async support. | Prerequisites: AI Gateway, SDKs & APIs | Topics: ai gateway, sdks and apis
  - [Authentication & BYOK](/docs/ai-gateway/authentication-and-byok) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how to authenticate with the AI Gateway and configure your own provider keys. | Prerequisites: AI Gateway | Topics: ai gateway, authentication and byok
    - [Authentication](/docs/ai-gateway/authentication-and-byok/authentication) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how to authenticate with the AI Gateway using API keys and OIDC tokens. | Prerequisites: AI Gateway, Authentication & BYOK | Topics: ai gateway, authentication and byok
    - [BYOK](/docs/ai-gateway/authentication-and-byok/byok) | Type: How-to | Lastmod: 2026-03-07 | Summary: Learn how to configure your own provider keys with the AI Gateway. | Prerequisites: AI Gateway, Authentication & BYOK | Topics: ai gateway, authentication and byok
  - [Ecosystem](/docs/ai-gateway/ecosystem) | Type: Conceptual | Lastmod: 2026-03-08 | Summary: Explore community framework integrations and ecosystem features for the AI Gateway. | Prerequisites: AI Gateway | Topics: ai gateway, ecosystem
    - [Framework Integrations](/docs/ai-gateway/ecosystem/framework-integrations) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Explore available community framework integrations with Vercel AI Gateway | Prerequisites: AI Gateway, Ecosystem | Topics: ai gateway, ecosystem
      - [LangChain](/docs/ai-gateway/ecosystem/framework-integrations/langchain) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Learn how to integrate Vercel AI Gateway with LangChain to access multiple AI models through a unified interface | Prerequisites: AI Gateway, Ecosystem | Topics: ai gateway, ecosystem
      - [LangFuse](/docs/ai-gateway/ecosystem/framework-integrations/langfuse) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how to integrate Vercel AI Gateway with LangFuse to access multiple AI models through a unified interface | Prerequisites: AI Gateway, Ecosystem | Topics: ai gateway, ecosystem
      - [LiteLLM](/docs/ai-gateway/ecosystem/framework-integrations/litellm) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how to integrate Vercel AI Gateway with LiteLLM to access multiple AI models through a unified interface | Prerequisites: AI Gateway, Ecosystem | Topics: ai gateway, ecosystem
      - [LlamaIndex](/docs/ai-gateway/ecosystem/framework-integrations/llamaindex) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how to integrate Vercel AI Gateway with LlamaIndex to access multiple AI models through a unified interface | Prerequisites: AI Gateway, Ecosystem | Topics: ai gateway, ecosystem
      - [Mastra](/docs/ai-gateway/ecosystem/framework-integrations/mastra) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how to integrate Vercel AI Gateway with Mastra to access multiple AI models through a unified interface | Prerequisites: AI Gateway, Ecosystem | Topics: ai gateway, ecosystem
      - [Pydantic AI](/docs/ai-gateway/ecosystem/framework-integrations/pydantic-ai) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how to integrate Vercel AI Gateway with Pydantic AI to access multiple AI models through a unified interface | Prerequisites: AI Gateway, Ecosystem | Topics: ai gateway, ecosystem
    - [App Attribution](/docs/ai-gateway/ecosystem/app-attribution) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Attribute your requests so Vercel can identify and feature your app on AI Gateway pages | Prerequisites: AI Gateway, Ecosystem | Topics: ai gateway, ecosystem
    - [Stripe Billing](/docs/ai-gateway/ecosystem/stripe-billing) | Type: How-to | Lastmod: 2026-03-08 | Summary: Add usage-based billing to your AI application with Stripe and AI Gateway. | Prerequisites: AI Gateway, Ecosystem | Topics: ai gateway, ecosystem
  - [Pricing](/docs/ai-gateway/pricing) | Type: Reference | Lastmod: 2026-02-26 | Summary: Learn about pricing for AI Gateway. | Prerequisites: AI Gateway | Topics: ai gateway, pricing
  - [Chat Platforms](/docs/ai-gateway/chat-platforms) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Configure AI chat platforms to use the AI Gateway for unified model access and spend monitoring. | Prerequisites: AI Gateway | Topics: ai gateway, chat platforms
    - [LibreChat](/docs/ai-gateway/chat-platforms/librechat) | Type: Conceptual | Lastmod: 2026-03-07 | Summary: Use LibreChat with the AI Gateway. | Prerequisites: AI Gateway, Chat Platforms | Topics: ai gateway, chat platforms
    - [OpenClaw \(Clawdbot\)](/docs/ai-gateway/chat-platforms/openclaw) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Use OpenClaw \(formerly Clawdbot\) with AI Gateway. | Prerequisites: AI Gateway, Chat Platforms | Topics: ai gateway, chat platforms
    - [Chatbox](/docs/ai-gateway/chat-platforms/chatbox) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Use Chatbox with the AI Gateway. | Prerequisites: AI Gateway, Chat Platforms | Topics: ai gateway, chat platforms
    - [Open WebUI](/docs/ai-gateway/chat-platforms/open-webui) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Use Open WebUI with the AI Gateway. | Prerequisites: AI Gateway, Chat Platforms | Topics: ai gateway, chat platforms
- [MCP](/docs/mcp) | Type: Integration | Lastmod: 2026-02-10 | Summary: Learn more about MCP and how you can use it on Vercel. | Prerequisites: None | Topics: ai, mcp
  - [Deploy MCP servers](/docs/mcp/deploy-mcp-servers-to-vercel) | Type: How-to | Lastmod: 2026-02-17 | Summary: Learn how to deploy Model Context Protocol \(MCP\) servers on Vercel with OAuth authentication and efficient scaling. | Prerequisites: MCP | Topics: ai, mcp, deploy mcp servers to vercel
- [Agent Resources](/docs/agent-resources) | Type: Integration | Lastmod: 2026-02-27 | Summary: Resources for building with AI on Vercel, including documentation access, MCP servers, and agent skills. | Prerequisites: None | Topics: ai, agent resources
  - [Markdown Access](/docs/agent-resources/markdown-access) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Access Vercel documentation as markdown using .md endpoints or the copy button. | Prerequisites: Agent Resources | Topics: agent resources, markdown access
  - [Vercel Plugin](/docs/agent-resources/vercel-plugin) | Type: Conceptual | Summary: Learn about vercel plugin on Vercel. | Prerequisites: Agent Resources | Topics: agent resources, vercel plugin
  - [Vercel MCP server](/docs/agent-resources/vercel-mcp) | Type: Conceptual | Lastmod: 2026-02-12 | Summary: Vercel MCP has tools available for searching docs along with managing teams, projects, and deployments. | Prerequisites: Agent Resources | Topics: agent resources, vercel mcp
    - [Tools](/docs/agent-resources/vercel-mcp/tools) | Type: Conceptual | Lastmod: 2026-02-13 | Summary: Available tools in Vercel MCP for searching docs, managing teams, projects, deployments, and viewing runtime logs. | Prerequisites: Agent Resources, Vercel MCP server | Topics: agent resources, vercel mcp
  - [Coding Agents](/docs/agent-resources/coding-agents) | Type: Conceptual | Lastmod: 2026-03-16 | Summary: Configure popular AI coding agents to use the AI Gateway for unified model access and spend monitoring. | Prerequisites: Agent Resources | Topics: agent resources, coding agents
    - [Claude Code](/docs/agent-resources/coding-agents/claude-code) | Type: Conceptual | Lastmod: 2026-02-10 | Summary: Use Claude Code with the AI Gateway. | Prerequisites: Agent Resources, Coding Agents | Topics: agent resources, coding agents
    - [Conductor](/docs/agent-resources/coding-agents/conductor) | Type: Integration | Lastmod: 2026-02-26 | Summary: Use Conductor with the AI Gateway. | Prerequisites: Agent Resources, Coding Agents | Topics: ai, agent resources, coding agents
    - [OpenAI Codex](/docs/agent-resources/coding-agents/openai-codex) | Type: Conceptual | Lastmod: 2026-03-16 | Summary: Use OpenAI Codex CLI with the AI Gateway. | Prerequisites: Agent Resources, Coding Agents | Topics: agent resources, coding agents
    - [Roo Code](/docs/agent-resources/coding-agents/roo-code) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Use Roo Code with the AI Gateway. | Prerequisites: Agent Resources, Coding Agents | Topics: agent resources, coding agents
    - [Cline](/docs/agent-resources/coding-agents/cline) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Use Cline with the AI Gateway. | Prerequisites: Agent Resources, Coding Agents | Topics: agent resources, coding agents
    - [Blackbox AI](/docs/agent-resources/coding-agents/blackbox) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Use the Blackbox AI CLI with the AI Gateway. | Prerequisites: Agent Resources, Coding Agents | Topics: agent resources, coding agents
    - [Crush](/docs/agent-resources/coding-agents/crush) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Use Crush with the AI Gateway. | Prerequisites: Agent Resources, Coding Agents | Topics: agent resources, coding agents
    - [OpenCode](/docs/agent-resources/coding-agents/opencode) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Use OpenCode with the AI Gateway. | Prerequisites: Agent Resources, Coding Agents | Topics: agent resources, coding agents
    - [Superset](/docs/agent-resources/coding-agents/superset) | Type: Conceptual | Lastmod: 2026-03-06 | Summary: Use Superset with the AI Gateway. | Prerequisites: Agent Resources, Coding Agents | Topics: agent resources, coding agents
  - [Integrations for Agents](/docs/agent-resources/integrations-for-agents) | Type: Conceptual | Lastmod: 2026-02-10 | Summary: Install AI agents and services through the Vercel Marketplace to automate workflows and build custom AI systems. | Prerequisites: Agent Resources | Topics: agent resources, integrations for agents
  - [Integrations for Models](/docs/agent-resources/integrations-for-models) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Integrate powerful AI services and models seamlessly into your Vercel projects. | Prerequisites: Agent Resources | Topics: agent resources, integrations for models
    - [Adding a Provider](/docs/agent-resources/integrations-for-models/adding-a-provider) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to add a new AI provider to your Vercel projects. | Prerequisites: Agent Resources, Integrations for Models | Topics: agent resources, integrations for models
    - [Adding a Model](/docs/agent-resources/integrations-for-models/adding-a-model) | Type: How-to | Lastmod: 2026-02-17 | Summary: Learn how to add a new AI model to your Vercel projects | Prerequisites: Agent Resources, Integrations for Models | Topics: agent resources, integrations for models
    - [xAI](/docs/agent-resources/integrations-for-models/xai) | Type: How-to | Lastmod: 2026-02-10 | Summary: Learn how to add the xAI native integration with Vercel. | Prerequisites: Agent Resources, Integrations for Models | Topics: agent resources, integrations for models
    - [Groq](/docs/agent-resources/integrations-for-models/groq) | Type: How-to | Lastmod: 2026-02-10 | Summary: Learn how to add the Groq native integration with Vercel. | Prerequisites: Agent Resources, Integrations for Models | Topics: agent resources, integrations for models
    - [fal](/docs/agent-resources/integrations-for-models/fal) | Type: How-to | Lastmod: 2026-02-10 | Summary: Learn how to add the fal native integration with Vercel. | Prerequisites: Agent Resources, Integrations for Models | Topics: agent resources, integrations for models
    - [Deep Infra](/docs/agent-resources/integrations-for-models/deepinfra) | Type: How-to | Lastmod: 2026-02-10 | Summary: Learn how to add the Deep Infra native integration with Vercel. | Prerequisites: Agent Resources, Integrations for Models | Topics: agent resources, integrations for models
    - [ElevenLabs](/docs/agent-resources/integrations-for-models/elevenlabs) | Type: How-to | Lastmod: 2026-02-10 | Summary: Learn how to add the ElevenLabs connectable account integration with Vercel. | Prerequisites: Agent Resources, Integrations for Models | Topics: agent resources, integrations for models
    - [LMNT](/docs/agent-resources/integrations-for-models/lmnt) | Type: How-to | Lastmod: 2026-02-10 | Summary: Learn how to add LMNT connectable account integration with Vercel. | Prerequisites: Agent Resources, Integrations for Models | Topics: agent resources, integrations for models
    - [OpenAI](/docs/agent-resources/integrations-for-models/openai) | Type: How-to | Lastmod: 2026-02-24 | Summary: Integrate your Vercel project with OpenAI's powerful suite of models. | Prerequisites: Agent Resources, Integrations for Models | Topics: agent resources, integrations for models
    - [Perplexity](/docs/agent-resources/integrations-for-models/perplexity) | Type: How-to | Lastmod: 2026-02-10 | Summary: Learn how to add Perplexity connectable account integration with Vercel. | Prerequisites: Agent Resources, Integrations for Models | Topics: agent resources, integrations for models
    - [Pinecone](/docs/agent-resources/integrations-for-models/pinecone) | Type: How-to | Lastmod: 2026-02-10 | Summary: Learn how to add Pinecone connectable account integration with Vercel. | Prerequisites: Agent Resources, Integrations for Models | Topics: agent resources, integrations for models
    - [Replicate](/docs/agent-resources/integrations-for-models/replicate) | Type: How-to | Lastmod: 2026-02-10 | Summary: Learn how to add Replicate connectable account integration with Vercel. | Prerequisites: Agent Resources, Integrations for Models | Topics: agent resources, integrations for models
    - [Together AI](/docs/agent-resources/integrations-for-models/togetherai) | Type: How-to | Lastmod: 2026-02-10 | Summary: Learn how to add Together AI connectable account integration with Vercel. | Prerequisites: Agent Resources, Integrations for Models | Topics: agent resources, integrations for models
  - [CLI Workflows](/docs/agent-resources/workflows) | Type: Conceptual | Lastmod: 2026-02-24 | Summary: End-to-end workflows that show how to compose Vercel CLI commands into complete debugging, deployment, and recovery sessions. | Prerequisites: Agent Resources | Topics: agent resources, workflows
  - [Skills](/docs/agent-resources/skills) | Type: Reference | Lastmod: 2026-02-17 | Summary: Install skills to enhance AI coding agents with specialized capabilities for React, Next.js, deployment, and more. | Prerequisites: Agent Resources | Topics: agent resources, skills
  - [sitemap.md](/docs/sitemap.md) | Type: Conceptual | Summary: Learn about sitemap.md on Vercel. | Prerequisites: Agent Resources | Topics: sitemap.md

## Build & Deploy

- [Builds](/docs/builds) | Type: Conceptual | Lastmod: 2026-02-17 | Summary: Understand how the build step works when creating a Vercel Deployment. | Prerequisites: None | Topics: build & deploy, builds
  - [Build Features](/docs/builds/build-features) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to customize your deployments using Vercel's build features. | Prerequisites: Builds | Topics: builds, build features
  - [Build Image](/docs/builds/build-image) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn about the container image used for Vercel builds. | Prerequisites: Builds | Topics: builds, build image
  - [Build Queues](/docs/builds/build-queues) | Type: Conceptual | Lastmod: 2026-02-12 | Summary: Understand how concurrency and same branch build queues manage multiple simultaneous deployments. | Prerequisites: Builds | Topics: builds, build queues
  - [Configuring a Build](/docs/builds/configure-a-build) | Type: Reference | Lastmod: 2026-03-17 | Summary: Vercel automatically configures the build settings for many front-end frameworks, but you can also customize the build according to your requirements. | Prerequisites: Builds | Topics: builds, configure a build
  - [Managing Builds](/docs/builds/managing-builds) | Type: How-to | Lastmod: 2026-02-26 | Summary: Vercel allows you to increase the speed of your builds when needed in specific situations and workflows. | Prerequisites: Builds | Topics: builds, managing builds
- [Deploy Hooks](/docs/deploy-hooks) | Type: Conceptual | Lastmod: 2026-02-17 | Summary: Learn how to create and trigger deploy hooks to integrate Vercel deployments with other systems. | Prerequisites: None | Topics: build & deploy, deploy hooks
- [Deployment Checks](/docs/deployment-checks) | Type: Reference | Lastmod: 2026-03-10 | Summary: Set conditions that must be met before proceeding to the next phase of the deployment lifecycle. | Prerequisites: None | Topics: build & deploy, deployment checks
- [Deployment Retention](/docs/deployment-retention) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how Deployment Retention policies affect a deployment's lifecycle | Prerequisites: None | Topics: build & deploy, deployment retention
- [Deployments](/docs/deployments) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how to create and manage deployments on Vercel. | Prerequisites: None | Topics: build & deploy, deployments
  - [Environments](/docs/deployments/environments) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Environments are for developing locally, testing changes in a pre-production environment, and serving end-users in production. | Prerequisites: Deployments | Topics: deployments, environments
  - [Generated URLs](/docs/deployments/generated-urls) | Type: Conceptual | Lastmod: 2025-09-24 | Summary: When you create a new deployment, Vercel will automatically generate a unique URL which you can use to access that particular deployment. | Prerequisites: Deployments | Topics: deployments, generated urls
  - [Managing Deployments](/docs/deployments/managing-deployments) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to manage your current and previously deployed projects to Vercel through the dashboard. You can redeploy at any time and even delete a deployment. | Prerequisites: Deployments | Topics: deployments, managing deployments
  - [Promoting Deployments](/docs/deployments/promoting-a-deployment) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to promote deployments to production on Vercel. | Prerequisites: Deployments | Topics: deployments, promoting a deployment
  - [Troubleshoot Build Errors](/docs/deployments/troubleshoot-a-build) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Learn how to resolve common scenarios you may encounter during the Build step, including build errors that cancel a deployment and long build times. | Prerequisites: Deployments | Topics: deployments, troubleshoot a build
  - [Accessing Build Logs](/docs/deployments/logs) | Type: How-to | Lastmod: 2025-09-24 | Summary: Learn how to use Vercel's build logs to monitor the progress of building or running your deployment, and check for possible errors or build failures. | Prerequisites: Deployments | Topics: deployments, logs
  - [Claim Deployments](/docs/deployments/claim-deployments) | Type: Conceptual | Lastmod: 2025-09-30 | Summary: Learn how to take ownership of deployments on Vercel with the Claim Deployments feature. | Prerequisites: Deployments | Topics: deployments, claim deployments
  - [Inspect OG Metadata](/docs/deployments/og-preview) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to inspect and validate your Open Graph metadata through the Open Graph deployment tab. | Prerequisites: Deployments | Topics: deployments, og preview
  - [Preview Deployment Suffix](/docs/deployments/preview-deployment-suffix) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: When you create a new deployment, Vercel will automatically generate a unique URL which you can use to access that particular deployment. | Prerequisites: Deployments | Topics: deployments, preview deployment suffix
  - [Promote Preview to Production](/docs/deployments/promote-preview-to-production) | Type: How-to | Lastmod: 2026-02-24 | Summary: Test a preview deployment and promote it to production using the CLI. | Prerequisites: Deployments | Topics: build & deploy, deployments, promote preview to production
  - [Rollback Production](/docs/deployments/rollback-production-deployment) | Type: How-to | Lastmod: 2026-02-24 | Summary: Recover from a bad production deployment by rolling back, investigating the root cause, and redeploying a fix. | Prerequisites: Deployments | Topics: build & deploy, deployments, rollback production deployment
  - [Sharing a Preview Deployment](/docs/deployments/sharing-deployments) | Type: How-to | Lastmod: 2025-09-24 | Summary: Learn how to share a preview deployment with your team and external collaborators. | Prerequisites: Deployments | Topics: deployments, sharing deployments
  - [Troubleshoot project collaboration](/docs/deployments/troubleshoot-project-collaboration) | Type: Reference | Lastmod: 2026-03-13 | Summary: Learn about common reasons for deployment issues related to team member requirements and how to resolve them. | Prerequisites: Deployments | Topics: deployments, troubleshoot project collaboration
- [Environment Variables](/docs/environment-variables) | Type: Conceptual | Lastmod: 2026-02-23 | Summary: Learn more about environment variables on Vercel. | Prerequisites: None | Topics: build & deploy, environment variables
  - [Framework Environment Variables](/docs/environment-variables/framework-environment-variables) | Type: Reference | Lastmod: 2025-07-18 | Summary: Framework environment variables are automatically populated by the Vercel, based on your project's framework. | Prerequisites: Environment Variables | Topics: environment variables, framework environment variables
  - [Manage Across Environments](/docs/environment-variables/manage-across-environments) | Type: How-to | Lastmod: 2026-02-24 | Summary: Add, sync, and verify environment variables across development, preview, production, and custom environments using the CLI. | Prerequisites: Environment Variables | Topics: platform, environment variables, manage across environments
  - [Managing Environment Variables](/docs/environment-variables/managing-environment-variables) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to create and manage environment variables for Vercel. | Prerequisites: Environment Variables | Topics: environment variables, managing environment variables
  - [Reserved Environment Variables](/docs/environment-variables/reserved-environment-variables) | Type: Reference | Lastmod: 2025-12-10 | Summary: Reserved environment variables are reserved by Vercel Vercel Function runtimes. | Prerequisites: Environment Variables | Topics: environment variables, reserved environment variables
  - [Rotating Environment Variables](/docs/environment-variables/rotating-secrets) | Type: How-to | Lastmod: 2026-02-27 | Summary: Safely rotate API keys, tokens, and other secrets in your Vercel environment variables. | Prerequisites: Environment Variables | Topics: environment variables, rotating secrets
  - [Sensitive Environment Variables](/docs/environment-variables/sensitive-environment-variables) | Type: How-to | Lastmod: 2026-02-27 | Summary: Environment variables that cannot be decrypted once created. | Prerequisites: Environment Variables | Topics: environment variables, sensitive environment variables
  - [Shared Environment Variables](/docs/environment-variables/shared-environment-variables) | Type: How-to | Lastmod: 2026-03-03 | Summary: Learn how to use Shared environment variables, which are environment variables that you define at the Team level and can link to multiple projects. | Prerequisites: Environment Variables | Topics: environment variables, shared environment variables
  - [System Environment Variables](/docs/environment-variables/system-environment-variables) | Type: Reference | Lastmod: 2026-02-27 | Summary: System environment variables are automatically populated by Vercel, such as the URL of the deployment or the name of the Git branch deployed. | Prerequisites: Environment Variables | Topics: environment variables, system environment variables
- [Git Integrations](/docs/git) | Type: Conceptual | Lastmod: 2026-03-12 | Summary: Vercel allows for automatic deployments on every branch push and merges onto the production branch of your GitHub, GitLab, and Bitbucket projects. | Prerequisites: None | Topics: build & deploy, git
  - [GitHub](/docs/git/vercel-for-github) | Type: Conceptual | Lastmod: 2026-03-17 | Summary: Vercel for GitHub automatically deploys your GitHub projects with Vercel, providing Preview Deployment URLs, and automatic Custom Domain updates. | Prerequisites: Git Integrations | Topics: git, vercel for github
  - [Azure DevOps](/docs/git/vercel-for-azure-pipelines) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: ​Vercel for Azure DevOps allows you to deploy from Azure Pipelines to Vercel automatically. | Prerequisites: Git Integrations | Topics: git, vercel for azure pipelines
  - [Bitbucket](/docs/git/vercel-for-bitbucket) | Type: Conceptual | Lastmod: 2025-11-25 | Summary: ​Vercel for Bitbucket automatically deploys your Bitbucket projects with Vercel, providing Preview Deployment URLs, and automatic Custom Domain updates. | Prerequisites: Git Integrations | Topics: git, vercel for bitbucket
  - [GitLab](/docs/git/vercel-for-gitlab) | Type: Conceptual | Lastmod: 2025-11-25 | Summary: ​Vercel for GitLab automatically deploys your GitLab projects with Vercel, providing Preview Deployment URLs, and automatic Custom Domain updates. | Prerequisites: Git Integrations | Topics: git, vercel for gitlab
- [Instant Rollback](/docs/instant-rollback) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to perform an Instant Rollback on your production deployments and quickly roll back to a previously deployed production deployment. | Prerequisites: None | Topics: build & deploy, instant rollback
- [Microfrontends](/docs/microfrontends) | Type: Conceptual | Summary: Learn about microfrontends on Vercel. | Prerequisites: None | Topics: microfrontends
  - [Getting Started](/docs/microfrontends/quickstart) | Type: Conceptual | Summary: Learn about getting started on Vercel. | Prerequisites: Microfrontends | Topics: microfrontends, quickstart
  - [Local Development](/docs/microfrontends/local-development) | Type: Conceptual | Summary: Learn about local development on Vercel. | Prerequisites: Microfrontends | Topics: microfrontends, local development
  - [Path Routing](/docs/microfrontends/path-routing) | Type: Conceptual | Summary: Learn about path routing on Vercel. | Prerequisites: Microfrontends | Topics: microfrontends, path routing
  - [Configuration](/docs/microfrontends/configuration) | Type: Conceptual | Summary: Learn about configuration on Vercel. | Prerequisites: Microfrontends | Topics: microfrontends, configuration
  - [Managing Microfrontends](/docs/microfrontends/managing-microfrontends) | Type: Conceptual | Summary: Learn about managing microfrontends on Vercel. | Prerequisites: Microfrontends | Topics: microfrontends, managing microfrontends
    - [Security](/docs/microfrontends/managing-microfrontends/security) | Type: Conceptual | Summary: Learn about security on Vercel. | Prerequisites: Microfrontends, Managing Microfrontends | Topics: microfrontends, managing microfrontends
    - [Using Vercel Toolbar](/docs/microfrontends/managing-microfrontends/vercel-toolbar) | Type: Conceptual | Summary: Learn about using vercel toolbar on Vercel. | Prerequisites: Microfrontends, Managing Microfrontends | Topics: microfrontends, managing microfrontends
  - [Testing & Troubleshooting](/docs/microfrontends/troubleshooting) | Type: Conceptual | Summary: Learn about testing & troubleshooting on Vercel. | Prerequisites: Microfrontends | Topics: microfrontends, troubleshooting
- [Monorepos](/docs/monorepos) | Type: Conceptual | Lastmod: 2026-03-17 | Summary: Vercel provides support for monorepos. Learn how to deploy a monorepo here. | Prerequisites: None | Topics: build & deploy, monorepos
  - [Turborepo](/docs/monorepos/turborepo) | Type: Reference | Lastmod: 2026-02-26 | Summary: Learn about Turborepo, a build system for monorepos that allows you to have faster incremental builds, content-aware hashing, and Remote Caching. | Prerequisites: Monorepos | Topics: monorepos, turborepo
  - [Remote Caching](/docs/monorepos/remote-caching) | Type: Tutorial | Lastmod: 2026-02-26 | Summary: Vercel Remote Cache allows you to share build outputs and artifacts across distributed teams. | Prerequisites: Monorepos | Topics: monorepos, remote caching
  - [Nx](/docs/monorepos/nx) | Type: Tutorial | Lastmod: 2026-03-11 | Summary: Nx is an extensible build system with support for monorepos, integrations, and Remote Caching on Vercel. Learn how to deploy Nx to Vercel with this guide. | Prerequisites: Monorepos | Topics: monorepos, nx
  - [Monorepos FAQ](/docs/monorepos/monorepo-faq) | Type: Reference | Lastmod: 2026-03-11 | Summary: Learn the answer to common questions about deploying monorepos on Vercel. | Prerequisites: Monorepos | Topics: monorepos, monorepo faq
- [Package Managers](/docs/package-managers) | Type: Reference | Lastmod: 2026-03-17 | Summary: Discover the package managers supported by Vercel for dependency management. Learn how Vercel detects and uses npm, Yarn, pnpm, and Bun for optimal build performance. | Prerequisites: None | Topics: build & deploy, package managers
- [Restricting Git Connections to a single Vercel team](/docs/protected-git-scopes) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Information to stop developers from deploying their repositories to a personal Vercel account by using Protected Git Scopes. | Prerequisites: None | Topics: build & deploy, protected git scopes
- [Rolling Releases](/docs/rolling-releases) | Type: Conceptual | Lastmod: 2026-02-19 | Summary: Learn how to use Rolling Releases for more cautious deployments. | Prerequisites: None | Topics: build & deploy, rolling releases
  - [Rolling Release Deployment](/docs/rolling-releases/rolling-release-deployment) | Type: How-to | Lastmod: 2026-02-24 | Summary: Gradually roll out a production deployment using traffic stages, monitoring, and automated abort. | Prerequisites: Rolling Releases | Topics: build & deploy, rolling releases, rolling release deployment
- [Skew Protection](/docs/skew-protection) | Type: Conceptual | Lastmod: 2026-03-16 | Summary: Learn how Vercel's Skew Protection ensures that the client and server stay in sync for any particular deployment. | Prerequisites: None | Topics: build & deploy, skew protection
- [Webhooks](/docs/webhooks) | Type: Conceptual | Lastmod: 2026-03-11 | Summary: Learn how to set up webhooks and use them with Vercel Integrations. | Prerequisites: None | Topics: build & deploy, webhooks
  - [Webhooks API Reference](/docs/webhooks/webhooks-api) | Type: Reference | Lastmod: 2026-03-17 | Summary: Vercel Integrations allow you to subscribe to certain trigger-based events through webhooks. Learn about the supported webhook events and how to use them. | Prerequisites: Webhooks | Topics: webhooks, webhooks api

## CDN

- [Overview](/docs/cdn) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Vercel's CDN is a globally distributed platform that handles routing, caching, security, and compression for every deployment. | Prerequisites: None | Topics: cdn
- [How Vercel CDN works](/docs/how-vercel-cdn-works) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Learn how Vercel's CDN processes requests through routing, caching, and compute layers to deliver your content with low latency. | Prerequisites: None | Topics: cdn, how vercel cdn works
  - [Compression](/docs/how-vercel-cdn-works/compression) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Vercel helps reduce data transfer and improve performance by supporting both Gzip and Brotli compression | Prerequisites: How Vercel CDN works | Topics: cdn, how vercel cdn works, compression
- [Global Network & Regions](/docs/regions) | Type: Reference | Lastmod: 2026-03-05 | Summary: View the list of regions supported by Vercel's CDN and learn about our global infrastructure. | Prerequisites: None | Topics: cdn, regions
- [Routing](/docs/routing) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Learn how Vercel's CDN routes requests through firewall, project routes, and deployment routes before reaching your application. | Prerequisites: None | Topics: cdn, routing
  - [Redirects](/docs/routing/redirects) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Learn how to use redirects on Vercel to instruct Vercel's platform to redirect incoming requests to a new URL. | Prerequisites: Routing | Topics: cdn, routing, redirects
    - [Configuration Redirects](/docs/routing/redirects/configuration-redirects) | Type: Reference | Lastmod: 2026-03-05 | Summary: Learn how to define static redirects in your framework configuration or vercel.json with support for wildcards, pattern matching, and geolocation. | Prerequisites: Routing, Redirects | Topics: routing, redirects
    - [Bulk Redirects](/docs/routing/redirects/bulk-redirects) | Type: Reference | Lastmod: 2026-03-13 | Summary: Learn how to import thousands of simple redirects from CSV, JSON, or JSONL files. | Prerequisites: Routing, Redirects | Topics: cdn, routing, redirects
      - [Getting Started](/docs/routing/redirects/bulk-redirects/getting-started) | Type: How-to | Lastmod: 2026-03-17 | Summary: Learn how to import thousands of simple redirects from CSV, JSON, or JSONL files. | Prerequisites: Routing, Redirects | Topics: cdn, routing, redirects
  - [Rewrites](/docs/routing/rewrites) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Learn how to use rewrites to send users to different URLs without modifying the visible URL. | Prerequisites: Routing | Topics: cdn, routing, rewrites
  - [Project Routing Rules](/docs/routing/project-routing-rules) | Type: How-to | Lastmod: 2026-03-05 | Summary: Add redirects, rewrites, headers, and status codes to your project from the dashboard or API, without deploying new code. | Prerequisites: Routing | Topics: cdn, routing, project routing rules
- [Security](/docs/cdn-security) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Learn how Vercel's CDN secures every request with HTTPS, TLS, DDoS mitigation, firewall protection, and security headers. | Prerequisites: None | Topics: cdn, cdn security
  - [Encryption & TLS](/docs/cdn-security/encryption) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Learn how Vercel encrypts data in transit and at rest. | Prerequisites: Security | Topics: cdn security, encryption
  - [Security Headers](/docs/cdn-security/security-headers) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Learn how the Content Security Policy \(CSP\) offers defense against web vulnerabilities, its key features, and best practices. | Prerequisites: Security | Topics: cdn security, security headers
- [Incremental Static Regeneration](/docs/incremental-static-regeneration) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: ISR serves cached static pages while regenerating content in the background. Vercel\\ | Prerequisites: None | Topics: cdn, incremental static regeneration
  - [Getting Started](/docs/incremental-static-regeneration/quickstart) | Type: Tutorial | Lastmod: 2026-02-23 | Summary: Learn how to set up Incremental Static Regeneration \(ISR\) with time-based and on-demand revalidation. | Prerequisites: Incremental Static Regeneration | Topics: incremental static regeneration, quickstart
  - [Usage & Pricing](/docs/incremental-static-regeneration/limits-and-pricing) | Type: Reference | Lastmod: 2026-02-23 | Summary: Learn about ISR costs, usage metrics, and strategies to optimize your ISR reads and writes. | Prerequisites: Incremental Static Regeneration | Topics: incremental static regeneration, limits and pricing
  - [Request Collapsing](/docs/incremental-static-regeneration/request-collapsing) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Learn how Vercel's CDN shields your origin during traffic surges for uncached routes. | Prerequisites: Incremental Static Regeneration | Topics: cdn, incremental static regeneration, request collapsing
- [Caching](/docs/caching) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Learn how Vercel caches content across multiple layers to deliver fast responses and reduce load on your backend. | Prerequisites: None | Topics: cdn, caching
  - [CDN Cache](/docs/caching/cdn-cache) | Type: Conceptual | Lastmod: 2026-03-17 | Summary: Learn how Vercel's CDN cache stores your content across a global network to reduce latency and origin load. | Prerequisites: Caching | Topics: cdn, caching, cdn cache
    - [Purge CDN Cache](/docs/caching/cdn-cache/purge) | Type: Reference | Lastmod: 2026-03-05 | Summary: Learn how to invalidate and delete cached content on Vercel's CDN, including cache keys and manual purging options. | Prerequisites: Caching, CDN Cache | Topics: caching, cdn cache
  - [Runtime Cache](/docs/caching/runtime-cache) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Vercel Runtime Cache is a specialized cache that stores responses from data fetches in Vercel functions | Prerequisites: Caching | Topics: cdn, caching, runtime cache
    - [Data Cache](/docs/caching/runtime-cache/data-cache) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Vercel Data Cache is a specialized cache that stores responses from data fetches in Next.js App Router | Prerequisites: Caching, Runtime Cache | Topics: cdn, caching, runtime cache
  - [Cache-Control Headers](/docs/caching/cache-control-headers) | Type: Reference | Lastmod: 2026-03-05 | Summary: Learn about the cache-control headers sent to each Vercel deployment and how to use them to control the caching behavior of your application. | Prerequisites: Caching | Topics: caching, cache control headers
- [System Headers](/docs/headers) | Type: Reference | Lastmod: 2026-03-05 | Summary: This reference covers the list of request, response, cache-control, and custom response headers included with deployments with Vercel. | Prerequisites: None | Topics: cdn, headers
  - [Request Headers](/docs/headers/request-headers) | Type: Reference | Lastmod: 2025-12-13 | Summary: Learn about the request headers sent to each Vercel deployment and how to use them to process requests before sending a response. | Prerequisites: System Headers | Topics: headers, request headers
  - [Response Headers](/docs/headers/response-headers) | Type: Reference | Lastmod: 2026-03-05 | Summary: Learn about the response headers sent to each Vercel deployment and how to use them to process responses before sending a response. | Prerequisites: System Headers | Topics: headers, response headers
- [Image Optimization](/docs/image-optimization) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Transform and optimize images to improve page load performance. | Prerequisites: None | Topics: cdn, image optimization
  - [Getting Started](/docs/image-optimization/quickstart) | Type: Tutorial | Lastmod: 2025-10-14 | Summary: Learn how you can leverage Vercel Image Optimization in your projects. | Prerequisites: Image Optimization | Topics: image optimization, quickstart
  - [Limits and Pricing](/docs/image-optimization/limits-and-pricing) | Type: Reference | Lastmod: 2026-02-23 | Summary: This page outlines information on the limits that are applicable when using Image Optimization, and the costs they can incur. | Prerequisites: Image Optimization | Topics: image optimization, limits and pricing
  - [Managing Usage & Costs](/docs/image-optimization/managing-image-optimization-costs) | Type: Reference | Lastmod: 2026-02-26 | Summary: Learn how to measure and manage Image Optimization usage with this guide to avoid any unexpected costs. | Prerequisites: Image Optimization | Topics: image optimization, managing image optimization costs
  - [Legacy Pricing](/docs/image-optimization/legacy-pricing) | Type: Reference | Lastmod: 2026-02-25 | Summary: This page outlines information on the pricing and limits for the source images-based legacy option. | Prerequisites: Image Optimization | Topics: image optimization, legacy pricing
- [Custom Error Pages](/docs/custom-error-pages) | Type: How-to | Lastmod: 2026-02-17 | Summary: Learn how to configure custom error pages for 5xx server errors on Vercel. | Prerequisites: None | Topics: cdn, custom error pages
- [Pricing & Usage](/docs/manage-cdn-usage) | Type: Reference | Lastmod: 2026-03-05 | Summary: Understand CDN pricing resources, monitor usage from your dashboard, and optimize Fast Data Transfer, Fast Origin Transfer, and CDN Requests. | Prerequisites: None | Topics: cdn, manage cdn usage
- [CLI](/docs/cli) | Type: Conceptual | Lastmod: 2026-03-11 | Summary: Learn how to use the Vercel command-line interface \(CLI\) to manage and configure your Vercel Projects from the command line. | Prerequisites: None | Topics: cli
  - [Deploying from CLI](/docs/cli/deploying-from-cli) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to deploy your Vercel Projects from Vercel CLI using the vercel or vercel deploy commands. | Prerequisites: CLI | Topics: cli, deploying from cli
  - [Project Linking](/docs/cli/project-linking) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to link existing Vercel Projects with Vercel CLI. | Prerequisites: CLI | Topics: cli, project linking
  - [Telemetry](/docs/cli/about-telemetry) | Type: Reference | Lastmod: 2026-03-17 | Summary: Vercel CLI collects telemetry data about general usage. | Prerequisites: CLI | Topics: cli, about telemetry
  - [Global Options](/docs/cli/global-options) | Type: Reference | Lastmod: 2026-03-17 | Summary: Global options are commonly available to use with multiple Vercel CLI commands. Learn about Vercel CLI's global options here. | Prerequisites: CLI | Topics: cli, global options
  - [vercel activity](/docs/cli/activity) | Type: Reference | Lastmod: 2026-03-17 | Summary: View activity events for your Vercel project or team, filtered by type, date range, and project. | Prerequisites: CLI | Topics: cli, activity
  - [vercel alias](/docs/cli/alias) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to apply custom domain aliases to your Vercel deployments using the vercel alias CLI command. | Prerequisites: CLI | Topics: cli, alias
  - [vercel api](/docs/cli/api) | Type: Reference | Lastmod: 2026-03-11 | Summary: Learn how to make authenticated HTTP requests to the Vercel API using the vercel api CLI command. | Prerequisites: CLI | Topics: cli, api
  - [vercel bisect](/docs/cli/bisect) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to perform a binary search on your deployments to help surface issues using the vercel bisect CLI command. | Prerequisites: CLI | Topics: cli, bisect
  - [vercel blob](/docs/cli/blob) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to interact with Vercel Blob storage using the vercel blob CLI command. | Prerequisites: CLI | Topics: cli, blob
  - [vercel build](/docs/cli/build) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to build a Vercel Project locally or in your own CI environment using the vercel build CLI command. | Prerequisites: CLI | Topics: cli, build
  - [vercel buy](/docs/cli/buy) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to purchase Vercel products like credits, addons, subscriptions, and domains using the vercel buy CLI command. | Prerequisites: CLI | Topics: cli, buy
  - [vercel cache](/docs/cli/cache) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to manage cache for your project using the vercel cache CLI command. | Prerequisites: CLI | Topics: cli, cache
  - [vercel certs](/docs/cli/certs) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to manage certificates for your domains using the vercel certs CLI command. | Prerequisites: CLI | Topics: cli, certs
  - [vercel contract](/docs/cli/contract) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to view contract commitment information for your Vercel account using the vercel contract CLI command. | Prerequisites: CLI | Topics: cli, contract
  - [vercel curl](/docs/cli/curl) | Type: Reference | Lastmod: 2026-02-10 | Summary: Learn how to make HTTP requests to your Vercel deployments with automatic deployment protection bypass using the vercel curl CLI command. | Prerequisites: CLI | Topics: cli, curl
  - [vercel deploy](/docs/cli/deploy) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to deploy your Vercel projects using the vercel deploy CLI command. | Prerequisites: CLI | Topics: cli, deploy
  - [vercel dev](/docs/cli/dev) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to replicate the Vercel deployment environment locally and test your Vercel Project before deploying using the vercel dev CLI command. | Prerequisites: CLI | Topics: cli, dev
  - [vercel dns](/docs/cli/dns) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to manage your DNS records for your domains using the vercel dns CLI command. | Prerequisites: CLI | Topics: cli, dns
  - [vercel domains](/docs/cli/domains) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to buy, sell, transfer, and manage your domains using the vercel domains CLI command. | Prerequisites: CLI | Topics: cli, domains
  - [vercel env](/docs/cli/env) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to manage your environment variables in your Vercel Projects using the vercel env CLI command. | Prerequisites: CLI | Topics: cli, env
  - [vercel flags](/docs/cli/flags) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to manage feature flags for your Vercel project using the vercel flags CLI command. | Prerequisites: CLI | Topics: cli, flags
  - [vercel git](/docs/cli/git) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to manage your Git provider connections using the vercel git CLI command. | Prerequisites: CLI | Topics: cli, git
  - [vercel guidance](/docs/cli/guidance) | Type: Reference | Lastmod: 2026-03-17 | Summary: Enable or disable guidance messages in the Vercel CLI using the vercel guidance command. | Prerequisites: CLI | Topics: cli, guidance
  - [vercel help](/docs/cli/help) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to use the vercel help CLI command to get information about all available Vercel CLI commands. | Prerequisites: CLI | Topics: cli, help
  - [vercel httpstat](/docs/cli/httpstat) | Type: Reference | Lastmod: 2026-02-10 | Summary: Learn how to visualize HTTP request timing statistics for your Vercel deployments using the vercel httpstat CLI command. | Prerequisites: CLI | Topics: cli, httpstat
  - [vercel init](/docs/cli/init) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to initialize Vercel supported framework examples locally using the vercel init CLI command. | Prerequisites: CLI | Topics: cli, init
  - [vercel inspect](/docs/cli/inspect) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to retrieve information about your Vercel deployments using the vercel inspect CLI command. | Prerequisites: CLI | Topics: cli, inspect
  - [vercel install](/docs/cli/install) | Type: Reference | Lastmod: 2026-02-27 | Summary: Learn how to install marketplace native integrations and provision resources with the vercel install CLI command. | Prerequisites: CLI | Topics: cli, install
  - [vercel integration](/docs/cli/integration) | Type: Reference | Lastmod: 2026-02-27 | Summary: Learn how to manage marketplace native integrations, provision resources, and discover available products using the vercel integration CLI command. | Prerequisites: CLI | Topics: cli, integration
  - [vercel integration-resource](/docs/cli/integration-resource) | Type: Reference | Lastmod: 2026-02-27 | Summary: Learn how to manage marketplace native integration resources using the vercel integration-resource CLI command. | Prerequisites: CLI | Topics: cli, integration resource
  - [vercel link](/docs/cli/link) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to link a local directory to a Vercel Project using the vercel link CLI command. | Prerequisites: CLI | Topics: cli, link
  - [vercel list](/docs/cli/list) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to list out all recent deployments for the current Vercel Project using the vercel list CLI command. | Prerequisites: CLI | Topics: cli, list
  - [vercel login](/docs/cli/login) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to login into your Vercel account using the vercel login CLI command. | Prerequisites: CLI | Topics: cli, login
  - [vercel logout](/docs/cli/logout) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to logout from your Vercel account using the vercel logout CLI command. | Prerequisites: CLI | Topics: cli, logout
  - [vercel logs](/docs/cli/logs) | Type: Reference | Lastmod: 2026-02-10 | Summary: View and filter request logs for your Vercel project, or stream live runtime logs from a deployment. | Prerequisites: CLI | Topics: cli, logs
  - [vercel mcp](/docs/cli/mcp) | Type: Reference | Lastmod: 2026-03-17 | Summary: Set up Model Context Protocol \(MCP\) usage with a Vercel project using the vercel mcp CLI command. | Prerequisites: CLI | Topics: cli, mcp
  - [vercel microfrontends](/docs/cli/microfrontends) | Type: Reference | Lastmod: 2026-03-17 | Summary: Manage microfrontends configuration from the CLI. Learn how to pull configuration for local development. | Prerequisites: CLI | Topics: cli, microfrontends
  - [vercel open](/docs/cli/open) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to open your current project in the Vercel Dashboard using the vercel open CLI command. | Prerequisites: CLI | Topics: cli, open
  - [vercel project](/docs/cli/project) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to list, add, remove, and manage your Vercel Projects using the vercel project CLI command. | Prerequisites: CLI | Topics: cli, project
  - [vercel promote](/docs/cli/promote) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to promote an existing deployment using the vercel promote CLI command. | Prerequisites: CLI | Topics: cli, promote
  - [vercel pull](/docs/cli/pull) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to update your local project with remote environment variables using the vercel pull CLI command. | Prerequisites: CLI | Topics: cli, pull
  - [vercel redeploy](/docs/cli/redeploy) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to redeploy your project using the vercel redeploy CLI command. | Prerequisites: CLI | Topics: cli, redeploy
  - [vercel redirects](/docs/cli/redirects) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to manage project-level redirects using the vercel redirects CLI command. | Prerequisites: CLI | Topics: cli, redirects
  - [vercel remove](/docs/cli/remove) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to remove a deployment using the vercel remove CLI command. | Prerequisites: CLI | Topics: cli, remove
  - [vercel rollback](/docs/cli/rollback) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to roll back your production deployments to previous deployments using the vercel rollback CLI command. | Prerequisites: CLI | Topics: cli, rollback
  - [vercel rolling-release](/docs/cli/rolling-release) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to manage your project's rolling releases using the vercel rolling-release CLI command. | Prerequisites: CLI | Topics: cli, rolling release
  - [vercel routes](/docs/cli/routes) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to manage project-level routing rules using the vercel routes CLI command. | Prerequisites: CLI | Topics: cli, routes
  - [vercel switch](/docs/cli/switch) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to switch between different team scopes using the vercel switch CLI command. | Prerequisites: CLI | Topics: cli, switch
  - [vercel target](/docs/cli/target) | Type: Reference | Lastmod: 2026-03-17 | Summary: Work with custom environments using the --target flag in Vercel CLI. | Prerequisites: CLI | Topics: cli, target
  - [vercel teams](/docs/cli/teams) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to list, add, remove, and manage your teams using the vercel teams CLI command. | Prerequisites: CLI | Topics: cli, teams
  - [vercel telemetry](/docs/cli/telemetry) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to manage telemetry collection. | Prerequisites: CLI | Topics: cli, telemetry
  - [vercel usage](/docs/cli/usage) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to view billing usage and costs, for your Vercel account using the vercel usage CLI command. | Prerequisites: CLI | Topics: cli, usage
  - [vercel webhooks](/docs/cli/webhooks) | Type: Reference | Lastmod: 2026-02-10 | Summary: Learn how to manage webhooks for your Vercel account using the vercel webhooks CLI command. | Prerequisites: CLI | Topics: cli, webhooks
  - [vercel whoami](/docs/cli/whoami) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to display the username of the currently logged in user with the vercel whoami CLI command. | Prerequisites: CLI | Topics: cli, whoami

## Collaboration

- [Comments](/docs/comments) | Type: Conceptual | Lastmod: 2026-02-17 | Summary: Comments allow teams and invited participants to give direct feedback on preview deployments. Learn more about Comments in this overview. | Prerequisites: None | Topics: collaboration, comments
  - [Enabling Comments](/docs/comments/how-comments-work) | Type: How-to | Lastmod: 2025-09-24 | Summary: Learn when and where Comments are available, and how to enable and disable Comments at the account, project, and session or interface levels. | Prerequisites: Comments | Topics: comments, how comments work
  - [Using Comments](/docs/comments/using-comments) | Type: How-to | Lastmod: 2026-02-17 | Summary: This guide will help you get started with using Comments with your Vercel Preview Deployments. | Prerequisites: Comments | Topics: comments, using comments
  - [Managing Comments](/docs/comments/managing-comments) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to manage Comments on your Preview Deployments from Team members and invited collaborators. | Prerequisites: Comments | Topics: comments, managing comments
  - [Integrations](/docs/comments/integrations) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how Comments integrates with Git providers like GitHub, GitLab, and BitBucket, as well as Vercel's Slack app. | Prerequisites: Comments | Topics: comments, integrations
- [Draft Mode](/docs/draft-mode) | Type: How-to | Lastmod: 2025-09-24 | Summary: Vercel's Draft Mode enables you to view your unpublished headless CMS content on your site before publishing it. | Prerequisites: None | Topics: collaboration, draft mode
- [Edit Mode](/docs/edit-mode) | Type: Conceptual | Lastmod: 2025-03-12 | Summary: Discover how Vercel's Edit Mode enhances content management for headless CMSs, enabling real-time editing, and seamless collaboration. | Prerequisites: None | Topics: collaboration, edit mode
- [Toolbar](/docs/vercel-toolbar) | Type: Reference | Lastmod: 2025-09-24 | Summary: Learn how to use the Vercel Toolbar to leave feedback, navigate through important dashboard pages, share deployments, use Draft Mode for previewing unpublished content, and Edit Mode for editing content in real-time. | Prerequisites: None | Topics: collaboration, vercel toolbar
  - [Add to Environments](/docs/vercel-toolbar/in-production-and-localhost) | Type: Conceptual | Lastmod: 2025-05-23 | Summary: Learn how to use the Vercel Toolbar in production and local environments. | Prerequisites: Toolbar | Topics: vercel toolbar, in production and localhost
    - [Add to Localhost](/docs/vercel-toolbar/in-production-and-localhost/add-to-localhost) | Type: How-to | Lastmod: 2026-02-17 | Summary: Learn how to use the Vercel Toolbar in your local environment. | Prerequisites: Toolbar, Add to Environments | Topics: vercel toolbar, in production and localhost
    - [Add to Production](/docs/vercel-toolbar/in-production-and-localhost/add-to-production) | Type: How-to | Lastmod: 2026-03-17 | Summary: Learn how to add the Vercel Toolbar to your production environment and how your team members can use tooling to access the toolbar. | Prerequisites: Toolbar, Add to Environments | Topics: vercel toolbar, in production and localhost
  - [Managing Toolbar](/docs/vercel-toolbar/managing-toolbar) | Type: How-to | Lastmod: 2025-07-18 | Summary: Learn how to enable or disable the Vercel Toolbar for your team, project, and session. | Prerequisites: Toolbar | Topics: vercel toolbar, managing toolbar
  - [Browser Extensions](/docs/vercel-toolbar/browser-extension) | Type: Reference | Lastmod: 2025-03-04 | Summary: The browser extensions enable you to use the toolbar in production environments, take screenshots and attach them to comments, and set personal preferences for how the toolbar behaves. | Prerequisites: Toolbar | Topics: vercel toolbar, browser extension
  - [Accessibility Audit Tool](/docs/vercel-toolbar/accessibility-audit-tool) | Type: How-to | Lastmod: 2025-09-24 | Summary: Learn how to use the Accessibility Audit Tool to automatically check the Web Content Accessibility Guidelines 2.0 level A and AA rules. | Prerequisites: Toolbar | Topics: vercel toolbar, accessibility audit tool
  - [Interaction Timing Tool](/docs/vercel-toolbar/interaction-timing-tool) | Type: How-to | Lastmod: 2025-07-18 | Summary: The interaction timing tool allows you to inspect in detail each interaction's latency and get notified for interactions taking >200ms. | Prerequisites: Toolbar | Topics: vercel toolbar, interaction timing tool
  - [Layout Shift Tool](/docs/vercel-toolbar/layout-shift-tool) | Type: Reference | Lastmod: 2025-09-24 | Summary: The layout shift tool gives you insight into any elements that may cause layout shifts on the page. | Prerequisites: Toolbar | Topics: vercel toolbar, layout shift tool

## Compute

- [Fluid Compute](/docs/fluid-compute) | Type: Reference | Lastmod: 2026-01-29 | Summary: Learn about fluid compute, an execution model for Vercel Functions that provides a more flexible and efficient way to run your functions. | Prerequisites: None | Topics: compute, fluid compute
- [Functions](/docs/functions) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Run server-side code on Vercel without managing a server. | Prerequisites: None | Topics: compute, functions
  - [Getting Started](/docs/functions/quickstart) | Type: Tutorial | Lastmod: 2026-02-11 | Summary: Build your first Vercel Function in a few steps. | Prerequisites: Functions | Topics: functions, quickstart
  - [Streaming](/docs/functions/streaming-functions) | Type: How-to | Lastmod: 2026-02-13 | Summary: Learn how to stream responses from Vercel Functions. | Prerequisites: Functions | Topics: functions, streaming functions
  - [Runtimes](/docs/functions/runtimes) | Type: Reference | Lastmod: 2026-02-18 | Summary: Runtimes transform your source code into Functions, which are served by our CDN. Learn about the official runtimes supported by Vercel. | Prerequisites: Functions | Topics: functions, runtimes
    - [Node.js](/docs/functions/runtimes/node-js) | Type: Reference | Lastmod: 2025-12-01 | Summary: Learn how to use the Node.js runtime with Vercel Functions to create functions. | Prerequisites: Functions, Runtimes | Topics: functions, runtimes
      - [Advanced Node.js Usage](/docs/functions/runtimes/node-js/advanced-node-configuration) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn about advanced configurations for Vercel functions on Vercel. | Prerequisites: Functions, Runtimes | Topics: functions, runtimes
      - [Supported Node.js versions](/docs/functions/runtimes/node-js/node-js-versions) | Type: Reference | Lastmod: 2026-02-27 | Summary: Learn about the supported Node.js versions on Vercel. | Prerequisites: Functions, Runtimes | Topics: functions, runtimes
    - [Bun](/docs/functions/runtimes/bun) | Type: Reference | Lastmod: 2025-11-10 | Summary: Learn how to use the Bun runtime with Vercel Functions to create fast, efficient functions. | Prerequisites: Functions, Runtimes | Topics: functions, runtimes
    - [Python](/docs/functions/runtimes/python) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to use the Python runtime to run Python applications on Vercel. | Prerequisites: Functions, Runtimes | Topics: functions, runtimes
    - [Rust](/docs/functions/runtimes/rust) | Type: Reference | Lastmod: 2025-12-08 | Summary: Build fast, memory-safe serverless functions with Rust on Vercel. | Prerequisites: Functions, Runtimes | Topics: functions, runtimes
    - [Go](/docs/functions/runtimes/go) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to use the Go runtime to run Go APIs on Vercel. | Prerequisites: Functions, Runtimes | Topics: functions, runtimes
    - [Ruby](/docs/functions/runtimes/ruby) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to use the Ruby runtime to compile Ruby Vercel Functions on Vercel. | Prerequisites: Functions, Runtimes | Topics: functions, runtimes
    - [Wasm](/docs/functions/runtimes/wasm) | Type: How-to | Lastmod: 2025-12-08 | Summary: Learn how to use WebAssembly \(Wasm\) to enable low-level languages to run on Vercel Functions and Routing Middleware. | Prerequisites: Functions, Runtimes | Topics: functions, runtimes
    - [Edge Runtime](/docs/functions/runtimes/edge) | Type: Reference | Lastmod: 2025-12-08 | Summary: Learn about the Edge runtime, an environment in which Vercel Functions can run. | Prerequisites: Functions, Runtimes | Topics: functions, runtimes
  - [Configuring Functions](/docs/functions/configuring-functions) | Type: How-to | Lastmod: 2025-06-25 | Summary: Learn how to configure the runtime, region, maximum duration, and memory for Vercel Functions. | Prerequisites: Functions | Topics: functions, configuring functions
    - [Duration](/docs/functions/configuring-functions/duration) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to set the maximum duration of a Vercel Function. | Prerequisites: Functions, Configuring Functions | Topics: functions, configuring functions
    - [Memory](/docs/functions/configuring-functions/memory) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to set the memory / CPU of a Vercel Function. | Prerequisites: Functions, Configuring Functions | Topics: functions, configuring functions
    - [Runtime](/docs/functions/configuring-functions/runtime) | Type: How-to | Lastmod: 2026-03-17 | Summary: Learn how to configure the runtime for Vercel Functions. | Prerequisites: Functions, Configuring Functions | Topics: functions, configuring functions
    - [Region](/docs/functions/configuring-functions/region) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to configure regions for Vercel Functions. | Prerequisites: Functions, Configuring Functions | Topics: functions, configuring functions
    - [Advanced Configuration](/docs/functions/configuring-functions/advanced-configuration) | Type: Conceptual | Lastmod: 2025-05-21 | Summary: Learn how to add utility files to the /api directory, and bundle Vercel Functions. | Prerequisites: Functions, Configuring Functions | Topics: functions, configuring functions
  - [API Reference](/docs/functions/functions-api-reference) | Type: Reference | Lastmod: 2026-02-18 | Summary: Learn about available APIs when working with Vercel Functions. | Prerequisites: Functions | Topics: functions, functions api reference
    - [Node.js](/docs/functions/functions-api-reference/vercel-functions-package) | Type: Reference | Lastmod: 2026-01-23 | Summary: Learn about available APIs when working with Vercel Functions. | Prerequisites: Functions, API Reference | Topics: functions, functions api reference
    - [Python](/docs/functions/functions-api-reference/vercel-sdk-python) | Type: Reference | Lastmod: 2025-10-23 | Summary: Learn about available APIs when working with Vercel Functions in Python. | Prerequisites: Functions, API Reference | Topics: functions, functions api reference
  - [Logs](/docs/functions/logs) | Type: Reference | Lastmod: 2026-02-26 | Summary: Use runtime logs to debug and monitor your Vercel Functions. | Prerequisites: Functions | Topics: functions, logs
  - [Limits](/docs/functions/limitations) | Type: Reference | Lastmod: 2026-02-24 | Summary: Learn about the limits and restrictions of using Vercel Functions with the Node.js runtime. | Prerequisites: Functions | Topics: functions, limitations
  - [Concurrency Scaling](/docs/functions/concurrency-scaling) | Type: Reference | Lastmod: 2025-09-05 | Summary: Learn how Vercel automatically scales your functions to handle traffic surges. | Prerequisites: Functions | Topics: functions, concurrency scaling
  - [Debug Slow Functions](/docs/functions/debug-slow-functions) | Type: How-to | Lastmod: 2026-02-24 | Summary: Diagnose and fix slow Vercel Functions using CLI tools, logs, and timing analysis. | Prerequisites: Functions | Topics: compute, functions, debug slow functions
  - [Pricing](/docs/functions/usage-and-pricing) | Type: Reference | Lastmod: 2026-02-18 | Summary: Learn about usage and pricing for fluid compute on Vercel. | Prerequisites: Functions | Topics: functions, usage and pricing
    - [Legacy Usage & Pricing](/docs/functions/usage-and-pricing/legacy-pricing) | Type: Reference | Lastmod: 2026-03-02 | Summary: Learn about legacy usage and pricing for Vercel Functions. | Prerequisites: Functions, Pricing | Topics: functions, usage and pricing
- [Routing Middleware](/docs/routing-middleware) | Type: Conceptual | Lastmod: 2026-01-28 | Summary: Learn how you can use Routing Middleware, code that executes before a request is processed on a site, to provide speed and personalization to your users. | Prerequisites: None | Topics: compute, routing middleware
  - [Getting Started](/docs/routing-middleware/getting-started) | Type: Tutorial | Lastmod: 2026-02-26 | Summary: Learn how you can use Routing Middleware, code that executes before a request is processed on a site, to provide speed and personalization to your users. | Prerequisites: Routing Middleware | Topics: cdn, routing middleware, getting started
  - [API](/docs/routing-middleware/api) | Type: Reference | Lastmod: 2026-01-28 | Summary: Learn how you can use Routing Middleware, code that executes before a request is processed on a site, to provide speed and personalization to your users. | Prerequisites: Routing Middleware | Topics: routing middleware, api
- [Cron Jobs](/docs/cron-jobs) | Type: How-to | Lastmod: 2025-06-25 | Summary: Learn about cron jobs, how they work, and how to use them on Vercel. | Prerequisites: None | Topics: compute, cron jobs
  - [Getting Started](/docs/cron-jobs/quickstart) | Type: Tutorial | Lastmod: 2026-03-17 | Summary: Learn how to schedule cron jobs to run at specific times or intervals. | Prerequisites: Cron Jobs | Topics: cron jobs, quickstart
  - [Managing Cron Jobs](/docs/cron-jobs/manage-cron-jobs) | Type: Reference | Lastmod: 2026-02-27 | Summary: Learn how to manage Cron Jobs effectively in Vercel. Explore cron job duration, error handling, deployments, concurrency control, local execution, and more to optimize your serverless workflows. | Prerequisites: Cron Jobs | Topics: cron jobs, manage cron jobs
  - [Usage & Pricing](/docs/cron-jobs/usage-and-pricing) | Type: Reference | Lastmod: 2026-03-04 | Summary: Learn about cron jobs usage and pricing details. | Prerequisites: Cron Jobs | Topics: cron jobs, usage and pricing
- [OG Image Generation](/docs/og-image-generation) | Type: Reference | Lastmod: 2026-02-17 | Summary: Learn how to optimize social media image generation through the Open Graph Protocol and @vercel/og library. | Prerequisites: None | Topics: compute, og image generation
  - [@vercel/og](/docs/og-image-generation/og-image-api) | Type: Reference | Lastmod: 2025-07-18 | Summary: This reference provides information on how the @vercel/og package works on Vercel. | Prerequisites: OG Image Generation | Topics: og image generation, og image api
  - [Examples](/docs/og-image-generation/examples) | Type: Conceptual | Lastmod: 2025-04-28 | Summary: Learn how to use the @vercel/og library with examples. | Prerequisites: OG Image Generation | Topics: compute, og image generation, examples
- [Sandbox](/docs/vercel-sandbox) | Type: Conceptual | Lastmod: 2026-03-13 | Summary: Vercel Sandbox allows you to run arbitrary code in isolated, ephemeral Linux VMs. | Prerequisites: None | Topics: compute, vercel sandbox
  - [Quickstart](/docs/vercel-sandbox/quickstart) | Type: Tutorial | Lastmod: 2026-02-17 | Summary: Learn how to run your first code in a Vercel Sandbox. | Prerequisites: Sandbox | Topics: vercel sandbox, quickstart
  - [Concepts](/docs/vercel-sandbox/concepts) | Type: Conceptual | Lastmod: 2026-02-17 | Summary: Learn how Vercel Sandboxes provide on-demand, isolated compute environments for running untrusted code, testing applications, and executing AI-generated scripts. | Prerequisites: Sandbox | Topics: vercel sandbox, concepts
    - [Authentication](/docs/vercel-sandbox/concepts/authentication) | Type: Conceptual | Lastmod: 2026-01-30 | Summary: Learn how to authenticate with Vercel Sandbox using OIDC tokens or access tokens. | Prerequisites: Sandbox, Concepts | Topics: concepts, vercel sandbox
    - [Snapshots](/docs/vercel-sandbox/concepts/snapshots) | Type: Conceptual | Lastmod: 2026-02-17 | Summary: Save and restore sandbox state with snapshots for faster startups and environment sharing. | Prerequisites: Sandbox, Concepts | Topics: concepts, vercel sandbox
    - [Firewall](/docs/vercel-sandbox/concepts/firewall) | Type: Conceptual | Lastmod: 2026-02-23 | Summary: Define network policies on sandboxes, preventing data exfiltration. | Prerequisites: Sandbox, Concepts | Topics: concepts, vercel sandbox
    - [Persistent Sandboxes](/docs/vercel-sandbox/concepts/persistent-sandboxes) | Type: Conceptual | Summary: Learn about persistent sandboxes on Vercel. | Prerequisites: Sandbox, Concepts | Topics: vercel sandbox, concepts
    - [Tags](/docs/vercel-sandbox/concepts/tags) | Type: Conceptual | Summary: Learn about tags on Vercel. | Prerequisites: Sandbox, Concepts | Topics: vercel sandbox, concepts
  - [Examples](/docs/vercel-sandbox/working-with-sandbox) | Type: Conceptual | Lastmod: 2026-03-10 | Summary: Task-oriented guides for common Vercel Sandbox operations. | Prerequisites: Sandbox | Topics: vercel sandbox, working with sandbox
  - [SDK Reference](/docs/vercel-sandbox/sdk-reference) | Type: Conceptual | Lastmod: 2026-03-09 | Summary: A comprehensive reference for the Vercel Sandbox SDK, which allows you to run code in a secure, isolated environment. | Prerequisites: Sandbox | Topics: vercel sandbox, sdk reference
  - [CLI Reference](/docs/vercel-sandbox/cli-reference) | Type: Reference | Lastmod: 2026-03-17 | Summary: Based on the Docker CLI, you can use the Sandbox CLI to manage your Vercel Sandbox from the command line. | Prerequisites: Sandbox | Topics: vercel sandbox, cli reference
  - [System Specifications](/docs/vercel-sandbox/system-specifications) | Type: Conceptual | Lastmod: 2026-01-30 | Summary: Detailed specifications for the Vercel Sandbox environment. | Prerequisites: Sandbox | Topics: vercel sandbox, system specifications
  - [Pricing and Limits](/docs/vercel-sandbox/pricing) | Type: Reference | Lastmod: 2026-03-14 | Summary: Understand how Vercel Sandbox billing works, what's included in each plan, and the limits that apply. | Prerequisites: Sandbox | Topics: vercel sandbox, pricing
  - [Run Commands in Vercel Sandbox](/docs/vercel-sandbox/run-commands-in-sandbox) | Type: How-to | Lastmod: 2026-02-24 | Summary: Create isolated sandbox environments to run builds, tests, and commands safely. | Prerequisites: Sandbox | Topics: compute, vercel sandbox, run commands in sandbox
- [Queues](/docs/queues) | Type: Conceptual | Lastmod: 2026-03-03 | Summary: Durable event streaming for serverless. Publish messages to topics and process them reliably with managed consumer groups, automatic scaling, and built-in retries. | Prerequisites: None | Topics: compute, queues
  - [Quickstart](/docs/queues/quickstart) | Type: Tutorial | Lastmod: 2026-02-27 | Summary: Set up Vercel Queues with the SDK. | Prerequisites: Queues | Topics: queues, quickstart
  - [Concepts](/docs/queues/concepts) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Learn delivery, retries, visibility timeouts, and deployment isolation in Vercel Queues. | Prerequisites: Queues | Topics: queues, concepts
  - [SDK Reference](/docs/queues/sdk) | Type: Reference | Lastmod: 2026-02-27 | Summary: Publish and consume messages with the @vercel/queue SDK. | Prerequisites: Queues | Topics: queues, sdk
  - [API Reference](/docs/queues/api) | Type: Reference | Lastmod: 2026-02-27 | Summary: HTTP API reference for Vercel Queues. Publish, consume, acknowledge, and manage messages. | Prerequisites: Queues | Topics: queues, api
  - [Observability](/docs/queues/observability) | Type: How-to | Lastmod: 2026-03-03 | Summary: Monitor queue throughput, message age, and consumer performance to optimize your queue-based workflows. | Prerequisites: Queues | Topics: queues, observability
  - [Poll Mode](/docs/queues/poll-mode) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Consume messages from Vercel Queues by polling on your own schedule, from any environment. | Prerequisites: Queues | Topics: queues, poll mode
  - [Pricing and Limits](/docs/queues/pricing) | Type: Reference | Lastmod: 2026-02-27 | Summary: Understand how Vercel Queues billing works, what's included, and which service limits apply. | Prerequisites: Queues | Topics: queues, pricing
- [Workflow](/docs/workflow) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Build durable, reliable, and observable applications and AI agents with the Workflow SDK. | Prerequisites: None | Topics: compute, workflow
- [Flags](/docs/flags) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Control feature visibility, run experiments, and ship with confidence using Vercel's feature flags platform. | Prerequisites: None | Topics: flags
  - [Vercel Flags](/docs/flags/vercel-flags) | Type: Conceptual | Lastmod: 2026-02-11 | Summary: Use Vercel as your feature flag provider to create and manage flags, define targeting rules, and run experiments directly from the dashboard. | Prerequisites: Flags | Topics: flags, vercel flags
    - [Getting Started](/docs/flags/vercel-flags/quickstart) | Type: Tutorial | Lastmod: 2026-03-06 | Summary: Create your first feature flag and evaluate it in your application using the Flags SDK, OpenFeature, or the core library. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
    - [Dashboard](/docs/flags/vercel-flags/dashboard) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to manage your feature flags using the Vercel Dashboard. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
      - [Feature Flag](/docs/flags/vercel-flags/dashboard/feature-flag) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to configure individual feature flags in the Vercel Dashboard. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
      - [Entities](/docs/flags/vercel-flags/dashboard/entities) | Type: How-to | Lastmod: 2026-02-26 | Summary: Define entities and their attributes for precise feature flag targeting. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
      - [Segments](/docs/flags/vercel-flags/dashboard/segments) | Type: How-to | Lastmod: 2026-02-26 | Summary: Create reusable user segments for targeting feature flags. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
      - [SDK Keys](/docs/flags/vercel-flags/dashboard/sdk-keys) | Type: How-to | Lastmod: 2026-02-27 | Summary: Manage SDK Keys that connect your application to Vercel Flags. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
      - [Drafts](/docs/flags/vercel-flags/dashboard/drafts) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how draft flags work and how to promote them to Vercel Flags. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
      - [Archive](/docs/flags/vercel-flags/dashboard/archive) | Type: How-to | Lastmod: 2026-02-26 | Summary: Archive unused feature flags and restore them when needed. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
    - [SDKs](/docs/flags/vercel-flags/sdks) | Type: Conceptual | Lastmod: 2026-02-11 | Summary: Learn how to integrate Vercel Flags into your application using the Flags SDK, OpenFeature, or the core library. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
      - [Flags SDK](/docs/flags/vercel-flags/sdks/flags-sdk) | Type: How-to | Lastmod: 2026-02-11 | Summary: Integrate Vercel Flags into your Next.js or SvelteKit application using the Flags SDK. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
      - [OpenFeature](/docs/flags/vercel-flags/sdks/openfeature) | Type: How-to | Lastmod: 2026-02-11 | Summary: Use the vendor-neutral OpenFeature API with Vercel Flags as your provider. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
      - [Core](/docs/flags/vercel-flags/sdks/core) | Type: How-to | Lastmod: 2026-02-11 | Summary: Use the Vercel Flags core evaluation library directly for custom setups. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
    - [Limits and Pricing](/docs/flags/vercel-flags/limits-and-pricing) | Type: Reference | Lastmod: 2026-02-23 | Summary: Learn about limits and pricing for Vercel Flags. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
    - [Clean Up After Rollout](/docs/flags/vercel-flags/cli/clean-up-after-rollout) | Type: How-to | Lastmod: 2026-02-24 | Summary: Audit active flags, remove a fully rolled-out flag from your codebase, and archive it using the Vercel CLI. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
    - [Roll Out a Feature](/docs/flags/vercel-flags/cli/roll-out-feature) | Type: How-to | Lastmod: 2026-02-24 | Summary: Create a feature flag, wire it into your application with the Flags SDK, and progressively enable it across environments using the Vercel CLI. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
    - [Run an A/B Test](/docs/flags/vercel-flags/cli/run-ab-test) | Type: How-to | Lastmod: 2026-02-24 | Summary: Set up an A/B test with a feature flag, track results through Web Analytics, and clean up afterward using the Vercel CLI. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
    - [Set Up Flags Explorer](/docs/flags/vercel-flags/cli/set-up-flags-explorer) | Type: How-to | Lastmod: 2026-02-24 | Summary: Add the Flags Explorer to the Vercel Toolbar so you can override flag values on preview deployments without affecting other users. | Prerequisites: Flags, Vercel Flags | Topics: flags, vercel flags
  - [Flags Explorer](/docs/flags/flags-explorer) | Type: How-to | Lastmod: 2026-02-11 | Summary: View and override your application's feature flags from the Vercel Toolbar | Prerequisites: Flags | Topics: flags, flags explorer
    - [Getting Started](/docs/flags/flags-explorer/getting-started) | Type: Tutorial | Lastmod: 2026-02-11 | Summary: Learn how to set up the Flags Explorer so you can see and override your application's feature flags | Prerequisites: Flags, Flags Explorer | Topics: flags, flags explorer
    - [Reference](/docs/flags/flags-explorer/reference) | Type: Reference | Lastmod: 2026-02-11 | Summary: In-depth reference for configuring the Flags Explorer | Prerequisites: Flags, Flags Explorer | Topics: flags, flags explorer
    - [Pricing](/docs/flags/flags-explorer/limits-and-pricing) | Type: Reference | Lastmod: 2026-02-23 | Summary: Learn about pricing for Flags Explorer. | Prerequisites: Flags, Flags Explorer | Topics: flags, flags explorer
  - [Marketplace](/docs/flags/marketplace) | Type: Conceptual | Lastmod: 2026-03-12 | Summary: Connect your preferred feature flag provider through the Vercel Marketplace for a unified flags experience. | Prerequisites: Flags | Topics: flags, marketplace
  - [Flags SDK](/docs/flags/flags-sdk-reference) | Type: Reference | Lastmod: 2026-02-25 | Summary: API reference for the Flags SDK for Next.js and SvelteKit. | Prerequisites: Flags | Topics: flags, flags sdk reference
  - [Observability](/docs/flags/observability) | Type: Conceptual | Lastmod: 2026-03-09 | Summary: Track feature flag evaluations and analyze their impact with Web Analytics. | Prerequisites: Flags | Topics: flags, observability
    - [Web Analytics](/docs/flags/observability/web-analytics) | Type: How-to | Lastmod: 2026-02-11 | Summary: Learn how to tag your page views and custom events with feature flags | Prerequisites: Flags, Observability | Topics: flags, observability

## Integrations

- [Overview](/docs/integrations) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Learn how to extend Vercel's capabilities by integrating with your preferred providers for AI, databases, headless content, commerce, and more. | Prerequisites: None | Topics: integrations
- [Install an Integration](/docs/integrations/install-an-integration) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Learn how to pair Vercel's functionality with a third-party service to streamline observability, integrate with testing tools, connect to your CMS, and more. | Prerequisites: Overview | Topics: integrations, install an integration
  - [Add a Native Integration](/docs/integrations/install-an-integration/product-integration) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how you can add a product to your Vercel project through a native integration. | Prerequisites: Overview, Install an Integration | Topics: integrations, install an integration
  - [Add a Connectable Account](/docs/integrations/install-an-integration/add-a-connectable-account) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to connect Vercel to your third-party account. | Prerequisites: Overview, Install an Integration | Topics: integrations, install an integration
  - [Agent Tools](/docs/integrations/install-an-integration/agent-tools) | Type: How-to | Lastmod: 2026-02-27 | Summary: Use Agent Tools to query, debug, and manage your installed integrations through a chat interface with natural language. | Prerequisites: Overview, Install an Integration | Topics: integrations, install an integration
  - [Permissions and Access](/docs/integrations/install-an-integration/manage-integrations-reference) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to manage project access and added products for your integrations. | Prerequisites: Overview, Install an Integration | Topics: integrations, install an integration
- [Create an Integration](/docs/integrations/create-integration) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to create and manage your own integration for internal or public use with Vercel. | Prerequisites: Overview | Topics: integrations, create integration
  - [Native integration concepts](/docs/integrations/create-integration/native-integration) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: As an integration provider, understanding how your service interacts with Vercel's platform will help you create and optimize your integration. | Prerequisites: Overview, Create an Integration | Topics: integrations, create integration
  - [Create a Native Integration](/docs/integrations/create-integration/marketplace-product) | Type: Tutorial | Lastmod: 2026-03-09 | Summary: Learn how to create a product for your Vercel native integration | Prerequisites: Overview, Create an Integration | Topics: integrations, create integration
  - [Deployment integration actions](/docs/integrations/create-integration/deployment-integration-action) | Type: How-to | Lastmod: 2025-07-18 | Summary: These actions allow integration providers to set up automated tasks with Vercel deployments. | Prerequisites: Overview, Create an Integration | Topics: integrations, create integration
  - [Native Integration Flows](/docs/integrations/create-integration/marketplace-flows) | Type: Reference | Lastmod: 2026-02-26 | Summary: Learn how information flows between the integration user, Vercel, and the integration provider for Vercel native integrations. | Prerequisites: Overview, Create an Integration | Topics: integrations, create integration
  - [Integration Approval Checklist](/docs/integrations/create-integration/approval-checklist) | Type: Reference | Lastmod: 2026-03-02 | Summary: Review this checklist before submitting your native or connectable account integration for approval on the Vercel Marketplace. | Prerequisites: Overview, Create an Integration | Topics: integrations, create integration
  - [Using Integrations API](/docs/integrations/create-integration/marketplace-api) | Type: Reference | Lastmod: 2026-02-27 | Summary: Learn how to authenticate and use the Integrations REST API to build your integration server. | Prerequisites: Overview, Create an Integration | Topics: integrations, create integration
  - [Billing and Refunds](/docs/integrations/create-integration/billing) | Type: Reference | Lastmod: 2026-03-03 | Summary: Learn how billing works for native integrations, including invoice lifecycle, pricing models, and refunds. | Prerequisites: Overview, Create an Integration | Topics: integrations, create integration
  - [Integration Image Guidelines](/docs/integrations/create-integration/integration-image-guidelines) | Type: Reference | Lastmod: 2025-08-26 | Summary: Guidelines for creating images for integrations, including layout, content, visual assets, descriptions, and design standards. | Prerequisites: Overview, Create an Integration | Topics: integrations, create integration
  - [Requirements for listing an Integration](/docs/integrations/create-integration/submit-integration) | Type: Reference | Lastmod: 2025-12-18 | Summary: Learn about all the requirements and guidelines needed when creating your Integration. | Prerequisites: Overview, Create an Integration | Topics: integrations, create integration
  - [Upgrade an Integration](/docs/integrations/create-integration/upgrade-integration) | Type: Conceptual | Lastmod: 2025-09-24 | Summary: Lean more about when you may need to upgrade your Integration. | Prerequisites: Overview, Create an Integration | Topics: integrations, create integration
  - [Building Integrations with Vercel REST API](/docs/integrations/create-integration/vercel-api-integrations) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to use Vercel REST API to build your integrations and work with redirect URLs. | Prerequisites: Overview, Create an Integration | Topics: integrations, create integration
  - [Secrets Rotation](/docs/integrations/create-integration/secrets-rotation) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to implement secrets rotation in your integration to allow users to rotate credentials securely. | Prerequisites: Overview, Create an Integration | Topics: integrations, create integration
- [CMS Integrations](/docs/integrations/cms) | Type: How-to | Lastmod: 2026-02-25 | Summary: Learn how to integrate Vercel with CMS platforms, including Contentful, Sanity, and Sitecore XM Cloud. | Prerequisites: Overview | Topics: integrations, cms
  - [Agility CMS](/docs/integrations/cms/agility-cms) | Type: How-to | Lastmod: 2025-03-04 | Summary: Learn how to integrate Agility CMS with Vercel. Follow our tutorial to deploy the Agility CMS template or install the integration for flexible and scalable content management. | Prerequisites: Overview, CMS Integrations | Topics: integrations, cms
  - [ButterCMS](/docs/integrations/cms/butter-cms) | Type: How-to | Lastmod: 2025-03-04 | Summary: Learn how to integrate ButterCMS with Vercel. Follow our tutorial to set up the ButterCMS template on Vercel and manage content seamlessly using ButterCMS API. | Prerequisites: Overview, CMS Integrations | Topics: integrations, cms
  - [Contentful](/docs/integrations/cms/contentful) | Type: Tutorial | Lastmod: 2026-02-18 | Summary: Integrate Vercel with Contentful to deploy your content. | Prerequisites: Overview, CMS Integrations | Topics: integrations, cms
  - [DatoCMS](/docs/integrations/cms/dato-cms) | Type: How-to | Lastmod: 2025-03-04 | Summary: Learn how to integrate DatoCMS with Vercel. Follow our step-by-step tutorial to set up and manage your digital content seamlessly using DatoCMS API. | Prerequisites: Overview, CMS Integrations | Topics: integrations, cms
  - [Formspree](/docs/integrations/cms/formspree) | Type: How-to | Lastmod: 2025-03-04 | Summary: Learn how to integrate Formspree with Vercel. Follow our tutorial to set up Formspree and manage form submissions on your static website without needing a server.  | Prerequisites: Overview, CMS Integrations | Topics: integrations, cms
  - [Makeswift](/docs/integrations/cms/makeswift) | Type: How-to | Lastmod: 2025-03-04 | Summary: Learn how to integrate Makeswift with Vercel. Makeswift is a no-code website builder designed for creating and managing React websites. Follow our tutorial to set up Makeswift and deploy your website on Vercel. | Prerequisites: Overview, CMS Integrations | Topics: integrations, cms
  - [Sanity](/docs/integrations/cms/sanity) | Type: How-to | Lastmod: 2025-03-04 | Summary: Learn how to integrate Sanity with Vercel. Follow our tutorial to deploy the Sanity template or install the integration for real-time collaboration and structured content management. | Prerequisites: Overview, CMS Integrations | Topics: integrations, cms
  - [Sitecore](/docs/integrations/cms/sitecore) | Type: Tutorial | Lastmod: 2026-02-18 | Summary: Integrate Vercel with Sitecore XM Cloud to deploy your content. | Prerequisites: Overview, CMS Integrations | Topics: integrations, cms
- [Commerce and Payments](/docs/integrations/ecommerce) | Type: Conceptual | Lastmod: 2026-03-02 | Summary: Learn how to integrate Vercel with payment processors and ecommerce platforms, including Stripe, Shopify, BigCommerce, and more. | Prerequisites: Overview | Topics: integrations, ecommerce
  - [Stripe](/docs/integrations/ecommerce/stripe) | Type: Tutorial | Lastmod: 2026-03-02 | Summary: Connect your Stripe account to Vercel and accept payments in your applications. | Prerequisites: Overview, Commerce and Payments | Topics: integrations, ecommerce

## External Platforms

- [Kubernetes](/docs/integrations/external-platforms/kubernetes) | Type: How-to | Lastmod: 2025-11-25 | Summary: Deploy your frontend on Vercel alongside your existing Kubernetes infrastructure. | Prerequisites: Overview | Topics: integrations, external platforms
- [Multi-tenant](/docs/multi-tenant) | Type: Conceptual | Lastmod: 2025-12-18 | Summary: Build multi-tenant applications that serve multiple customers from a single codebase with custom domains and subdomains. | Prerequisites: None | Topics: multi tenant
  - [Domain Management](/docs/multi-tenant/domain-management) | Type: How-to | Lastmod: 2025-11-25 | Summary: Manage custom domains, wildcard subdomains, and SSL certificates programmatically for multi-tenant applications using Vercel for Platforms. | Prerequisites: Multi-tenant | Topics: multi tenant, domain management
  - [Limits](/docs/multi-tenant/limits) | Type: Reference | Lastmod: 2025-11-25 | Summary: Understand the limits and features available for Vercel for Platforms. | Prerequisites: Multi-tenant | Topics: multi tenant, limits

## Observability

- [Overview](/docs/observability) | Type: Conceptual | Lastmod: 2026-03-03 | Summary: Observability on Vercel provides framework-aware insights enabling you to optimize infrastructure and application performance. | Prerequisites: None | Topics: observability
  - [Insights](/docs/observability/insights) | Type: Reference | Lastmod: 2026-03-03 | Summary: List of available data sources that you can view and monitor with Observability on Vercel. | Prerequisites: Overview | Topics: observability, insights
  - [Debug 500 Errors](/docs/observability/debug-production-errors) | Type: How-to | Lastmod: 2026-02-24 | Summary: Find, fix, and verify production 500 errors using the Vercel CLI. | Prerequisites: Overview | Topics: observability, debug production errors
  - [Observability Plus](/docs/observability/observability-plus) | Type: Reference | Lastmod: 2026-03-18 | Summary: Learn about using Observability Plus and its limits. | Prerequisites: Overview | Topics: observability, observability plus
- [Alerts](/docs/alerts) | Type: How-to | Lastmod: 2026-02-27 | Summary: Get notified when something's wrong with your Vercel projects. Set up alerts through Slack, webhooks, or email so you can fix issues quickly. | Prerequisites: None | Topics: observability, alerts
- [Logs](/docs/logs) | Type: Conceptual | Lastmod: 2026-02-23 | Summary: Use logs to find information on deployment builds, function executions, and more. | Prerequisites: None | Topics: observability, logs
  - [Runtime](/docs/logs/runtime) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to search, inspect, and share your runtime logs with the Logs tab. | Prerequisites: Logs | Topics: logs, runtime
- [Tracing](/docs/tracing) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to trace your application to understand performance and infrastructure details. | Prerequisites: None | Topics: observability, tracing
  - [Instrumentation](/docs/tracing/instrumentation) | Type: How-to | Lastmod: 2026-02-17 | Summary: Learn how to instrument your application to understand performance and infrastructure details. | Prerequisites: Tracing | Topics: observability, tracing, instrumentation
  - [Session Tracing](/docs/tracing/session-tracing) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to trace your sessions to understand performance and infrastructure details. | Prerequisites: Tracing | Topics: observability, tracing, session tracing
- [Query](/docs/query) | Type: How-to | Lastmod: 2026-02-26 | Summary: Query and visualize your Vercel usage, traffic, and more in observability. | Prerequisites: None | Topics: observability, query
  - [Query Reference](/docs/query/reference) | Type: Reference | Lastmod: 2025-12-18 | Summary: This reference covers the dimensions and operators used to create a query. | Prerequisites: Query | Topics: query, reference
  - [Monitoring](/docs/query/monitoring) | Type: Reference | Lastmod: 2026-02-27 | Summary: Query and visualize your Vercel usage, traffic, and more with Monitoring. | Prerequisites: Query | Topics: query, monitoring
    - [Getting Started](/docs/query/monitoring/quickstart) | Type: Tutorial | Lastmod: 2026-02-27 | Summary: In this quickstart guide, you'll discover how to create and execute a query to visualize the most popular posts on your website. | Prerequisites: Query, Monitoring | Topics: query, monitoring
    - [Monitoring Reference](/docs/query/monitoring/monitoring-reference) | Type: Reference | Lastmod: 2026-03-17 | Summary: This reference covers the clauses, fields, and variables used to create a Monitoring query. | Prerequisites: Query, Monitoring | Topics: query, monitoring
    - [Limits and Pricing](/docs/query/monitoring/limits-and-pricing) | Type: Reference | Lastmod: 2026-02-25 | Summary: Learn about our limits and pricing when using Monitoring. Different limitations are applied depending on your plan. | Prerequisites: Query, Monitoring | Topics: query, monitoring
- [Notebooks](/docs/notebooks) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn more about Notebooks and how they allow you to organize and save your queries. | Prerequisites: None | Topics: observability, notebooks
- [Speed Insights](/docs/speed-insights) | Type: Conceptual | Lastmod: 2026-03-10 | Summary: This page lists out and explains all the performance metrics provided by Vercel's Speed Insights feature. | Prerequisites: None | Topics: observability, speed insights
  - [Getting Started](/docs/speed-insights/quickstart) | Type: Tutorial | Lastmod: 2026-03-11 | Summary: Vercel Speed Insights provides you detailed insights into your website's performance. This quickstart guide will help you get started with using Speed Insights on Vercel. | Prerequisites: Speed Insights | Topics: speed insights, quickstart
  - [Using Speed Insights](/docs/speed-insights/using-speed-insights) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to use Speed Insights to analyze your application's performance data. | Prerequisites: Speed Insights | Topics: speed insights, using speed insights
  - [Metrics](/docs/speed-insights/metrics) | Type: Conceptual | Lastmod: 2026-02-18 | Summary: Learn what each performance metric on Speed Insights means and how the scores are calculated. | Prerequisites: Speed Insights | Topics: speed insights, metrics
  - [Privacy](/docs/speed-insights/privacy-policy) | Type: Reference | Lastmod: 2026-03-11 | Summary: Learn how Vercel follows the latest privacy and data compliance standards with its Speed Insights feature. | Prerequisites: Speed Insights | Topics: speed insights, privacy policy
  - [@vercel/speed-insights](/docs/speed-insights/package) | Type: Reference | Lastmod: 2026-03-11 | Summary: Learn how to configure your application to capture and send web performance metrics to Vercel using the @vercel/speed-insights npm package. | Prerequisites: Speed Insights | Topics: speed insights, package
  - [Limits and Pricing](/docs/speed-insights/limits-and-pricing) | Type: Reference | Lastmod: 2026-03-04 | Summary: Learn about our limits and pricing when using Vercel Speed Insights. Different limitations are applied depending on your plan. | Prerequisites: Speed Insights | Topics: speed insights, limits and pricing
  - [Managing Usage & Costs](/docs/speed-insights/managing-usage) | Type: Reference | Lastmod: 2026-02-26 | Summary: Learn how to measure and manage Speed Insights usage with this guide to reduce data points and avoid unexpected costs. | Prerequisites: Speed Insights | Topics: speed insights, managing usage
  - [Troubleshooting](/docs/speed-insights/troubleshooting) | Type: Reference | Lastmod: 2026-03-11 | Summary: Learn about common issues and how to troubleshoot Vercel Speed Insights. | Prerequisites: Speed Insights | Topics: speed insights, troubleshooting
- [Drains](/docs/drains) | Type: Reference | Lastmod: 2026-03-04 | Summary: Drains collect logs, traces, speed insights, and analytics from your applications. Forward observability data to custom endpoints or popular services. | Prerequisites: None | Topics: observability, drains
  - [Using Drains](/docs/drains/using-drains) | Type: How-to | Lastmod: 2026-03-17 | Summary: Learn how to configure drains to forward observability data to custom HTTP endpoints and add integrations. | Prerequisites: Drains | Topics: drains, using drains
  - [Logs](/docs/drains/reference/logs) | Type: Reference | Lastmod: 2025-11-24 | Summary: Learn about Log Drains - data formats, sources, environments, and security configuration. | Prerequisites: Drains | Topics: drains, reference
  - [Traces](/docs/drains/reference/traces) | Type: Reference | Lastmod: 2026-02-28 | Summary: Learn about Trace Drains - OpenTelemetry-compliant distributed tracing data formats and configuration. | Prerequisites: Drains | Topics: drains, reference
  - [Speed Insights](/docs/drains/reference/speed-insights) | Type: Reference | Lastmod: 2025-09-24 | Summary: Learn about Speed Insights Drains - data formats and performance metrics configuration. | Prerequisites: Drains | Topics: drains, reference
  - [Web Analytics](/docs/drains/reference/analytics) | Type: Reference | Lastmod: 2025-09-24 | Summary: Learn about Web Analytics Drains - data formats and custom events configuration. | Prerequisites: Drains | Topics: drains, reference
  - [Security](/docs/drains/security) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to secure your Drains endpoints with authentication and signature verification. | Prerequisites: Drains | Topics: drains, security
- [Web Analytics](/docs/analytics) | Type: Conceptual | Lastmod: 2026-03-10 | Summary: With Web Analytics, you can get detailed insights into your website's visitors with new metrics like top pages, top referrers, and demographics. | Prerequisites: None | Topics: observability, analytics
  - [Getting Started](/docs/analytics/quickstart) | Type: Tutorial | Lastmod: 2026-03-11 | Summary: Vercel Web Analytics provides you detailed insights into your website's visitors. This quickstart guide will help you get started with using Analytics on Vercel. | Prerequisites: Web Analytics | Topics: analytics, quickstart
  - [Using Web Analytics](/docs/analytics/using-web-analytics) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to use Vercel's Web Analytics to understand how visitors are using your website. | Prerequisites: Web Analytics | Topics: analytics, using web analytics
  - [Filtering](/docs/analytics/filtering) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how filters allow you to explore insights about your website's visitors. | Prerequisites: Web Analytics | Topics: analytics, filtering
  - [Custom Events](/docs/analytics/custom-events) | Type: How-to | Lastmod: 2026-03-11 | Summary: Learn how to send custom analytics events from your application. | Prerequisites: Web Analytics | Topics: analytics, custom events
  - [Redacting Sensitive Data](/docs/analytics/redacting-sensitive-data) | Type: How-to | Lastmod: 2025-03-04 | Summary: Learn how to redact sensitive data from your Web Analytics events. | Prerequisites: Web Analytics | Topics: analytics, redacting sensitive data
  - [Privacy](/docs/analytics/privacy-policy) | Type: Reference | Lastmod: 2026-03-11 | Summary: Learn how Vercel supports privacy and data compliance standards with Vercel Web Analytics. | Prerequisites: Web Analytics | Topics: analytics, privacy policy
  - [@vercel/analytics](/docs/analytics/package) | Type: Reference | Lastmod: 2026-03-11 | Summary: With the @vercel/analytics npm package, you are able to configure your application to send analytics data to Vercel. | Prerequisites: Web Analytics | Topics: analytics, package
  - [Pricing](/docs/analytics/limits-and-pricing) | Type: Reference | Lastmod: 2026-02-27 | Summary: Learn about pricing for Vercel Web Analytics. | Prerequisites: Web Analytics | Topics: analytics, limits and pricing
  - [Troubleshooting](/docs/analytics/troubleshooting) | Type: Reference | Lastmod: 2026-03-11 | Summary: Learn how to troubleshoot common issues with Vercel Web Analytics. | Prerequisites: Web Analytics | Topics: analytics, troubleshooting
- [Manage & Optimize](/docs/manage-and-optimize-observability) | Type: Reference | Lastmod: 2025-09-24 | Summary: Learn how to understand the different charts in the Vercel dashboard, how usage relates to billing, and how to optimize your usage of Web Analytics and Speed Insights. | Prerequisites: None | Topics: observability, manage and optimize observability
- [Debug Cache Issues](/docs/cdn-cache/debug-cache-issues) | Type: How-to | Lastmod: 2026-02-24 | Summary: Diagnose stale content and fix CDN cache, data cache, and build cache issues using the CLI. | Prerequisites: None | Topics: observability, cdn cache, debug cache issues

## Platform

- [Project Configuration](/docs/project-configuration) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how to configure your Vercel projects using vercel.json, vercel.ts, or the dashboard to control builds, routing, functions, and more. | Prerequisites: None | Topics: platform, project configuration
  - [vercel.json](/docs/project-configuration/vercel-json) | Type: Reference | Lastmod: 2026-03-11 | Summary: Learn how to use vercel.json to configure and override the default behavior of Vercel from within your project.  | Prerequisites: Project Configuration | Topics: project configuration, vercel json
  - [vercel.ts](/docs/project-configuration/vercel-ts) | Type: Reference | Lastmod: 2025-12-19 | Summary: Define your Vercel configuration in vercel.ts with @vercel/config for type-safe routing and build settings. | Prerequisites: Project Configuration | Topics: project configuration, vercel ts
  - [General Settings](/docs/project-configuration/general-settings) | Type: Reference | Lastmod: 2026-02-26 | Summary: Configure basic settings for your Vercel project, including the project name, build and development settings, root directory, Node.js version, Project ID, and Vercel Toolbar settings. | Prerequisites: Project Configuration | Topics: project configuration, general settings
  - [Project Settings](/docs/project-configuration/project-settings) | Type: Reference | Lastmod: 2026-02-26 | Summary: Use the project settings, to configure custom domains, environment variables, Git, integrations, deployment protection, functions, cron jobs, project members, webhooks, Drains, and security settings. | Prerequisites: Project Configuration | Topics: project configuration, project settings
  - [Git Configuration](/docs/project-configuration/git-configuration) | Type: Reference | Lastmod: 2025-12-19 | Summary: Learn how to configure Git for your project through vercel.json or vercel.ts. | Prerequisites: Project Configuration | Topics: project configuration, git configuration
  - [Git Settings](/docs/project-configuration/git-settings) | Type: Reference | Lastmod: 2026-03-10 | Summary: Use the project settings to manage the Git connection, enable Git LFS, and create deploy hooks. | Prerequisites: Project Configuration | Topics: project configuration, git settings
  - [Global Configuration](/docs/project-configuration/global-configuration) | Type: Reference | Lastmod: 2025-12-19 | Summary: Learn how to configure Vercel CLI under your system user. | Prerequisites: Project Configuration | Topics: project configuration, global configuration
  - [Security settings](/docs/project-configuration/security-settings) | Type: Reference | Lastmod: 2026-03-17 | Summary: Configure security settings for your Vercel project, including Logs and Source Protection, Customer Success Code Visibility, Git Fork Protection, and Secure Backend Access with OIDC Federation. | Prerequisites: Project Configuration | Topics: project configuration, security settings
- [Projects](/docs/projects) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: A project is the application that you have deployed to Vercel. | Prerequisites: None | Topics: platform, projects
  - [Deploy from CLI](/docs/projects/deploy-from-cli) | Type: How-to | Lastmod: 2026-02-24 | Summary: Set up and deploy a Vercel project using the CLI, from linking to production. | Prerequisites: Projects | Topics: platform, projects, deploy from cli
  - [Managing projects](/docs/projects/managing-projects) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to manage your projects through the Vercel Dashboard. | Prerequisites: Projects | Topics: projects, managing projects
  - [Transferring a project](/docs/projects/transferring-projects) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to transfer a project between Vercel teams. | Prerequisites: Projects | Topics: projects, transferring projects
- [Domains](/docs/domains) | Type: Conceptual | Lastmod: 2026-02-17 | Summary: Learn the fundamentals of how domains, DNS, and nameservers work on Vercel. | Prerequisites: None | Topics: platform, domains
  - [Working with Domains](/docs/domains/working-with-domains) | Type: Conceptual | Lastmod: 2026-03-17 | Summary: Learn how domains work and the options Vercel provides for managing them. | Prerequisites: Domains | Topics: domains, working with domains
    - [Adding a Domain](/docs/domains/working-with-domains/add-a-domain) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to add a custom domain to your Vercel project, verify it, and correctly set the DNS or Nameserver values. | Prerequisites: Domains, Working with Domains | Topics: domains, working with domains
    - [Adding a Domain to an Environment](/docs/domains/working-with-domains/add-a-domain-to-environment) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to add a custom domain to your Vercel project, verify it, and correctly set the DNS or Nameserver values. | Prerequisites: Domains, Working with Domains | Topics: domains, working with domains
    - [Assigning a Domain to a Git Branch](/docs/domains/working-with-domains/assign-domain-to-a-git-branch) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to assign a domain to a different Git branch with this guide. | Prerequisites: Domains, Working with Domains | Topics: domains, working with domains
    - [Claiming Ownership](/docs/domains/working-with-domains/claim-domain-ownership) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to claim ownership of a domain that is registered with another Vercel account by verifying DNS ownership. | Prerequisites: Domains, Working with Domains | Topics: domains, working with domains
    - [Deploying & Redirecting Domains](/docs/domains/working-with-domains/deploying-and-redirecting) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to deploy your domains and set up domain redirects with this guide. | Prerequisites: Domains, Working with Domains | Topics: domains, working with domains
    - [Removing a Domain](/docs/domains/working-with-domains/remove-a-domain) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to remove a domain from a Project and from your account completely with this guide. | Prerequisites: Domains, Working with Domains | Topics: domains, working with domains
    - [Renewing a Domain](/docs/domains/working-with-domains/renew-a-domain) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to manage automatic and manual renewals for custom domains purchased through or registered with Vercel, and how to redeem expired domains with this guide. | Prerequisites: Domains, Working with Domains | Topics: domains, working with domains
    - [Transferring Domains](/docs/domains/working-with-domains/transfer-your-domain) | Type: How-to | Lastmod: 2026-02-26 | Summary: Domains can be transferred to another team or project within Vercel, or to and from a third-party registrar. Learn how to transfer domains with this guide. | Prerequisites: Domains, Working with Domains | Topics: domains, working with domains
    - [Viewing & Searching Domains](/docs/domains/working-with-domains/view-and-search-domains) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to view and search all registered domains that are assigned to Vercel Projects through the Vercel dashboard. | Prerequisites: Domains, Working with Domains | Topics: domains, working with domains
  - [Working with DNS](/docs/domains/working-with-dns) | Type: Conceptual | Lastmod: 2025-10-02 | Summary: Learn how DNS works in order to properly configure your domain. | Prerequisites: Domains | Topics: domains, working with dns
  - [Managing DNS Records](/docs/domains/managing-dns-records) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to add, verify, and remove DNS records for your domains on Vercel with this guide. | Prerequisites: Domains | Topics: domains, managing dns records
  - [Domain Connect](/docs/domains/domain-connect) | Type: Conceptual | Summary: Learn about domain connect on Vercel. | Prerequisites: Domains | Topics: domains, domain connect
  - [Working with Nameservers](/docs/domains/working-with-nameservers) | Type: Conceptual | Lastmod: 2025-09-24 | Summary: Learn about nameservers and the benefits Vercel nameservers provide. | Prerequisites: Domains | Topics: domains, working with nameservers
  - [Managing Nameservers](/docs/domains/managing-nameservers) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to add custom nameservers and restore original nameservers for your domains on Vercel with this guide. | Prerequisites: Domains | Topics: domains, managing nameservers
  - [Working with SSL](/docs/domains/working-with-ssl) | Type: Conceptual | Lastmod: 2026-03-05 | Summary: Learn how Vercel uses SSL certification to keep your site secure. | Prerequisites: Domains | Topics: domains, working with ssl
  - [Custom SSL Certificates](/docs/domains/custom-SSL-certificate) | Type: How-to | Lastmod: 2026-02-26 | Summary: By default, Vercel provides all domains with a custom SSL certificates. However, Enterprise teams can upload their own custom SSL certificate. | Prerequisites: Domains | Topics: domains, custom SSL certificate
  - [Pre-Generate SSL Certificates](/docs/domains/pre-generating-ssl-certs) | Type: How-to | Lastmod: 2025-11-25 | Summary: test | Prerequisites: Domains | Topics: domains, pre generating ssl certs
  - [Supported Domains](/docs/domains/supported-domains) | Type: Reference | Lastmod: 2025-12-10 | Summary: Learn about supported domains on Vercel. | Prerequisites: Domains | Topics: domains, supported domains
  - [Troubleshooting Domains](/docs/domains/troubleshooting) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn about common reasons for domain misconfigurations and how to troubleshoot your domain on Vercel. | Prerequisites: Domains | Topics: domains, troubleshooting
  - [Set Up Custom Domain](/docs/domains/set-up-custom-domain) | Type: How-to | Lastmod: 2026-02-26 | Summary: Add and configure a custom domain for your Vercel project using the CLI. | Prerequisites: Domains | Topics: domains, set up custom domain
  - [Using Domains API](/docs/domains/registrar-api) | Type: Reference | Lastmod: 2025-10-08 | Summary: Programmatically search, price, purchase, renew, and manage domains with Vercel's domains registrar API endpoints. | Prerequisites: Domains | Topics: domains, registrar api
- [Notifications](/docs/notifications) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to use Notifications to view and manage important alerts about your deployments, domains, integrations, account, and usage. | Prerequisites: None | Topics: platform, notifications
- [Build Output API](/docs/build-output-api) | Type: Conceptual | Lastmod: 2025-12-04 | Summary: The Build Output API is a file-system-based specification for a directory structure that can produce a Vercel deployment. | Prerequisites: None | Topics: platform, build output api
  - [Build Output Configuration](/docs/build-output-api/configuration) | Type: Conceptual | Lastmod: 2025-08-15 | Summary: Learn about the Build Output Configuration file, which is used to configure the behavior of a Deployment. | Prerequisites: Build Output API | Topics: build output api, configuration
  - [Features](/docs/build-output-api/features) | Type: Conceptual | Lastmod: 2025-03-04 | Summary: Learn how to implement common Vercel platform features through the Build Output API. | Prerequisites: Build Output API | Topics: build output api, features
  - [Vercel Primitives](/docs/build-output-api/primitives) | Type: Reference | Lastmod: 2025-03-04 | Summary: Learn about the Vercel platform primitives and how they work together to create a Vercel Deployment. | Prerequisites: Build Output API | Topics: build output api, primitives
- [Glossary](/docs/glossary) | Type: Reference | Lastmod: 2026-03-05 | Summary: Learn about the terms and concepts used in Vercel's products and documentation. | Prerequisites: None | Topics: platform, glossary
- [Limits](/docs/limits) | Type: Reference | Lastmod: 2026-03-02 | Summary: This reference covers a list of all the limits and limitations that apply on Vercel. | Prerequisites: None | Topics: platform, limits
  - [Fair Use Guidelines](/docs/limits/fair-use-guidelines) | Type: Reference | Lastmod: 2026-02-27 | Summary: Learn about all subscription plans included usage that is subject to Vercel's fair use guidelines. | Prerequisites: Limits | Topics: limits, fair use guidelines
- [Checks](/docs/checks) | Type: Conceptual | Lastmod: 2025-09-15 | Summary: Vercel automatically keeps an eye on various aspects of your web application using the Checks API. Learn how to use Checks in your Vercel workflow here. | Prerequisites: None | Topics: platform, checks
  - [Checks API](/docs/checks/checks-api) | Type: Reference | Lastmod: 2026-03-17 | Summary: The Vercel Checks API let you create tests and assertions that run after each deployment has been built, and are powered by Vercel Integrations. | Prerequisites: Checks | Topics: checks, checks api
  - [Checks Reference](/docs/checks/creating-checks) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to create your own Checks with Vercel Integrations. You can build your own Integration in order to register any arbitrary Check for your deployments. | Prerequisites: Checks | Topics: checks, creating checks
- [Manage Redirects at Scale](/docs/redirects/manage-redirects-at-scale) | Type: How-to | Lastmod: 2026-02-24 | Summary: Add, bulk upload, version, and roll back project-level redirects using the CLI. | Prerequisites: None | Topics: platform, redirects, manage redirects at scale
- [Support Center](/docs/support-center) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to communicate securely with the Vercel support team | Prerequisites: None | Topics: platform, support center

## Pricing

- [Plans](/docs/plans) | Type: Reference | Lastmod: 2026-01-07 | Summary: Learn about the different plans available on Vercel. | Prerequisites: None | Topics: pricing, plans
  - [Hobby Plan](/docs/plans/hobby) | Type: Reference | Lastmod: 2026-02-27 | Summary: Learn about the Hobby plan and how it compares to the Pro plan. | Prerequisites: Plans | Topics: plans, hobby
  - [Pro Plan](/docs/plans/pro-plan) | Type: Reference | Lastmod: 2026-02-26 | Summary: Learn about the Vercel Pro plan with credit-based billing, free viewer seats, and self-serve enterprise features for professional teams. | Prerequisites: Plans | Topics: plans, pro plan
    - [Pro Plan Trial](/docs/plans/pro-plan/trials) | Type: Reference | Lastmod: 2026-02-26 | Summary: Learn all about Vercel's Pro Plan free trial, including features, usage limits, and options post-trial. Learn how to manage your team's projects with Vercel's Pro Plan trial. | Prerequisites: Plans, Pro Plan | Topics: plans, pro plan
    - [Billing FAQ](/docs/plans/pro-plan/billing) | Type: Reference | Lastmod: 2026-02-27 | Summary: This page covers frequently asked questions around payments, invoices, and billing on the Pro plan. | Prerequisites: Plans, Pro Plan | Topics: plans, pro plan
  - [Enterprise Plan](/docs/plans/enterprise) | Type: Reference | Lastmod: 2026-02-26 | Summary: Learn about the Enterprise plan for Vercel, including features, pricing, and more. | Prerequisites: Plans | Topics: plans, enterprise
    - [Billing FAQ](/docs/plans/enterprise/billing) | Type: Reference | Lastmod: 2026-02-27 | Summary: This page covers frequently asked questions around payments, invoices, and billing on the Enterprise plan. | Prerequisites: Plans, Enterprise Plan | Topics: plans, enterprise
- [Pricing](/docs/pricing) | Type: Reference | Lastmod: 2026-02-27 | Summary: Learn about Vercel's pricing model, including the resources and services that are billed, and how they are priced. | Prerequisites: None | Topics: pricing
  - [Regional Pricing](/docs/pricing/regional-pricing) | Type: Reference | Lastmod: 2026-02-27 | Summary: Vercel pricing for Managed Infrastructure resources in different regions. | Prerequisites: Pricing | Topics: pricing, regional pricing
    - [Cape Town, South Africa \(cpt1\)](/docs/pricing/regional-pricing/cpt1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Cape Town, South Africa \(cpt1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Cleveland, USA \(cle1\)](/docs/pricing/regional-pricing/cle1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Cleveland, USA \(cle1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Dubai, UAE \(dxb1\)](/docs/pricing/regional-pricing/dxb1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Dubai, UAE \(dxb1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Dublin, Ireland \(dub1\)](/docs/pricing/regional-pricing/dub1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Dublin, Ireland \(dub1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Frankfurt, Germany \(fra1\)](/docs/pricing/regional-pricing/fra1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Frankfurt, Germany \(fra1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Hong Kong \(hkg1\)](/docs/pricing/regional-pricing/hkg1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Hong Kong \(hkg1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [London, UK \(lhr1\)](/docs/pricing/regional-pricing/lhr1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the London, UK \(lhr1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Montréal, Canada \(yul1\)](/docs/pricing/regional-pricing/yul1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Montréal, Canada \(yul1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Mumbai, India \(bom1\)](/docs/pricing/regional-pricing/bom1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Mumbai, India \(bom1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Osaka, Japan \(kix1\)](/docs/pricing/regional-pricing/kix1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Osaka, Japan \(kix1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Paris, France \(cdg1\)](/docs/pricing/regional-pricing/cdg1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Paris, France \(cdg1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Portland, USA \(pdx1\)](/docs/pricing/regional-pricing/pdx1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Portland, USA \(pdx1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [San Francisco, USA \(sfo1\)](/docs/pricing/regional-pricing/sfo1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the San Francisco, USA \(sfo1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [São Paulo, Brazil \(gru1\)](/docs/pricing/regional-pricing/gru1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the São Paulo, Brazil \(gru1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Seoul, South Korea \(icn1\)](/docs/pricing/regional-pricing/icn1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Seoul, South Korea \(icn1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Singapore \(sin1\)](/docs/pricing/regional-pricing/sin1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Singapore \(sin1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Stockholm, Sweden \(arn1\)](/docs/pricing/regional-pricing/arn1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Stockholm, Sweden \(arn1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Sydney, Australia \(syd1\)](/docs/pricing/regional-pricing/syd1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Sydney, Australia \(syd1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Tokyo, Japan \(hnd1\)](/docs/pricing/regional-pricing/hnd1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Tokyo, Japan \(hnd1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
    - [Washington D.C., USA \(iad1\)](/docs/pricing/regional-pricing/iad1) | Type: Reference | Lastmod: 2026-02-13 | Summary: Vercel pricing for the Washington D.C., USA \(iad1\) region. | Prerequisites: Pricing, Regional Pricing | Topics: pricing, regional pricing
  - [Manage and Optimize Usage](/docs/pricing/manage-and-optimize-usage) | Type: Reference | Lastmod: 2026-03-04 | Summary: Understand how to manage and optimize your usage on Vercel, learn how to track your usage, set up alerts, and optimize your usage to save costs. | Prerequisites: Pricing | Topics: pricing, manage and optimize usage
  - [Calculating Usage of Resources](/docs/pricing/how-does-vercel-calculate-usage-of-resources) | Type: Conceptual | Lastmod: 2026-02-18 | Summary: Understand how Vercel measures and calculates your resource usage based on a typical user journey. | Prerequisites: Pricing | Topics: pricing, how does vercel calculate usage of resources
  - [Billing & Invoices](/docs/pricing/understanding-my-invoice) | Type: Reference | Lastmod: 2026-02-26 | Summary: Learn how Vercel invoices get structured for Pro and Enterprise plans. Learn how usage allotments and on-demand charges get included. | Prerequisites: Pricing | Topics: pricing, understanding my invoice
  - [Legacy Metrics](/docs/pricing/legacy) | Type: Reference | Lastmod: 2026-02-18 | Summary: Learn about Bandwidth, Requests, Vercel Function Invocations, and Vercel Function Execution metrics. | Prerequisites: Pricing | Topics: pricing, legacy
  - [Taxes](/docs/pricing/taxes) | Type: Reference | Lastmod: 2026-02-17 | Summary: This page covers frequently asked questions around taxes. | Prerequisites: Pricing | Topics: pricing, taxes
- [Spend Management](/docs/spend-management) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to get notified about your account spend and configure a webhook. | Prerequisites: None | Topics: pricing, spend management

## Security

- [Overview](/docs/security) | Type: Conceptual | Lastmod: 2026-02-18 | Summary: Vercel provides built-in and customizable features to ensure that your site is secure. | Prerequisites: None | Topics: security
  - [Security & Compliance Measures](/docs/security/compliance) | Type: Reference | Lastmod: 2026-02-18 | Summary: Learn about the protection and compliance measures Vercel takes to ensure the security of your data, including DDoS mitigation and SOC 2 compliance. | Prerequisites: Overview | Topics: security, compliance
  - [Shared Responsibility Model](/docs/security/shared-responsibility) | Type: Conceptual | Lastmod: 2026-01-21 | Summary: Discover the essentials of our Shared Responsibility Model, outlining the key roles and responsibilities for customers, Vercel, and shared aspects in ensuring secure and efficient cloud computing services. | Prerequisites: Overview | Topics: security, shared responsibility
  - [PCI DSS iframe Integration](/docs/security/pci-dss) | Type: How-to | Lastmod: 2026-03-17 | Summary: Learn how to integrate an iframe into your application to support PCI DSS compliance. | Prerequisites: Overview | Topics: security, pci dss
  - [Reverse Proxy Servers and Vercel](/docs/security/reverse-proxy) | Type: Conceptual | Lastmod: 2026-02-18 | Summary: Learn why reverse proxy servers are not recommended with Vercel's firewall. | Prerequisites: Overview | Topics: security, reverse proxy
  - [Access Control](/docs/security/access-control) | Type: Reference | Lastmod: 2026-02-18 | Summary: Learn about the protection and compliance measures Vercel takes to ensure the security of your data, including DDoS mitigation, SOC 2 compliance and more. | Prerequisites: Overview | Topics: security, access control
- [Audit Logs](/docs/audit-log) | Type: Reference | Lastmod: 2026-03-17 | Summary: Learn how to track and analyze your team members' activities. | Prerequisites: None | Topics: security, audit log
- [Firewall](/docs/vercel-firewall) | Type: Conceptual | Lastmod: 2026-02-26 | Summary: Learn how Vercel Firewall helps protect your applications and websites from malicious attacks and unauthorized access. | Prerequisites: None | Topics: security, vercel firewall
  - [Firewall Concepts](/docs/vercel-firewall/firewall-concepts) | Type: Conceptual | Lastmod: 2026-02-18 | Summary: Understand the fundamentals behind the Vercel Firewall. | Prerequisites: Firewall | Topics: vercel firewall, firewall concepts
  - [DDoS Mitigation](/docs/vercel-firewall/ddos-mitigation) | Type: Conceptual | Lastmod: 2026-01-05 | Summary: Learn how the Vercel Firewall mitigates against DoS and DDoS attacks | Prerequisites: Firewall | Topics: vercel firewall, ddos mitigation
  - [Attack Challenge Mode](/docs/vercel-firewall/attack-challenge-mode) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Learn how to use Attack Challenge Mode to help control who has access to your site when it's under attack. | Prerequisites: Firewall | Topics: vercel firewall, attack challenge mode
  - [Web Application Firewall](/docs/vercel-firewall/vercel-waf) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to secure your website with the Vercel Web Application Firewall \(WAF\) | Prerequisites: Firewall | Topics: vercel firewall, vercel waf
    - [Custom Rules](/docs/vercel-firewall/vercel-waf/custom-rules) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to add and manage custom rules to configure the Vercel Web Application Firewall \(WAF\). | Prerequisites: Firewall, Web Application Firewall | Topics: vercel firewall, vercel waf
    - [Rate Limiting](/docs/vercel-firewall/vercel-waf/rate-limiting) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to configure custom rate limiting rules with the Vercel Web Application Firewall \(WAF\). | Prerequisites: Firewall, Web Application Firewall | Topics: vercel firewall, vercel waf
    - [Rule Configuration](/docs/vercel-firewall/vercel-waf/rule-configuration) | Type: Reference | Lastmod: 2025-04-21 | Summary: List of configurable options with the Vercel WAF | Prerequisites: Firewall, Web Application Firewall | Topics: vercel firewall, vercel waf
    - [System Bypass Rules](/docs/vercel-firewall/vercel-waf/system-bypass-rules) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to configure IP-based system bypass rules with the Vercel Web Application Firewall \(WAF\). | Prerequisites: Firewall, Web Application Firewall | Topics: vercel firewall, vercel waf
    - [Rate Limiting SDK](/docs/vercel-firewall/vercel-waf/rate-limiting-sdk) | Type: How-to | Lastmod: 2026-02-26 | Summary: Learn how to configure a custom rule with rate limit in your code. | Prerequisites: Firewall, Web Application Firewall | Topics: vercel firewall, vercel waf
    - [IP Blocking](/docs/vercel-firewall/vercel-waf/ip-blocking) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to customize the Vercel WAF to restrict access to certain IP addresses. | Prerequisites: Firewall, Web Application Firewall | Topics: vercel firewall, vercel waf
    - [WAF Managed Rulesets](/docs/vercel-firewall/vercel-waf/managed-rulesets) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to use WAF Managed Rulesets with the Vercel Web Application Firewall \(WAF\) | Prerequisites: Firewall, Web Application Firewall | Topics: vercel firewall, vercel waf
    - [Examples](/docs/vercel-firewall/vercel-waf/examples) | Type: How-to | Lastmod: 2025-11-25 | Summary: Learn how to use Vercel WAF to protect your site in specific situations. | Prerequisites: Firewall, Web Application Firewall | Topics: vercel firewall, vercel waf
    - [Usage & Pricing](/docs/vercel-firewall/vercel-waf/usage-and-pricing) | Type: Reference | Lastmod: 2025-09-09 | Summary: Learn how the Vercel WAF can affect your usage and how specific features are priced. | Prerequisites: Firewall, Web Application Firewall | Topics: vercel firewall, vercel waf
  - [Firewall API](/docs/vercel-firewall/firewall-api) | Type: How-to | Lastmod: 2025-11-25 | Summary: Learn how to interact with the security endpoints of the Vercel REST API programmatically. | Prerequisites: Firewall | Topics: vercel firewall, firewall api
  - [Firewall Observability](/docs/vercel-firewall/firewall-observability) | Type: How-to | Lastmod: 2026-02-13 | Summary: Learn how firewall traffic monitoring and alerts help you react quickly to potential security threats. | Prerequisites: Firewall | Topics: vercel firewall, firewall observability
- [Bot Management](/docs/bot-management) | Type: Conceptual | Lastmod: 2026-02-17 | Summary: Learn how to manage bot traffic to your site. | Prerequisites: None | Topics: security, bot management
- [BotID](/docs/botid) | Type: Conceptual | Lastmod: 2026-02-17 | Summary: Protect your applications from automated attacks with intelligent bot detection and verification, powered by Kasada. | Prerequisites: None | Topics: security, botid
  - [Get Started with BotID](/docs/botid/get-started) | Type: Tutorial | Lastmod: 2026-02-26 | Summary: Step-by-step guide to setting up BotID protection in your Vercel project | Prerequisites: BotID | Topics: botid, get started
  - [Handling Verified Bots](/docs/botid/verified-bots) | Type: Reference | Lastmod: 2026-02-26 | Summary: Information about verified bots and their handling in BotID | Prerequisites: BotID | Topics: botid, verified bots
  - [Advanced BotID Configuration](/docs/botid/advanced-configuration) | Type: Reference | Lastmod: 2026-02-26 | Summary: Fine-grained control over BotID detection levels and backend domain configuration | Prerequisites: BotID | Topics: botid, advanced configuration
  - [Form Submissions](/docs/botid/form-submissions) | Type: How-to | Lastmod: 2026-02-26 | Summary: How to properly handle form submissions with BotID protection | Prerequisites: BotID | Topics: botid, form submissions
  - [Local Development Behavior](/docs/botid/local-development-behavior) | Type: Reference | Lastmod: 2026-02-26 | Summary: How BotID behaves in local development environments and testing options | Prerequisites: BotID | Topics: botid, local development behavior
- [Connectivity](/docs/connectivity) | Type: Reference | Lastmod: 2026-02-25 | Summary: Connect your Vercel projects to backend services with static IPs and secure networking options. | Prerequisites: None | Topics: security, connectivity
  - [Secure Compute](/docs/connectivity/secure-compute) | Type: Reference | Lastmod: 2026-02-26 | Summary: Secure Compute provides dedicated private networks with VPC peering for Enterprise teams. | Prerequisites: Connectivity | Topics: security, connectivity, secure compute
  - [Static IPs](/docs/connectivity/static-ips) | Type: Reference | Lastmod: 2026-02-25 | Summary: Access IP-restricted backend services through shared static egress IPs for Pro and Enterprise teams. | Prerequisites: Connectivity | Topics: security, connectivity, static ips
    - [Getting Started](/docs/connectivity/static-ips/getting-started) | Type: Tutorial | Lastmod: 2025-10-02 | Summary: Learn how to set up Static IPs for your Vercel projects to connect to IP-restricted backend services. | Prerequisites: Connectivity, Static IPs | Topics: security, connectivity, static ips
- [OIDC](/docs/oidc) | Type: Conceptual | Lastmod: 2025-06-06 | Summary: Secure the access to your backend using OIDC Federation to enable auto-generated, short-lived, and non-persistent credentials. | Prerequisites: None | Topics: security, oidc
  - [AWS](/docs/oidc/aws) | Type: How-to | Lastmod: 2025-10-27 | Summary: Learn how to configure your AWS account to trust Vercel's OpenID Connect \(OIDC\) Identity Provider \(IdP\). | Prerequisites: OIDC | Topics: oidc, aws
  - [Azure](/docs/oidc/azure) | Type: How-to | Lastmod: 2025-10-27 | Summary: Learn how to configure your Microsoft Azure account to trust Vercel's OpenID Connect \(OIDC\) Identity Provider \(IdP\). | Prerequisites: OIDC | Topics: oidc, azure
  - [Connect your API](/docs/oidc/api) | Type: How-to | Lastmod: 2025-10-27 | Summary: Learn how to configure your own API to trust Vercel's OpenID Connect \(OIDC\) Identity Provider \(IdP\) | Prerequisites: OIDC | Topics: oidc, api
  - [Google Cloud Platform](/docs/oidc/gcp) | Type: How-to | Lastmod: 2025-10-27 | Summary: Learn how to configure your GCP project to trust Vercel's OpenID Connect \(OIDC\) Identity Provider \(IdP\). | Prerequisites: OIDC | Topics: oidc, gcp
  - [OIDC Reference](/docs/oidc/reference) | Type: Reference | Lastmod: 2025-10-27 | Summary: Review helper libraries to help you connect with your backend and understand the structure of an OIDC token. | Prerequisites: OIDC | Topics: oidc, reference
- [RBAC](/docs/rbac) | Type: Reference | Lastmod: 2025-05-23 | Summary: Learn how to manage team members on Vercel, and how to assign roles to each member with role-based access control \(RBAC\). | Prerequisites: None | Topics: security, rbac
  - [Access Roles](/docs/rbac/access-roles) | Type: Reference | Lastmod: 2026-03-02 | Summary: Learn about the different roles available for team members on a Vercel account. | Prerequisites: RBAC | Topics: rbac, access roles
    - [Extended Permissions](/docs/rbac/access-roles/extended-permissions) | Type: Reference | Lastmod: 2025-10-10 | Summary: Learn about extended permissions in Vercel's RBAC system. Understand how to combine roles and permissions for precise access control. | Prerequisites: RBAC, Access Roles | Topics: rbac, access roles
    - [Project Level Roles](/docs/rbac/access-roles/project-level-roles) | Type: Reference | Lastmod: 2025-10-10 | Summary: Learn about the project level roles and their permissions. | Prerequisites: RBAC, Access Roles | Topics: rbac, access roles
    - [Team Level Roles](/docs/rbac/access-roles/team-level-roles) | Type: Reference | Lastmod: 2026-02-26 | Summary: Learn about the different team level roles and the permissions they provide. | Prerequisites: RBAC, Access Roles | Topics: rbac, access roles
  - [Access Groups](/docs/rbac/access-groups) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to configure access groups for team members on a Vercel account. | Prerequisites: RBAC | Topics: rbac, access groups
  - [Managing Team Members](/docs/rbac/managing-team-members) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to manage team members on Vercel, and how to assign roles to each member with role-based access control \(RBAC\). | Prerequisites: RBAC | Topics: rbac, managing team members
- [Two-factor Enforcement](/docs/two-factor-enforcement) | Type: Reference | Lastmod: 2026-02-27 | Summary: Learn how to enforce two-factor authentication \(2FA\) for your Vercel team members to enhance security. | Prerequisites: None | Topics: security, two factor enforcement

## Storage

- [Overview](/docs/storage) | Type: Conceptual | Lastmod: 2026-02-27 | Summary: Store large files and global configuration with Vercel's storage products. | Prerequisites: None | Topics: storage
- [Blob](/docs/vercel-blob) | Type: Conceptual | Lastmod: 2026-02-19 | Summary: Vercel Blob is a scalable, cost-effective object storage service with private and public access modes for files of any size. | Prerequisites: None | Topics: storage, vercel blob
  - [Private Storage](/docs/vercel-blob/private-storage) | Type: Conceptual | Lastmod: 2026-03-03 | Summary: Learn how to use private Vercel Blob storage to serve files with authentication | Prerequisites: Blob | Topics: vercel blob, private storage
  - [Public Storage](/docs/vercel-blob/public-storage) | Type: Conceptual | Lastmod: 2026-03-16 | Summary: Learn how to use public Vercel Blob storage to serve files accessible to anyone with the URL | Prerequisites: Blob | Topics: vercel blob, public storage
  - [Server Uploads](/docs/vercel-blob/server-upload) | Type: Tutorial | Lastmod: 2026-02-26 | Summary: Learn how to upload files to Vercel Blob using Server Actions and Route Handlers | Prerequisites: Blob | Topics: vercel blob, server upload
  - [Client Uploads](/docs/vercel-blob/client-upload) | Type: Tutorial | Lastmod: 2026-02-26 | Summary: Learn how to upload files larger than 4.5 MB directly from the browser to Vercel Blob | Prerequisites: Blob | Topics: vercel blob, client upload
  - [Using the SDK](/docs/vercel-blob/using-blob-sdk) | Type: Reference | Lastmod: 2026-02-19 | Summary: Learn how to use the Vercel Blob SDK to access your blob store from your apps. | Prerequisites: Blob | Topics: vercel blob, using blob sdk
  - [Pricing](/docs/vercel-blob/usage-and-pricing) | Type: Reference | Lastmod: 2026-03-04 | Summary: Learn about the pricing for Vercel Blob. | Prerequisites: Blob | Topics: vercel blob, usage and pricing
  - [Security](/docs/vercel-blob/security) | Type: Conceptual | Lastmod: 2026-02-19 | Summary: Learn how your Vercel Blob store is secured | Prerequisites: Blob | Topics: vercel blob, security
  - [Examples](/docs/vercel-blob/examples) | Type: Reference | Lastmod: 2026-02-19 | Summary: Examples on how to use Vercel Blob in your applications | Prerequisites: Blob | Topics: vercel blob, examples
  - [Manage Vercel Blob Storage](/docs/vercel-blob/manage-blob-storage) | Type: How-to | Lastmod: 2026-02-26 | Summary: Create blob stores, upload files, list contents, and manage storage using the CLI. | Prerequisites: Blob | Topics: vercel blob, manage blob storage
- [Edge Config](/docs/edge-config) | Type: Conceptual | Lastmod: 2026-03-17 | Summary: An Edge Config is a global data store that enables experimentation with feature flags, A/B testing, critical redirects, and more. | Prerequisites: None | Topics: storage, edge config
  - [Getting Started](/docs/edge-config/get-started) | Type: Tutorial | Lastmod: 2026-02-27 | Summary: Learn how to create an Edge Config store and read from it in your project. | Prerequisites: Edge Config | Topics: edge config, get started
  - [Using Edge Config](/docs/edge-config/using-edge-config) | Type: Conceptual | Lastmod: 2026-03-17 | Summary: Learn how to use Edge Configs in your projects. | Prerequisites: Edge Config | Topics: edge config, using edge config
  - [Edge Configs & REST API](/docs/edge-config/vercel-api) | Type: Conceptual | Lastmod: 2026-03-17 | Summary: Learn how to use the Vercel REST API to create and update Edge Configs. You can also read data stored in Edge Configs with the Vercel REST API. | Prerequisites: Edge Config | Topics: edge config, vercel api
  - [Edge Configs & Dashboard](/docs/edge-config/edge-config-dashboard) | Type: How-to | Lastmod: 2026-02-27 | Summary: Learn how to create, view and update your Edge Configs and the data inside them in your Vercel Dashboard at the Hobby team, team, and project levels. | Prerequisites: Edge Config | Topics: edge config, edge config dashboard
  - [Edge Config SDK](/docs/edge-config/edge-config-sdk) | Type: Reference | Lastmod: 2026-01-13 | Summary: The Edge Config client SDK is the most ergonomic way to read data from Edge Configs. Learn how to set up the SDK so you can start reading Edge Configs. | Prerequisites: Edge Config | Topics: edge config, edge config sdk
  - [Limits & Pricing](/docs/edge-config/edge-config-limits) | Type: Reference | Lastmod: 2026-02-26 | Summary: Learn about the Edge Configs limits and pricing based on account plans. | Prerequisites: Edge Config | Topics: edge config, edge config limits
  - [Integrations](/docs/edge-config/edge-config-integrations) | Type: Conceptual | Lastmod: 2025-12-19 | Summary: Learn how to use Edge Config with popular A/B testing and feature flag service integrations. | Prerequisites: Edge Config | Topics: edge config, edge config integrations
    - [DevCycle](/docs/edge-config/edge-config-integrations/devcycle-edge-config) | Type: Tutorial | Lastmod: 2026-02-13 | Summary: Learn how to use Edge Config with Vercel's DevCycle integration. | Prerequisites: Edge Config, Integrations | Topics: edge config, edge config integrations
    - [Hypertune](/docs/edge-config/edge-config-integrations/hypertune-edge-config) | Type: Tutorial | Lastmod: 2025-11-19 | Summary: Learn how to use Hypertune's integration with Vercel Edge Config. | Prerequisites: Edge Config, Integrations | Topics: edge config, edge config integrations
    - [LaunchDarkly](/docs/edge-config/edge-config-integrations/launchdarkly-edge-config) | Type: Tutorial | Lastmod: 2026-02-13 | Summary: Learn how to use Edge Config with Vercel's LaunchDarkly integration. | Prerequisites: Edge Config, Integrations | Topics: edge config, edge config integrations
    - [Split](/docs/edge-config/edge-config-integrations/split-edge-config) | Type: Tutorial | Lastmod: 2026-02-26 | Summary: Learn how to use Edge Config with Vercel's Split integration. | Prerequisites: Edge Config, Integrations | Topics: edge config, edge config integrations
    - [Statsig](/docs/edge-config/edge-config-integrations/statsig-edge-config) | Type: Tutorial | Lastmod: 2026-02-13 | Summary: Learn how to use Edge Config with Vercel's Statsig integration. | Prerequisites: Edge Config, Integrations | Topics: edge config, edge config integrations
- [Marketplace](/docs/marketplace-storage) | Type: Conceptual | Lastmod: 2026-02-11 | Summary: Connect Postgres, Redis, NoSQL, and other storage solutions through the Vercel Marketplace. | Prerequisites: None | Topics: storage, marketplace storage

## REST API Reference

### access-groups

- [Reads an access group](/docs/rest-api/access-groups/reads-an-access-group)
  - Type: Reference
  - Summary: GET /v1/access-groups/{idOrName} — Allows to read an access group
  - Topics: rest api, access-groups

- [Update an access group](/docs/rest-api/access-groups/update-an-access-group)
  - Type: Reference
  - Summary: POST /v1/access-groups/{idOrName} — Allows to update an access group metadata
  - Topics: rest api, access-groups

- [Deletes an access group](/docs/rest-api/access-groups/deletes-an-access-group)
  - Type: Reference
  - Summary: DELETE /v1/access-groups/{idOrName} — Allows to delete an access group
  - Topics: rest api, access-groups

- [List members of an access group](/docs/rest-api/access-groups/list-members-of-an-access-group)
  - Type: Reference
  - Summary: GET /v1/access-groups/{idOrName}/members — List members of an access group
  - Topics: rest api, access-groups

- [List access groups for a team, project or member](/docs/rest-api/access-groups/list-access-groups-for-a-team-project-or-member)
  - Type: Reference
  - Summary: GET /v1/access-groups — List access groups
  - Topics: rest api, access-groups

- [Creates an access group](/docs/rest-api/access-groups/creates-an-access-group)
  - Type: Reference
  - Summary: POST /v1/access-groups — Allows to create an access group
  - Topics: rest api, access-groups

- [List projects of an access group](/docs/rest-api/access-groups/list-projects-of-an-access-group)
  - Type: Reference
  - Summary: GET /v1/access-groups/{idOrName}/projects — List projects of an access group
  - Topics: rest api, access-groups

- [Create an access group project](/docs/rest-api/access-groups/create-an-access-group-project)
  - Type: Reference
  - Summary: POST /v1/access-groups/{accessGroupIdOrName}/projects — Allows creation of an access group project
  - Topics: rest api, access-groups

- [Reads an access group project](/docs/rest-api/access-groups/reads-an-access-group-project)
  - Type: Reference
  - Summary: GET /v1/access-groups/{accessGroupIdOrName}/projects/{projectId} — Allows reading an access group project
  - Topics: rest api, access-groups

- [Update an access group project](/docs/rest-api/access-groups/update-an-access-group-project)
  - Type: Reference
  - Summary: PATCH /v1/access-groups/{accessGroupIdOrName}/projects/{projectId} — Allows update of an access group project
  - Topics: rest api, access-groups

- [Delete an access group project](/docs/rest-api/access-groups/delete-an-access-group-project)
  - Type: Reference
  - Summary: DELETE /v1/access-groups/{accessGroupIdOrName}/projects/{projectId} — Allows deletion of an access group project
  - Topics: rest api, access-groups

### aliases

- [List Deployment Aliases](/docs/rest-api/aliases/list-deployment-aliases)
  - Type: Reference
  - Summary: GET /v2/deployments/{id}/aliases — Retrieves all Aliases for the Deployment with the given ID. The authenticated user or team must own the deployment.
  - Topics: rest api, aliases

- [Assign an Alias](/docs/rest-api/aliases/assign-an-alias)
  - Type: Reference
  - Summary: POST /v2/deployments/{id}/aliases — Creates a new alias for the deployment with the given deployment ID. The authenticated user or team must own this...
  - Topics: rest api, aliases

- [List aliases](/docs/rest-api/aliases/list-aliases)
  - Type: Reference
  - Summary: GET /v4/aliases — Retrieves a list of aliases for the authenticated User or Team. When \`domain\` is provided, only aliases for that domain...
  - Topics: rest api, aliases

- [Get an Alias](/docs/rest-api/aliases/get-an-alias)
  - Type: Reference
  - Summary: GET /v4/aliases/{idOrAlias} — Retrieves an Alias for the given host name or alias ID.
  - Topics: rest api, aliases

- [Delete an Alias](/docs/rest-api/aliases/delete-an-alias)
  - Type: Reference
  - Summary: DELETE /v2/aliases/{aliasId} — Delete an Alias with the specified ID.
  - Topics: rest api, aliases

- [Update the protection bypass for a URL](/docs/rest-api/aliases/update-the-protection-bypass-for-a-url)
  - Type: Reference
  - Summary: PATCH /aliases/{id}/protection-bypass — Update the protection bypass for the alias or deployment URL \(used for user access & comment access for deployments\). Used...
  - Topics: rest api, aliases

### api-observability

- [Lists disabled Observability Plus projects](/docs/rest-api/api-observability/lists-disabled-observability-plus-projects)
  - Type: Reference
  - Summary: GET /v1/observability/manage/configuration/projects — Lists the projects that are currently configured as disabled for Observability Plus on a team.
  - Topics: rest api, api-observability

- [Updates a disabled Observability Plus project setting](/docs/rest-api/api-observability/updates-a-disabled-observability-plus-project-setting)
  - Type: Reference
  - Summary: PUT /v1/observability/manage/configuration/projects/{projectIdOrName} — Updates whether Observability Plus is disabled for a single project.
  - Topics: rest api, api-observability

### artifacts

- [Record an artifacts cache usage event](/docs/rest-api/artifacts/record-an-artifacts-cache-usage-event)
  - Type: Reference
  - Summary: POST /v8/artifacts/events — Records an artifacts cache usage event. The body of this request is an array of cache usage events. The supported...
  - Topics: rest api, artifacts

- [Get status of Remote Caching for this principal](/docs/rest-api/artifacts/get-status-of-remote-caching-for-this-principal)
  - Type: Reference
  - Summary: GET /v8/artifacts/status — Check the status of Remote Caching for this principal. Returns a JSON-encoded status indicating if Remote Caching is enabled, disabled,...
  - Topics: rest api, artifacts

- [Upload a cache artifact](/docs/rest-api/artifacts/upload-a-cache-artifact)
  - Type: Reference
  - Summary: PUT /v8/artifacts/{hash} — Uploads a cache artifact identified by the \`hash\` specified on the path. The cache artifact can then be downloaded with...
  - Topics: rest api, artifacts

- [Download a cache artifact](/docs/rest-api/artifacts/download-a-cache-artifact)
  - Type: Reference
  - Summary: GET /v8/artifacts/{hash} — Downloads a cache artifact indentified by its \`hash\` specified on the request path. The artifact is downloaded as an octet-stream....
  - Topics: rest api, artifacts

- [Check if a cache artifact exists](/docs/rest-api/artifacts/check-if-a-cache-artifact-exists)
  - Type: Reference
  - Summary: HEAD /v8/artifacts/{hash} — Check that a cache artifact with the given \`hash\` exists. This request returns response headers only and is equivalent to...
  - Topics: rest api, artifacts

- [Query information about an artifact](/docs/rest-api/artifacts/query-information-about-an-artifact)
  - Type: Reference
  - Summary: POST /v8/artifacts — Query information about an array of artifacts.
  - Topics: rest api, artifacts

### authentication

- [SSO Token Exchange](/docs/rest-api/authentication/sso-token-exchange)
  - Type: Reference
  - Summary: POST /v1/integrations/sso/token — During the autorization process, Vercel sends the user to the provider \[redirectLoginUrl\]\(<https://vercel.com/docs/integrations/create-integration/submit-integration#redirect-login-url\>), that includes the OAuth authorization \`code\` parameter. The...
  - Topics: rest api, authentication

- [List Auth Tokens](/docs/rest-api/authentication/list-auth-tokens)
  - Type: Reference
  - Summary: GET /v6/user/tokens — Retrieve a list of the current User's authentication tokens.
  - Topics: rest api, authentication

- [Create an Auth Token](/docs/rest-api/authentication/create-an-auth-token)
  - Type: Reference
  - Summary: POST /v3/user/tokens — Creates and returns a new authentication token for the currently authenticated User. The \`bearerToken\` property is only provided once, in...
  - Topics: rest api, authentication

- [Get Auth Token Metadata](/docs/rest-api/authentication/get-auth-token-metadata)
  - Type: Reference
  - Summary: GET /v5/user/tokens/{tokenId} — Retrieve metadata about an authentication token belonging to the currently authenticated User.
  - Topics: rest api, authentication

- [Delete an authentication token](/docs/rest-api/authentication/delete-an-authentication-token)
  - Type: Reference
  - Summary: DELETE /v3/user/tokens/{tokenId} — Invalidate an authentication token, such that it will no longer be valid for future HTTP requests.
  - Topics: rest api, authentication

### billing

- [List FOCUS billing charges](/docs/rest-api/billing/list-focus-billing-charges)
  - Type: Reference
  - Summary: GET /v1/billing/charges — Returns the billing charge data in FOCUS v1.3 JSONL format for a specified Vercel team, within a date range specified...
  - Topics: rest api, billing

- [List FOCUS contract commitments](/docs/rest-api/billing/list-focus-contract-commitments)
  - Type: Reference
  - Summary: GET /v1/billing/contract-commitments — Returns commitment allocations per contract period in FOCUS v1.3 JSONL format for a specified Vercel team. The response is streamed...
  - Topics: rest api, billing

- [Purchase credits](/docs/rest-api/billing/purchase-credits)
  - Type: Reference
  - Summary: POST /v1/billing/buy — Purchases credits for a Vercel team using the default payment method on file. The purchase is charged immediately via Stripe...
  - Topics: rest api, billing

### bulk-redirects

- [Stages new redirects for a project.](/docs/rest-api/bulk-redirects/stages-new-redirects-for-a-project)
  - Type: Reference
  - Summary: PUT /v1/bulk-redirects — Stages new redirects for a project and returns the new version.
  - Topics: rest api, bulk-redirects

- [Gets project-level redirects.](/docs/rest-api/bulk-redirects/gets-project-level-redirects)
  - Type: Reference
  - Summary: GET /v1/bulk-redirects — Get the version history for a project's bulk redirects
  - Topics: rest api, bulk-redirects

- [Delete project-level redirects.](/docs/rest-api/bulk-redirects/delete-project-level-redirects)
  - Type: Reference
  - Summary: DELETE /v1/bulk-redirects — Deletes the provided redirects from the latest version of the projects' bulk redirects. Stages a new change with the new...
  - Topics: rest api, bulk-redirects

- [Edit a project-level redirect.](/docs/rest-api/bulk-redirects/edit-a-project-level-redirect)
  - Type: Reference
  - Summary: PATCH /v1/bulk-redirects — Edits a single redirect identified by its source path. Stages a new change with the modified redirect and returns the...
  - Topics: rest api, bulk-redirects

- [Restore staged project-level redirects to their production version.](/docs/rest-api/bulk-redirects/restore-staged-project-level-redirects-to-their-production-version)
  - Type: Reference
  - Summary: POST /v1/bulk-redirects/restore — Restores the provided redirects in the staging version to the value in the production version. If no production version exists,...
  - Topics: rest api, bulk-redirects

- [Get the version history for a project's redirects.](/docs/rest-api/bulk-redirects/get-the-version-history-for-a-project-s-redirects)
  - Type: Reference
  - Summary: GET /v1/bulk-redirects/versions — Get the version history for a project's bulk redirects
  - Topics: rest api, bulk-redirects

- [Promote a staging version to production or restore a previous production version.](/docs/rest-api/bulk-redirects/promote-a-staging-version-to-production-or-restore-a-previous-production-version)
  - Type: Reference
  - Summary: POST /v1/bulk-redirects/versions — Update a version by promoting staging to production or restoring a previous production version
  - Topics: rest api, bulk-redirects

### certs

- [Get cert by id](/docs/rest-api/certs/get-cert-by-id)
  - Type: Reference
  - Summary: GET /v8/certs/{id} — Get cert by id
  - Topics: rest api, certs

- [Remove cert](/docs/rest-api/certs/remove-cert)
  - Type: Reference
  - Summary: DELETE /v8/certs/{id} — Remove cert
  - Topics: rest api, certs

- [Issue a new cert](/docs/rest-api/certs/issue-a-new-cert)
  - Type: Reference
  - Summary: POST /v8/certs — Issue a new cert
  - Topics: rest api, certs

- [Upload a cert](/docs/rest-api/certs/upload-a-cert)
  - Type: Reference
  - Summary: PUT /v8/certs — Upload a cert
  - Topics: rest api, certs

### checks-v2

- [List all checks for a project](/docs/rest-api/checks-v2/list-all-checks-for-a-project)
  - Type: Reference
  - Summary: GET /v2/projects/{projectIdOrName}/checks — List all checks for a project, optionally filtered by target.
  - Topics: rest api, checks-v2

- [Create a check](/docs/rest-api/checks-v2/create-a-check)
  - Type: Reference
  - Summary: POST /v2/projects/{projectIdOrName}/checks — Creates a new check for a project.
  - Topics: rest api, checks-v2

- [Get a check](/docs/rest-api/checks-v2/get-a-check)
  - Type: Reference
  - Summary: GET /v2/projects/{projectIdOrName}/checks/{checkId} — Return a detailed response for a single check.
  - Topics: rest api, checks-v2

- [Update a check](/docs/rest-api/checks-v2/update-a-check)
  - Type: Reference
  - Summary: PATCH /v2/projects/{projectIdOrName}/checks/{checkId} — Update an existing check.
  - Topics: rest api, checks-v2

- [Delete a check](/docs/rest-api/checks-v2/delete-a-check)
  - Type: Reference
  - Summary: DELETE /v2/projects/{projectIdOrName}/checks/{checkId} — Delete an existing check and all of its runs.
  - Topics: rest api, checks-v2

- [List runs for a check](/docs/rest-api/checks-v2/list-runs-for-a-check)
  - Type: Reference
  - Summary: GET /v2/projects/{projectIdOrName}/checks/{checkId}/runs — List all runs associated with a given check.
  - Topics: rest api, checks-v2

- [List check runs for a deployment](/docs/rest-api/checks-v2/list-check-runs-for-a-deployment)
  - Type: Reference
  - Summary: GET /v2/deployments/{deploymentId}/check-runs — List all check runs for a deployment.
  - Topics: rest api, checks-v2

- [Create a check run](/docs/rest-api/checks-v2/create-a-check-run)
  - Type: Reference
  - Summary: POST /v2/deployments/{deploymentId}/check-runs — Creates a new check run for a deployment.
  - Topics: rest api, checks-v2

- [Get a check run](/docs/rest-api/checks-v2/get-a-check-run)
  - Type: Reference
  - Summary: GET /v2/deployments/{deploymentId}/check-runs/{checkRunId} — Return a detailed response for a single check run.
  - Topics: rest api, checks-v2

- [Update a check run](/docs/rest-api/checks-v2/update-a-check-run)
  - Type: Reference
  - Summary: PATCH /v2/deployments/{deploymentId}/check-runs/{checkRunId} — Update an existing check run for a deployment.
  - Topics: rest api, checks-v2

### connect

- [List Secure Compute networks](/docs/rest-api/connect/list-secure-compute-networks)
  - Type: Reference
  - Summary: GET /v1/connect/networks — Allows to list Secure Compute networks.
  - Topics: rest api, connect

- [Create a Secure Compute network](/docs/rest-api/connect/create-a-secure-compute-network)
  - Type: Reference
  - Summary: POST /v1/connect/networks — Allows to create a Secure Compute network.
  - Topics: rest api, connect

- [Delete a Secure Compute network](/docs/rest-api/connect/delete-a-secure-compute-network)
  - Type: Reference
  - Summary: DELETE /v1/connect/networks/{networkId} — Allows to delete a Secure Compute network.
  - Topics: rest api, connect

- [Update a Secure Compute network](/docs/rest-api/connect/update-a-secure-compute-network)
  - Type: Reference
  - Summary: PATCH /v1/connect/networks/{networkId} — Allows to update a Secure Compute network.
  - Topics: rest api, connect

- [Read a Secure Compute network](/docs/rest-api/connect/read-a-secure-compute-network)
  - Type: Reference
  - Summary: GET /v1/connect/networks/{networkId} — Allows to read a Secure Compute network.
  - Topics: rest api, connect

- [Configures Static IPs for a project](/docs/rest-api/connect/configures-static-ip-s-for-a-project)
  - Type: Reference
  - Summary: PATCH /v1/projects/{idOrName}/shared-connect-links — Allows configuring Static IPs for a project
  - Topics: rest api, connect

### deployments

- [Get deployment events](/docs/rest-api/deployments/get-deployment-events)
  - Type: Reference
  - Summary: GET /v3/deployments/{idOrUrl}/events — Get the build logs of a deployment by deployment ID and build ID. It can work as an infinite stream...
  - Topics: rest api, deployments

- [Update deployment integration action](/docs/rest-api/deployments/update-deployment-integration-action)
  - Type: Reference
  - Summary: PATCH /v1/deployments/{deploymentId}/integrations/{integrationConfigurationId}/resources/{resourceId}/actions/{action} — Updates the deployment integration action for the specified integration installation
  - Topics: rest api, deployments

- [Get a deployment by ID or URL](/docs/rest-api/deployments/get-a-deployment-by-id-or-url)
  - Type: Reference
  - Summary: GET /v13/deployments/{idOrUrl} — Retrieves information for a deployment either by supplying its ID \(\`id\` property\) or Hostname \(\`url\` property\). Additional details will be...
  - Topics: rest api, deployments

- [Create a new deployment](/docs/rest-api/deployments/create-a-new-deployment)
  - Type: Reference
  - Summary: POST /v13/deployments — Create a new deployment with all the required and intended data. If the deployment is not a git deployment, all...
  - Topics: rest api, deployments

- [Cancel a deployment](/docs/rest-api/deployments/cancel-a-deployment)
  - Type: Reference
  - Summary: PATCH /v12/deployments/{id}/cancel — This endpoint allows you to cancel a deployment which is currently building, by supplying its \`id\` in the URL.
  - Topics: rest api, deployments

- [Upload Deployment Files](/docs/rest-api/deployments/upload-deployment-files)
  - Type: Reference
  - Summary: POST /v2/files — Before you create a deployment you need to upload the required files for that deployment. To do it, you need...
  - Topics: rest api, deployments

- [List Deployment Files](/docs/rest-api/deployments/list-deployment-files)
  - Type: Reference
  - Summary: GET /v6/deployments/{id}/files — Allows to retrieve the file structure of the source code of a deployment by supplying the deployment unique identifier. If...
  - Topics: rest api, deployments

- [Get Deployment File Contents](/docs/rest-api/deployments/get-deployment-file-contents)
  - Type: Reference
  - Summary: GET /v8/deployments/{id}/files/{fileId} — Allows to retrieve the content of a file by supplying the file identifier and the deployment unique identifier. The response...
  - Topics: rest api, deployments

- [List deployments](/docs/rest-api/deployments/list-deployments)
  - Type: Reference
  - Summary: GET /v6/deployments — List deployments under the authenticated user or team. If a deployment hasn't finished uploading \(is incomplete\), the \`url\` property will...
  - Topics: rest api, deployments

- [Delete a Deployment](/docs/rest-api/deployments/delete-a-deployment)
  - Type: Reference
  - Summary: DELETE /v13/deployments/{id} — This API allows you to delete a deployment, either by supplying its \`id\` in the URL or the \`url\` of...
  - Topics: rest api, deployments

### dns

- [List existing DNS records](/docs/rest-api/dns/list-existing-dns-records)
  - Type: Reference
  - Summary: GET /v5/domains/{domain}/records — Retrieves a list of DNS records created for a domain name. By default it returns 20 records if no limit...
  - Topics: rest api, dns

- [Create a DNS record](/docs/rest-api/dns/create-a-dns-record)
  - Type: Reference
  - Summary: POST /v2/domains/{domain}/records — Creates a DNS record for a domain.
  - Topics: rest api, dns

- [Update an existing DNS record](/docs/rest-api/dns/update-an-existing-dns-record)
  - Type: Reference
  - Summary: PATCH /v1/domains/records/{recordId} — Updates an existing DNS record for a domain name.
  - Topics: rest api, dns

- [Delete a DNS record](/docs/rest-api/dns/delete-a-dns-record)
  - Type: Reference
  - Summary: DELETE /v2/domains/{domain}/records/{recordId} — Removes an existing DNS record from a domain name.
  - Topics: rest api, dns

### domains

- [Get a Domain's configuration](/docs/rest-api/domains/get-a-domain-s-configuration)
  - Type: Reference
  - Summary: GET /v6/domains/{domain}/config — Get a Domain's configuration.
  - Topics: rest api, domains

- [Get Information for a Single Domain](/docs/rest-api/domains/get-information-for-a-single-domain)
  - Type: Reference
  - Summary: GET /v5/domains/{domain} — Get information for a single domain in an account or team.
  - Topics: rest api, domains

- [List all the domains](/docs/rest-api/domains/list-all-the-domains)
  - Type: Reference
  - Summary: GET /v5/domains — Retrieves a list of domains registered for the authenticated user or team. By default it returns the last 20 domains...
  - Topics: rest api, domains

- [Add an existing domain to the Vercel platform](/docs/rest-api/domains/add-an-existing-domain-to-the-vercel-platform)
  - Type: Reference
  - Summary: POST /v7/domains — This endpoint is used for adding a new apex domain name with Vercel for the authenticating user. Note: This endpoint...
  - Topics: rest api, domains

- [Update or move apex domain](/docs/rest-api/domains/update-or-move-apex-domain)
  - Type: Reference
  - Summary: PATCH /v3/domains/{domain} — Update or move apex domain. Note: This endpoint is no longer used for updating auto-renew or nameservers. For this, please...
  - Topics: rest api, domains

- [Remove a domain by name](/docs/rest-api/domains/remove-a-domain-by-name)
  - Type: Reference
  - Summary: DELETE /v6/domains/{domain} — Delete a previously registered domain name from Vercel. Deleting a domain will automatically remove any associated aliases.
  - Topics: rest api, domains

### domains-registrar

- [Get supported TLDs](/docs/rest-api/domains-registrar/get-supported-tld-s)
  - Type: Reference
  - Summary: GET /v1/registrar/tlds/supported — Get a list of TLDs supported by Vercel
  - Topics: rest api, domains-registrar

- [Get TLD](/docs/rest-api/domains-registrar/get-tld)
  - Type: Reference
  - Summary: GET /v1/registrar/tlds/{tld} — Get the metadata for a specific TLD.
  - Topics: rest api, domains-registrar

- [Get TLD price data](/docs/rest-api/domains-registrar/get-tld-price-data)
  - Type: Reference
  - Summary: GET /v1/registrar/tlds/{tld}/price — Get price data for a specific TLD. This only reflects base prices for the given TLD. Premium domains may have...
  - Topics: rest api, domains-registrar

- [Get availability for a domain](/docs/rest-api/domains-registrar/get-availability-for-a-domain)
  - Type: Reference
  - Summary: GET /v1/registrar/domains/{domain}/availability — Get availability for a specific domain. If the domain is available, it can be purchased using the \[Buy a domain\]\(<https://vercel.com/docs/rest-api/reference/endpoints/domains-registrar/buy-a-domain\>)...
  - Topics: rest api, domains-registrar

- [Get price data for a domain](/docs/rest-api/domains-registrar/get-price-data-for-a-domain)
  - Type: Reference
  - Summary: GET /v1/registrar/domains/{domain}/price — Get price data for a specific domain
  - Topics: rest api, domains-registrar

- [Get availability for multiple domains](/docs/rest-api/domains-registrar/get-availability-for-multiple-domains)
  - Type: Reference
  - Summary: POST /v1/registrar/domains/availability — Get availability for multiple domains. If the domains are available, they can be purchased using the \[Buy a domain\]\(<https://vercel.com/docs/rest-api/reference/endpoints/domains-registrar/buy-a-domain\>) endpoint...
  - Topics: rest api, domains-registrar

- [Get the auth code for a domain](/docs/rest-api/domains-registrar/get-the-auth-code-for-a-domain)
  - Type: Reference
  - Summary: GET /v1/registrar/domains/{domain}/auth-code — Get the auth code for a domain. This is required to transfer a domain from Vercel to another registrar.
  - Topics: rest api, domains-registrar

- [Buy a domain](/docs/rest-api/domains-registrar/buy-a-domain)
  - Type: Reference
  - Summary: POST /v1/registrar/domains/{domain}/buy — Buy a domain
  - Topics: rest api, domains-registrar

- [Buy multiple domains](/docs/rest-api/domains-registrar/buy-multiple-domains)
  - Type: Reference
  - Summary: POST /v1/registrar/domains/buy — Buy multiple domains at once
  - Topics: rest api, domains-registrar

- [Transfer-in a domain](/docs/rest-api/domains-registrar/transfer-in-a-domain)
  - Type: Reference
  - Summary: POST /v1/registrar/domains/{domain}/transfer — Transfer a domain in from another registrar
  - Topics: rest api, domains-registrar

- [Get a domain's transfer status](/docs/rest-api/domains-registrar/get-a-domain-s-transfer-status)
  - Type: Reference
  - Summary: GET /v1/registrar/domains/{domain}/transfer — Get the transfer status for a domain
  - Topics: rest api, domains-registrar

- [Renew a domain](/docs/rest-api/domains-registrar/renew-a-domain)
  - Type: Reference
  - Summary: POST /v1/registrar/domains/{domain}/renew — Renew a domain
  - Topics: rest api, domains-registrar

- [Update auto-renew for a domain](/docs/rest-api/domains-registrar/update-auto-renew-for-a-domain)
  - Type: Reference
  - Summary: PATCH /v1/registrar/domains/{domain}/auto-renew — Update the auto-renew setting for a domain
  - Topics: rest api, domains-registrar

- [Update nameservers for a domain](/docs/rest-api/domains-registrar/update-nameservers-for-a-domain)
  - Type: Reference
  - Summary: PATCH /v1/registrar/domains/{domain}/nameservers — Update the nameservers for a domain. Pass an empty array to use Vercel's default nameservers.
  - Topics: rest api, domains-registrar

- [Get contact info schema](/docs/rest-api/domains-registrar/get-contact-info-schema)
  - Type: Reference
  - Summary: GET /v1/registrar/domains/{domain}/contact-info/schema — Some TLDs require additional contact information. Use this endpoint to get the schema for the tld-specific contact information for a...
  - Topics: rest api, domains-registrar

- [Get a domain order](/docs/rest-api/domains-registrar/get-a-domain-order)
  - Type: Reference
  - Summary: GET /v1/registrar/orders/{orderId} — Get information about a domain order by its ID
  - Topics: rest api, domains-registrar

### drains

- [Create a new Drain](/docs/rest-api/drains/create-a-new-drain)
  - Type: Reference
  - Summary: POST /v1/drains — Create a new Drain with the provided configuration.
  - Topics: rest api, drains

- [Retrieve a list of all Drains](/docs/rest-api/drains/retrieve-a-list-of-all-drains)
  - Type: Reference
  - Summary: GET /v1/drains — Allows to retrieve the list of Drains of the authenticated team.
  - Topics: rest api, drains

- [Delete a drain](/docs/rest-api/drains/delete-a-drain)
  - Type: Reference
  - Summary: DELETE /v1/drains/{id} — Delete a specific Drain by passing the drain id in the URL.
  - Topics: rest api, drains

- [Find a Drain by id](/docs/rest-api/drains/find-a-drain-by-id)
  - Type: Reference
  - Summary: GET /v1/drains/{id} — Get the information for a specific Drain by passing the drain id in the URL.
  - Topics: rest api, drains

- [Update an existing Drain](/docs/rest-api/drains/update-an-existing-drain)
  - Type: Reference
  - Summary: PATCH /v1/drains/{id} — Update the configuration of an existing drain.
  - Topics: rest api, drains

- [Validate Drain delivery configuration](/docs/rest-api/drains/validate-drain-delivery-configuration)
  - Type: Reference
  - Summary: POST /v1/drains/test — Validate the delivery configuration of a Drain using sample events.
  - Topics: rest api, drains

### edge-cache

- [Invalidate by tag](/docs/rest-api/edge-cache/invalidate-by-tag)
  - Type: Reference
  - Summary: POST /v1/edge-cache/invalidate-by-tags — Marks a cache tag as stale, causing cache entries associated with that tag to be revalidated in the background on...
  - Topics: rest api, edge-cache

- [Dangerously delete by tag](/docs/rest-api/edge-cache/dangerously-delete-by-tag)
  - Type: Reference
  - Summary: POST /v1/edge-cache/dangerously-delete-by-tags — Marks a cache tag as deleted, causing cache entries associated with that tag to be revalidated in the foreground on...
  - Topics: rest api, edge-cache

- [Invalidate by source image](/docs/rest-api/edge-cache/invalidate-by-source-image)
  - Type: Reference
  - Summary: POST /v1/edge-cache/invalidate-by-src-images — Marks a source image as stale, causing its corresponding transformed images to be revalidated in the background on the next...
  - Topics: rest api, edge-cache

- [Dangerously delete by source image](/docs/rest-api/edge-cache/dangerously-delete-by-source-image)
  - Type: Reference
  - Summary: POST /v1/edge-cache/dangerously-delete-by-src-images — Marks a source image as deleted, causing cache entries associated with that source image to be revalidated in the foreground...
  - Topics: rest api, edge-cache

### edge-config

- [Get Edge Configs](/docs/rest-api/edge-config/get-edge-configs)
  - Type: Reference
  - Summary: GET /v1/edge-config — Returns all Edge Configs.
  - Topics: rest api, edge-config

- [Create an Edge Config](/docs/rest-api/edge-config/create-an-edge-config)
  - Type: Reference
  - Summary: POST /v1/edge-config — Creates an Edge Config.
  - Topics: rest api, edge-config

- [Get an Edge Config](/docs/rest-api/edge-config/get-an-edge-config)
  - Type: Reference
  - Summary: GET /v1/edge-config/{edgeConfigId} — Returns an Edge Config.
  - Topics: rest api, edge-config

- [Update an Edge Config](/docs/rest-api/edge-config/update-an-edge-config)
  - Type: Reference
  - Summary: PUT /v1/edge-config/{edgeConfigId} — Updates an Edge Config.
  - Topics: rest api, edge-config

- [Delete an Edge Config](/docs/rest-api/edge-config/delete-an-edge-config)
  - Type: Reference
  - Summary: DELETE /v1/edge-config/{edgeConfigId} — Delete an Edge Config by id.
  - Topics: rest api, edge-config

- [Get Edge Config items](/docs/rest-api/edge-config/get-edge-config-items)
  - Type: Reference
  - Summary: GET /v1/edge-config/{edgeConfigId}/items — Returns all items of an Edge Config.
  - Topics: rest api, edge-config

- [Update Edge Config items in batch](/docs/rest-api/edge-config/update-edge-config-items-in-batch)
  - Type: Reference
  - Summary: PATCH /v1/edge-config/{edgeConfigId}/items — Update multiple Edge Config Items in batch.
  - Topics: rest api, edge-config

- [Get Edge Config schema](/docs/rest-api/edge-config/get-edge-config-schema)
  - Type: Reference
  - Summary: GET /v1/edge-config/{edgeConfigId}/schema — Returns the schema of an Edge Config.
  - Topics: rest api, edge-config

- [Update Edge Config schema](/docs/rest-api/edge-config/update-edge-config-schema)
  - Type: Reference
  - Summary: POST /v1/edge-config/{edgeConfigId}/schema — Update an Edge Config's schema.
  - Topics: rest api, edge-config

- [Delete an Edge Config's schema](/docs/rest-api/edge-config/delete-an-edge-config-s-schema)
  - Type: Reference
  - Summary: DELETE /v1/edge-config/{edgeConfigId}/schema — Deletes the schema of existing Edge Config.
  - Topics: rest api, edge-config

- [Get an Edge Config item](/docs/rest-api/edge-config/get-an-edge-config-item)
  - Type: Reference
  - Summary: GET /v1/edge-config/{edgeConfigId}/item/{edgeConfigItemKey} — Returns a specific Edge Config Item.
  - Topics: rest api, edge-config

- [Get all tokens of an Edge Config](/docs/rest-api/edge-config/get-all-tokens-of-an-edge-config)
  - Type: Reference
  - Summary: GET /v1/edge-config/{edgeConfigId}/tokens — Returns all tokens of an Edge Config.
  - Topics: rest api, edge-config

- [Delete one or more Edge Config tokens](/docs/rest-api/edge-config/delete-one-or-more-edge-config-tokens)
  - Type: Reference
  - Summary: DELETE /v1/edge-config/{edgeConfigId}/tokens — Deletes one or more tokens of an existing Edge Config.
  - Topics: rest api, edge-config

- [Get Edge Config token meta data](/docs/rest-api/edge-config/get-edge-config-token-meta-data)
  - Type: Reference
  - Summary: GET /v1/edge-config/{edgeConfigId}/token/{token} — Return meta data about an Edge Config token.
  - Topics: rest api, edge-config

- [Create an Edge Config token](/docs/rest-api/edge-config/create-an-edge-config-token)
  - Type: Reference
  - Summary: POST /v1/edge-config/{edgeConfigId}/token — Adds a token to an existing Edge Config.
  - Topics: rest api, edge-config

- [Get Edge Config backup](/docs/rest-api/edge-config/get-edge-config-backup)
  - Type: Reference
  - Summary: GET /v1/edge-config/{edgeConfigId}/backups/{edgeConfigBackupVersionId} — Retrieves a specific version of an Edge Config from backup storage.
  - Topics: rest api, edge-config

- [Get Edge Config backups](/docs/rest-api/edge-config/get-edge-config-backups)
  - Type: Reference
  - Summary: GET /v1/edge-config/{edgeConfigId}/backups — Returns backups of an Edge Config.
  - Topics: rest api, edge-config

### environment

- [Create one or more shared environment variables](/docs/rest-api/environment/create-one-or-more-shared-environment-variables)
  - Type: Reference
  - Summary: POST /v1/env — Creates shared environment variable\(s\) for a team.
  - Topics: rest api, environment

- [Lists all Shared Environment Variables for a team](/docs/rest-api/environment/lists-all-shared-environment-variables-for-a-team)
  - Type: Reference
  - Summary: GET /v1/env — Lists all Shared Environment Variables for a team, taking into account optional filters.
  - Topics: rest api, environment

- [Updates one or more shared environment variables](/docs/rest-api/environment/updates-one-or-more-shared-environment-variables)
  - Type: Reference
  - Summary: PATCH /v1/env — Updates a given Shared Environment Variable for a Team.
  - Topics: rest api, environment

- [Delete one or more Env Var](/docs/rest-api/environment/delete-one-or-more-env-var)
  - Type: Reference
  - Summary: DELETE /v1/env — Deletes one or many Shared Environment Variables for a given team.
  - Topics: rest api, environment

- [Retrieve the decrypted value of a Shared Environment Variable by id.](/docs/rest-api/environment/retrieve-the-decrypted-value-of-a-shared-environment-variable-by-id)
  - Type: Reference
  - Summary: GET /v1/env/{id} — Retrieve the decrypted value of a Shared Environment Variable by id.
  - Topics: rest api, environment

- [Disconnects a shared environment variable for a given project](/docs/rest-api/environment/disconnects-a-shared-environment-variable-for-a-given-project)
  - Type: Reference
  - Summary: PATCH /v1/env/{id}/unlink/{projectId} — Disconnects a shared environment variable for a given project
  - Topics: rest api, environment

- [Create a custom environment for the current project.](/docs/rest-api/environment/create-a-custom-environment-for-the-current-project)
  - Type: Reference
  - Summary: POST /v9/projects/{idOrName}/custom-environments — Creates a custom environment for the current project. Cannot be named 'Production' or 'Preview'.
  - Topics: rest api, environment

- [Retrieve custom environments](/docs/rest-api/environment/retrieve-custom-environments)
  - Type: Reference
  - Summary: GET /v9/projects/{idOrName}/custom-environments — Retrieve custom environments for the project. Must not be named 'Production' or 'Preview'.
  - Topics: rest api, environment

- [Retrieve a custom environment](/docs/rest-api/environment/retrieve-a-custom-environment)
  - Type: Reference
  - Summary: GET /v9/projects/{idOrName}/custom-environments/{environmentSlugOrId} — Retrieve a custom environment for the project. Must not be named 'Production' or 'Preview'.
  - Topics: rest api, environment

- [Update a custom environment](/docs/rest-api/environment/update-a-custom-environment)
  - Type: Reference
  - Summary: PATCH /v9/projects/{idOrName}/custom-environments/{environmentSlugOrId} — Update a custom environment for the project. Must not be named 'Production' or 'Preview'.
  - Topics: rest api, environment

- [Remove a custom environment](/docs/rest-api/environment/remove-a-custom-environment)
  - Type: Reference
  - Summary: DELETE /v9/projects/{idOrName}/custom-environments/{environmentSlugOrId} — Remove a custom environment for the project. Must not be named 'Production' or 'Preview'.
  - Topics: rest api, environment

### feature-flags

- [List flags](/docs/rest-api/feature-flags/list-flags)
  - Type: Reference
  - Summary: GET /v1/projects/{projectIdOrName}/feature-flags/flags — Retrieve feature flags for a project. The list can be filtered by state and supports pagination.
  - Topics: rest api, feature-flags

- [Create a flag](/docs/rest-api/feature-flags/create-a-flag)
  - Type: Reference
  - Summary: PUT /v1/projects/{projectIdOrName}/feature-flags/flags — Create a new feature flag for a project. The flag must have a unique slug within the project and specify...
  - Topics: rest api, feature-flags

- [Get a flag](/docs/rest-api/feature-flags/get-a-flag)
  - Type: Reference
  - Summary: GET /v1/projects/{projectIdOrName}/feature-flags/flags/{flagIdOrSlug} — Retrieve a specific feature flag by its ID or slug.
  - Topics: rest api, feature-flags

- [Update a flag](/docs/rest-api/feature-flags/update-a-flag)
  - Type: Reference
  - Summary: PATCH /v1/projects/{projectIdOrName}/feature-flags/flags/{flagIdOrSlug} — Update an existing feature flag. This endpoint supports partial updates, allowing you to modify specific properties like variants, environments, or...
  - Topics: rest api, feature-flags

- [Delete a flag](/docs/rest-api/feature-flags/delete-a-flag)
  - Type: Reference
  - Summary: DELETE /v1/projects/{projectIdOrName}/feature-flags/flags/{flagIdOrSlug} — Permanently delete a feature flag from the project. This action cannot be undone. Consider archiving the flag instead if you...
  - Topics: rest api, feature-flags

- [List flag versions](/docs/rest-api/feature-flags/list-flag-versions)
  - Type: Reference
  - Summary: GET /v1/projects/{projectIdOrName}/feature-flags/flags/{flagIdOrSlug}/versions — Lists flag versions for a given flag.
  - Topics: rest api, feature-flags

- [Get project flag settings](/docs/rest-api/feature-flags/get-project-flag-settings)
  - Type: Reference
  - Summary: GET /v1/projects/{projectIdOrName}/feature-flags/settings — Retrieve feature flag settings for a project.
  - Topics: rest api, feature-flags

- [Update project flag settings](/docs/rest-api/feature-flags/update-project-flag-settings)
  - Type: Reference
  - Summary: PATCH /v1/projects/{projectIdOrName}/feature-flags/settings — Update feature flag settings for a project.
  - Topics: rest api, feature-flags

- [List team project flag settings](/docs/rest-api/feature-flags/list-team-project-flag-settings)
  - Type: Reference
  - Summary: GET /v1/teams/{teamId}/feature-flags/settings — Retrieve feature flag settings for projects in a team.
  - Topics: rest api, feature-flags

- [List all flags for a team](/docs/rest-api/feature-flags/list-all-flags-for-a-team)
  - Type: Reference
  - Summary: GET /v1/teams/{teamId}/feature-flags/flags — Retrieve all feature flags for a team across all projects. The list can be filtered by state and supports pagination.
  - Topics: rest api, feature-flags

- [Create a segment](/docs/rest-api/feature-flags/create-a-segment)
  - Type: Reference
  - Summary: PUT /v1/projects/{projectIdOrName}/feature-flags/segments — Create a new feature flag segment.
  - Topics: rest api, feature-flags

- [List segments](/docs/rest-api/feature-flags/list-segments)
  - Type: Reference
  - Summary: GET /v1/projects/{projectIdOrName}/feature-flags/segments — List all feature flag segments for a project.
  - Topics: rest api, feature-flags

- [Get a segment](/docs/rest-api/feature-flags/get-a-segment)
  - Type: Reference
  - Summary: GET /v1/projects/{projectIdOrName}/feature-flags/segments/{segmentIdOrSlug} — Retrieve a feature flag segment by ID or slug.
  - Topics: rest api, feature-flags

- [Delete a segment](/docs/rest-api/feature-flags/delete-a-segment)
  - Type: Reference
  - Summary: DELETE /v1/projects/{projectIdOrName}/feature-flags/segments/{segmentIdOrSlug} — Delete a feature flag segment.
  - Topics: rest api, feature-flags

- [Update a segment](/docs/rest-api/feature-flags/update-a-segment)
  - Type: Reference
  - Summary: PATCH /v1/projects/{projectIdOrName}/feature-flags/segments/{segmentIdOrSlug} — Update an existing feature flag segment.
  - Topics: rest api, feature-flags

- [Retrieve the feature flags of a deployment](/docs/rest-api/feature-flags/retrieve-the-feature-flags-of-a-deployment)
  - Type: Reference
  - Summary: GET /v1/deployments/{deploymentId}/feature-flags — Retrieve the feature flags of a deployment.
  - Topics: rest api, feature-flags

- [Get all SDK keys](/docs/rest-api/feature-flags/get-all-sdk-keys)
  - Type: Reference
  - Summary: GET /v1/projects/{projectIdOrName}/feature-flags/sdk-keys — Gets all SDK keys for a project.
  - Topics: rest api, feature-flags

- [Create an SDK key](/docs/rest-api/feature-flags/create-an-sdk-key)
  - Type: Reference
  - Summary: PUT /v1/projects/{projectIdOrName}/feature-flags/sdk-keys — Creates an SDK key.
  - Topics: rest api, feature-flags

- [Delete an SDK key](/docs/rest-api/feature-flags/delete-an-sdk-key)
  - Type: Reference
  - Summary: DELETE /v1/projects/{projectIdOrName}/feature-flags/sdk-keys/{hashKey} — Deletes an SDK key.
  - Topics: rest api, feature-flags

### integrations

- [List git namespaces by provider](/docs/rest-api/integrations/list-git-namespaces-by-provider)
  - Type: Reference
  - Summary: GET /v1/integrations/git-namespaces — Lists git namespaces for a supported provider. Supported providers are \`github\`, \`gitlab\` and \`bitbucket\`. If the provider is not provided,...
  - Topics: rest api, integrations

- [List git repositories linked to namespace by provider](/docs/rest-api/integrations/list-git-repositories-linked-to-namespace-by-provider)
  - Type: Reference
  - Summary: GET /v1/integrations/search-repo — Lists git repositories linked to a namespace \`id\` for a supported provider. A specific namespace \`id\` can be obtained via...
  - Topics: rest api, integrations

- [List integration billing plans](/docs/rest-api/integrations/list-integration-billing-plans)
  - Type: Reference
  - Summary: GET /v1/integrations/integration/{integrationIdOrSlug}/products/{productIdOrSlug}/plans — Get a list of billing plans for an integration and product.
  - Topics: rest api, integrations

- [Connect integration resource to project](/docs/rest-api/integrations/connect-integration-resource-to-project)
  - Type: Reference
  - Summary: POST /v1/integrations/installations/{integrationConfigurationId}/resources/{resourceId}/connections — Connects an integration resource to a Vercel project. This endpoint establishes a connection between a provisioned integration resource \(from storage...
  - Topics: rest api, integrations

- [Get configurations for the authenticated user or team](/docs/rest-api/integrations/get-configurations-for-the-authenticated-user-or-team)
  - Type: Reference
  - Summary: GET /v1/integrations/configurations — Allows to retrieve all configurations for an authenticated integration. When the \`project\` view is used, configurations generated for the authorization...
  - Topics: rest api, integrations

- [Retrieve an integration configuration](/docs/rest-api/integrations/retrieve-an-integration-configuration)
  - Type: Reference
  - Summary: GET /v1/integrations/configuration/{id} — Allows to retrieve a the configuration with the provided id in case it exists. The authenticated user or team must...
  - Topics: rest api, integrations

- [Delete an integration configuration](/docs/rest-api/integrations/delete-an-integration-configuration)
  - Type: Reference
  - Summary: DELETE /v1/integrations/configuration/{id} — Allows to remove the configuration with the \`id\` provided in the parameters. The configuration and all of its resources will...
  - Topics: rest api, integrations

- [List products for integration configuration](/docs/rest-api/integrations/list-products-for-integration-configuration)
  - Type: Reference
  - Summary: GET /v1/integrations/configuration/{id}/products — Returns products available for an integration configuration. Each product includes a \`metadataSchema\` field with the JSON Schema for required and...
  - Topics: rest api, integrations

- [Create integration store \(free and paid plans\)](/docs/rest-api/integrations/create-integration-store-free-and-paid-plans)
  - Type: Reference
  - Summary: POST /v1/storage/stores/integration/direct — Creates an integration store with automatic billing plan handling. For free resources, omit \`billingPlanId\` to auto-discover free plans. For paid...
  - Topics: rest api, integrations

### logDrains

- [Retrieves a Configurable Log Drain \(deprecated\)](/docs/rest-api/logDrains/retrieves-a-configurable-log-drain-deprecated)
  - Type: Reference
  - Summary: GET /v1/log-drains/{id} — Retrieves a Configurable Log Drain. This endpoint must be called with a team AccessToken \(integration OAuth2 clients are not allowed\)....
  - Topics: rest api, logdrains

- [Deletes a Configurable Log Drain \(deprecated\)](/docs/rest-api/logDrains/deletes-a-configurable-log-drain-deprecated)
  - Type: Reference
  - Summary: DELETE /v1/log-drains/{id} — Deletes a Configurable Log Drain. This endpoint must be called with a team AccessToken \(integration OAuth2 clients are not allowed\)....
  - Topics: rest api, logdrains

- [Retrieves a list of all the Log Drains \(deprecated\)](/docs/rest-api/logDrains/retrieves-a-list-of-all-the-log-drains-deprecated)
  - Type: Reference
  - Summary: GET /v1/log-drains — Retrieves a list of all the Log Drains owned by the account. This endpoint must be called with an account...
  - Topics: rest api, logdrains

- [Creates a Configurable Log Drain \(deprecated\)](/docs/rest-api/logDrains/creates-a-configurable-log-drain-deprecated)
  - Type: Reference
  - Summary: POST /v1/log-drains — Creates a configurable log drain. This endpoint must be called with a team AccessToken \(integration OAuth2 clients are not allowed\)
  - Topics: rest api, logdrains

- [Retrieves a list of Integration log drains \(deprecated\)](/docs/rest-api/logDrains/retrieves-a-list-of-integration-log-drains-deprecated)
  - Type: Reference
  - Summary: GET /v2/integrations/log-drains — Retrieves a list of all Integration log drains that are defined for the authenticated user or team. When using an...
  - Topics: rest api, logdrains

- [Creates a new Integration Log Drain \(deprecated\)](/docs/rest-api/logDrains/creates-a-new-integration-log-drain-deprecated)
  - Type: Reference
  - Summary: POST /v2/integrations/log-drains — Creates an Integration log drain. This endpoint must be called with an OAuth2 client \(integration\), since log drains are tied...
  - Topics: rest api, logdrains

- [Deletes the Integration log drain with the provided \`id\` \(deprecated\)](/docs/rest-api/logDrains/deletes-the-integration-log-drain-with-the-provided-id-deprecated)
  - Type: Reference
  - Summary: DELETE /v1/integrations/log-drains/{id} — Deletes the Integration log drain with the provided \`id\`. When using an OAuth2 Token, the log drain can be deleted...
  - Topics: rest api, logdrains

### logs

- [Get logs for a deployment](/docs/rest-api/logs/get-logs-for-a-deployment)
  - Type: Reference
  - Summary: GET /v1/projects/{projectId}/deployments/{deploymentId}/runtime-logs — Returns a stream of logs for a given deployment.
  - Topics: rest api, logs

### marketplace

- [Update Installation](/docs/rest-api/marketplace/update-installation)
  - Type: Reference
  - Summary: PATCH /v1/installations/{integrationConfigurationId} — This endpoint updates an integration installation.
  - Topics: rest api, marketplace

- [Get Account Information](/docs/rest-api/marketplace/get-account-information)
  - Type: Reference
  - Summary: GET /v1/installations/{integrationConfigurationId}/account — Fetches the best account or user’s contact info
  - Topics: rest api, marketplace

- [Get Member Information](/docs/rest-api/marketplace/get-member-information)
  - Type: Reference
  - Summary: GET /v1/installations/{integrationConfigurationId}/member/{memberId} — Returns the member role and other information for a given member ID \("user_id" claim in the SSO OIDC token\).
  - Topics: rest api, marketplace

- [Create Event](/docs/rest-api/marketplace/create-event)
  - Type: Reference
  - Summary: POST /v1/installations/{integrationConfigurationId}/events — Partner notifies Vercel of any changes made to an Installation or a Resource. Vercel is expected to use \`list-resources\` and...
  - Topics: rest api, marketplace

- [Get Integration Resources](/docs/rest-api/marketplace/get-integration-resources)
  - Type: Reference
  - Summary: GET /v1/installations/{integrationConfigurationId}/resources — Get all resources for a given installation ID.
  - Topics: rest api, marketplace

- [Get Integration Resource](/docs/rest-api/marketplace/get-integration-resource)
  - Type: Reference
  - Summary: GET /v1/installations/{integrationConfigurationId}/resources/{resourceId} — Get a resource by its partner ID.
  - Topics: rest api, marketplace

- [Delete Integration Resource](/docs/rest-api/marketplace/delete-integration-resource)
  - Type: Reference
  - Summary: DELETE /v1/installations/{integrationConfigurationId}/resources/{resourceId} — Delete a resource owned by the selected installation ID.
  - Topics: rest api, marketplace

- [Import Resource](/docs/rest-api/marketplace/import-resource)
  - Type: Reference
  - Summary: PUT /v1/installations/{integrationConfigurationId}/resources/{resourceId} — This endpoint imports \(upserts\) a resource to Vercel's installation. This may be needed if resources can be independently created on...
  - Topics: rest api, marketplace

- [Update Resource](/docs/rest-api/marketplace/update-resource)
  - Type: Reference
  - Summary: PATCH /v1/installations/{integrationConfigurationId}/resources/{resourceId} — This endpoint updates an existing resource in the installation. All parameters are optional, allowing partial updates.
  - Topics: rest api, marketplace

- [Submit Billing Data](/docs/rest-api/marketplace/submit-billing-data)
  - Type: Reference
  - Summary: POST /v1/installations/{integrationConfigurationId}/billing — Sends the billing and usage data. The partner should do this at least once a day and ideally once per...
  - Topics: rest api, marketplace

- [Submit Invoice](/docs/rest-api/marketplace/submit-invoice)
  - Type: Reference
  - Summary: POST /v1/installations/{integrationConfigurationId}/billing/invoices — This endpoint allows the partner to submit an invoice to Vercel. The invoice is created in Vercel's billing system and...
  - Topics: rest api, marketplace

- [Finalize Installation](/docs/rest-api/marketplace/finalize-installation)
  - Type: Reference
  - Summary: POST /v1/installations/{integrationConfigurationId}/billing/finalize — This endpoint allows the partner to mark an installation as finalized. This means you will not send any more invoices...
  - Topics: rest api, marketplace

- [Get Invoice](/docs/rest-api/marketplace/get-invoice)
  - Type: Reference
  - Summary: GET /v1/installations/{integrationConfigurationId}/billing/invoices/{invoiceId} — Get Invoice details and status for a given invoice ID.<br/> <br/> See \[Billing Events with Webhooks documentation\]\(<https://vercel.com/docs/integrations/create-integration/marketplace-api#working-with-billing-events-through-webhooks\>) on how to...
  - Topics: rest api, marketplace

- [Invoice Actions](/docs/rest-api/marketplace/invoice-actions)
  - Type: Reference
  - Summary: POST /v1/installations/{integrationConfigurationId}/billing/invoices/{invoiceId}/actions — This endpoint allows the partner to request a refund for an invoice to Vercel. The invoice is created using the...
  - Topics: rest api, marketplace

- [Submit Prepayment Balances](/docs/rest-api/marketplace/submit-prepayment-balances)
  - Type: Reference
  - Summary: POST /v1/installations/{integrationConfigurationId}/billing/balance — Sends the prepayment balances. The partner should do this at least once a day and ideally once per hour. <br/>...
  - Topics: rest api, marketplace

- [Update Resource Secrets](/docs/rest-api/marketplace/update-resource-secrets)
  - Type: Reference
  - Summary: PUT /v1/installations/{integrationConfigurationId}/resources/{resourceId}/secrets — This endpoint updates the secrets of a resource. If a resource has projects connected, the connected secrets are updated with...
  - Topics: rest api, marketplace

- [Create one or multiple experimentation items](/docs/rest-api/marketplace/create-one-or-multiple-experimentation-items)
  - Type: Reference
  - Summary: POST /v1/installations/{integrationConfigurationId}/resources/{resourceId}/experimentation/items — Create one or multiple experimentation items
  - Topics: rest api, marketplace

- [Patch an existing experimentation item](/docs/rest-api/marketplace/patch-an-existing-experimentation-item)
  - Type: Reference
  - Summary: PATCH /v1/installations/{integrationConfigurationId}/resources/{resourceId}/experimentation/items/{itemId} — Patch an existing experimentation item
  - Topics: rest api, marketplace

- [Delete an existing experimentation item](/docs/rest-api/marketplace/delete-an-existing-experimentation-item)
  - Type: Reference
  - Summary: DELETE /v1/installations/{integrationConfigurationId}/resources/{resourceId}/experimentation/items/{itemId} — Delete an existing experimentation item
  - Topics: rest api, marketplace

- [Get the data of a user-provided Edge Config](/docs/rest-api/marketplace/get-the-data-of-a-user-provided-edge-config)
  - Type: Reference
  - Summary: HEAD /v1/installations/{integrationConfigurationId}/resources/{resourceId}/experimentation/edge-config — When the user enabled Edge Config syncing, then this endpoint can be used by the partner to fetch the contents...
  - Topics: rest api, marketplace

- [Get the data of a user-provided Edge Config](/docs/rest-api/marketplace/get-the-data-of-a-user-provided-edge-config)
  - Type: Reference
  - Summary: GET /v1/installations/{integrationConfigurationId}/resources/{resourceId}/experimentation/edge-config — When the user enabled Edge Config syncing, then this endpoint can be used by the partner to fetch the contents...
  - Topics: rest api, marketplace

- [Push data into a user-provided Edge Config](/docs/rest-api/marketplace/push-data-into-a-user-provided-edge-config)
  - Type: Reference
  - Summary: PUT /v1/installations/{integrationConfigurationId}/resources/{resourceId}/experimentation/edge-config — When the user enabled Edge Config syncing, then this endpoint can be used by the partner to push their configuration...
  - Topics: rest api, marketplace

### microfrontends

- [List microfrontends groups](/docs/rest-api/microfrontends/list-microfrontends-groups)
  - Type: Reference
  - Summary: GET /v1/microfrontends/groups — Get the microfrontends group IDs for a team.
  - Topics: rest api, microfrontends

- [List projects in a microfrontends group](/docs/rest-api/microfrontends/list-projects-in-a-microfrontends-group)
  - Type: Reference
  - Summary: GET /v1/microfrontends/groups/{groupId}/projects — Get the microfrontends for a given group ID.
  - Topics: rest api, microfrontends

- [Get microfrontends config for a deployment](/docs/rest-api/microfrontends/get-microfrontends-config-for-a-deployment)
  - Type: Reference
  - Summary: GET /v1/microfrontends/{deploymentId}/config — Get the microfrontends config for a deployment.
  - Topics: rest api, microfrontends

- [Get microfrontends config for a project](/docs/rest-api/microfrontends/get-microfrontends-config-for-a-project)
  - Type: Reference
  - Summary: GET /v1/microfrontends/projects/{projectIdOrName}/production-mfe-config — Get the microfrontends config for a project by ID or name.
  - Topics: rest api, microfrontends

- [Create a microfrontends group with applications](/docs/rest-api/microfrontends/create-a-microfrontends-group-with-applications)
  - Type: Reference
  - Summary: POST /v1/microfrontends/group — Creates a microfrontends group and attaches multiple projects in a single request.
  - Topics: rest api, microfrontends

### project-routes

- [Get project routing rules](/docs/rest-api/project-routes/get-project-routing-rules)
  - Type: Reference
  - Summary: GET /v1/projects/{projectId}/routes — Get the routing rules for a project. Supports searching by name/ID/pattern, filtering by route type, and diffing staged changes against...
  - Topics: rest api, project-routes

- [Stage routing rules](/docs/rest-api/project-routes/stage-routing-rules)
  - Type: Reference
  - Summary: PUT /v1/projects/{projectId}/routes — Stage routing rules for a project. Set \`overwrite\` to true to replace all existing rules, or omit it to merge...
  - Topics: rest api, project-routes

- [Add a routing rule](/docs/rest-api/project-routes/add-a-routing-rule)
  - Type: Reference
  - Summary: POST /v1/projects/{projectId}/routes — Add a single routing rule to a project at a specified position. Defaults to the end of the list if...
  - Topics: rest api, project-routes

- [Delete routing rules](/docs/rest-api/project-routes/delete-routing-rules)
  - Type: Reference
  - Summary: DELETE /v1/projects/{projectId}/routes — Delete one or more routing rules from a project by ID. Stages a new version with the routes removed.
  - Topics: rest api, project-routes

- [Edit a routing rule](/docs/rest-api/project-routes/edit-a-routing-rule)
  - Type: Reference
  - Summary: PATCH /v1/projects/{projectId}/routes/{routeId} — Replace a routing rule identified by its ID, or restore it from the current production version. Stages a new version...
  - Topics: rest api, project-routes

- [Generate a routing rule from natural language](/docs/rest-api/project-routes/generate-a-routing-rule-from-natural-language)
  - Type: Reference
  - Summary: POST /v1/projects/{projectId}/routes/generate — Generate a routing rule configuration from a natural language description. Returns a suggested route configuration that can be reviewed and...
  - Topics: rest api, project-routes

- [Get routing rule version history](/docs/rest-api/project-routes/get-routing-rule-version-history)
  - Type: Reference
  - Summary: GET /v1/projects/{projectId}/routes/versions — Get the version history for a project's routing rules. Returns the staging version \(if one exists\) followed by production versions,...
  - Topics: rest api, project-routes

- [Promote, restore, or discard a routing rule version](/docs/rest-api/project-routes/promote-restore-or-discard-a-routing-rule-version)
  - Type: Reference
  - Summary: POST /v1/projects/{projectId}/routes/versions — Promote staged routing rules to production, restore a previous production version, or discard staged changes. - \`promote\`: Publishes the staging...
  - Topics: rest api, project-routes

### projectMembers

- [List project members](/docs/rest-api/projectMembers/list-project-members)
  - Type: Reference
  - Summary: GET /v1/projects/{idOrName}/members — Lists all members of a project.
  - Topics: rest api, projectmembers

- [Adds a new member to a project.](/docs/rest-api/projectMembers/adds-a-new-member-to-a-project)
  - Type: Reference
  - Summary: POST /v1/projects/{idOrName}/members — Adds a new member to the project.
  - Topics: rest api, projectmembers

- [Remove a Project Member](/docs/rest-api/projectMembers/remove-a-project-member)
  - Type: Reference
  - Summary: DELETE /v1/projects/{idOrName}/members/{uid} — Remove a member from a specific project
  - Topics: rest api, projectmembers

### projects

- [Retrieve a list of projects](/docs/rest-api/projects/retrieve-a-list-of-projects)
  - Type: Reference
  - Summary: GET /v10/projects — Allows to retrieve the list of projects of the authenticated user or team. The list will be paginated and the...
  - Topics: rest api, projects

- [Create a new project](/docs/rest-api/projects/create-a-new-project)
  - Type: Reference
  - Summary: POST /v11/projects — Allows to create a new project with the provided configuration. It only requires the project \`name\` but more configuration can...
  - Topics: rest api, projects

- [Find a project by id or name](/docs/rest-api/projects/find-a-project-by-id-or-name)
  - Type: Reference
  - Summary: GET /v9/projects/{idOrName} — Get the information for a specific project by passing either the project \`id\` or \`name\` in the URL.
  - Topics: rest api, projects

- [Update an existing project](/docs/rest-api/projects/update-an-existing-project)
  - Type: Reference
  - Summary: PATCH /v9/projects/{idOrName} — Update the fields of a project using either its \`name\` or \`id\`.
  - Topics: rest api, projects

- [Delete a Project](/docs/rest-api/projects/delete-a-project)
  - Type: Reference
  - Summary: DELETE /v9/projects/{idOrName} — Delete a specific project by passing either the project \`id\` or \`name\` in the URL.
  - Topics: rest api, projects

- [Retrieve project domains by project by id or name](/docs/rest-api/projects/retrieve-project-domains-by-project-by-id-or-name)
  - Type: Reference
  - Summary: GET /v9/projects/{idOrName}/domains — Retrieve the domains associated with a given project by passing either the project \`id\` or \`name\` in the URL.
  - Topics: rest api, projects

- [Get a project domain](/docs/rest-api/projects/get-a-project-domain)
  - Type: Reference
  - Summary: GET /v9/projects/{idOrName}/domains/{domain} — Get project domain by project id/name and domain name.
  - Topics: rest api, projects

- [Update a project domain](/docs/rest-api/projects/update-a-project-domain)
  - Type: Reference
  - Summary: PATCH /v9/projects/{idOrName}/domains/{domain} — Update a project domain's configuration, including the name, git branch and redirect of the domain.
  - Topics: rest api, projects

- [Remove a domain from a project](/docs/rest-api/projects/remove-a-domain-from-a-project)
  - Type: Reference
  - Summary: DELETE /v9/projects/{idOrName}/domains/{domain} — Remove a domain from a project by passing the domain name and by specifying the project by either passing the...
  - Topics: rest api, projects

- [Add a domain to a project](/docs/rest-api/projects/add-a-domain-to-a-project)
  - Type: Reference
  - Summary: POST /v10/projects/{idOrName}/domains — Add a domain to the project by passing its domain name and by specifying the project by either passing the...
  - Topics: rest api, projects

- [Move a project domain](/docs/rest-api/projects/move-a-project-domain)
  - Type: Reference
  - Summary: POST /v1/projects/{idOrName}/domains/{domain}/move — Move one project's domain to another project. Also allows the move of all redirects pointed to that domain in the...
  - Topics: rest api, projects

- [Verify project domain](/docs/rest-api/projects/verify-project-domain)
  - Type: Reference
  - Summary: POST /v9/projects/{idOrName}/domains/{domain}/verify — Attempts to verify a project domain with \`verified = false\` by checking the correctness of the project domain's \`verification\` challenge.
  - Topics: rest api, projects

- [Retrieve the environment variables of a project by id or name](/docs/rest-api/projects/retrieve-the-environment-variables-of-a-project-by-id-or-name)
  - Type: Reference
  - Summary: GET /v10/projects/{idOrName}/env — Retrieve the environment variables for a given project by passing either the project \`id\` or \`name\` in the URL.
  - Topics: rest api, projects

- [Create one or more environment variables](/docs/rest-api/projects/create-one-or-more-environment-variables)
  - Type: Reference
  - Summary: POST /v10/projects/{idOrName}/env — Create one or more environment variables for a project by passing its \`key\`, \`value\`, \`type\` and \`target\` and by specifying...
  - Topics: rest api, projects

- [Retrieve the decrypted value of an environment variable of a project by id](/docs/rest-api/projects/retrieve-the-decrypted-value-of-an-environment-variable-of-a-project-by-id)
  - Type: Reference
  - Summary: GET /v1/projects/{idOrName}/env/{id} — Retrieve the environment variable for a given project.
  - Topics: rest api, projects

- [Remove an environment variable](/docs/rest-api/projects/remove-an-environment-variable)
  - Type: Reference
  - Summary: DELETE /v9/projects/{idOrName}/env/{id} — Delete a specific environment variable for a given project by passing the environment variable identifier and either passing the project...
  - Topics: rest api, projects

- [Edit an environment variable](/docs/rest-api/projects/edit-an-environment-variable)
  - Type: Reference
  - Summary: PATCH /v9/projects/{idOrName}/env/{id} — Edit a specific environment variable for a given project by passing the environment variable identifier and either passing the project...
  - Topics: rest api, projects

- [Batch remove environment variables](/docs/rest-api/projects/batch-remove-environment-variables)
  - Type: Reference
  - Summary: DELETE /v1/projects/{idOrName}/env — Delete multiple environment variables for a given project in a single batch operation.
  - Topics: rest api, projects

- [Create project transfer request](/docs/rest-api/projects/create-project-transfer-request)
  - Type: Reference
  - Summary: POST /projects/{idOrName}/transfer-request — Initiates a project transfer request from one team to another. <br/> Returns a \`code\` that remains valid for 24 hours...
  - Topics: rest api, projects

- [Accept project transfer request](/docs/rest-api/projects/accept-project-transfer-request)
  - Type: Reference
  - Summary: PUT /projects/transfer-request/{code} — Accept a project transfer request initated by another team. <br/> The \`code\` is generated using the \`POST /projects/:idOrName/transfer-request\` endpoint.
  - Topics: rest api, projects

- [Update Protection Bypass for Automation](/docs/rest-api/projects/update-protection-bypass-for-automation)
  - Type: Reference
  - Summary: PATCH /v1/projects/{idOrName}/protection-bypass — Update the deployment protection automation bypass for a project
  - Topics: rest api, projects

- [Points all production domains for a project to the given deploy](/docs/rest-api/projects/points-all-production-domains-for-a-project-to-the-given-deploy)
  - Type: Reference
  - Summary: POST /v1/projects/{projectId}/rollback/{deploymentId} — Allows users to rollback to a deployment.
  - Topics: rest api, projects

- [Updates the description for a rollback](/docs/rest-api/projects/updates-the-description-for-a-rollback)
  - Type: Reference
  - Summary: PATCH /v1/projects/{projectId}/rollback/{deploymentId}/update-description — Updates the reason for a rollback, without changing the rollback status itself.
  - Topics: rest api, projects

- [Update the microfrontends settings](/docs/rest-api/projects/update-the-microfrontends-settings)
  - Type: Reference
  - Summary: PATCH /v1/projects/{projectId}/microfrontends — Update the microfrontends settings for a project.
  - Topics: rest api, projects

- [Points all production domains for a project to the given deploy](/docs/rest-api/projects/points-all-production-domains-for-a-project-to-the-given-deploy)
  - Type: Reference
  - Summary: POST /v10/projects/{projectId}/promote/{deploymentId} — Allows users to promote a deployment to production. Note: This does NOT rebuild the deployment. If you need that, then...
  - Topics: rest api, projects

- [Gets a list of aliases with status for the current promote](/docs/rest-api/projects/gets-a-list-of-aliases-with-status-for-the-current-promote)
  - Type: Reference
  - Summary: GET /v1/projects/{projectId}/promote/aliases — Get a list of aliases related to the last promote request with their mapping status
  - Topics: rest api, projects

- [Pause a project](/docs/rest-api/projects/pause-a-project)
  - Type: Reference
  - Summary: POST /v1/projects/{projectId}/pause — Pause a project by passing its project \`id\` in the URL. If the project does not exist given the id...
  - Topics: rest api, projects

- [Unpause a project](/docs/rest-api/projects/unpause-a-project)
  - Type: Reference
  - Summary: POST /v1/projects/{projectId}/unpause — Unpause a project by passing its project \`id\` in the URL. If the project does not exist given the id...
  - Topics: rest api, projects

### rolling-release

- [Get rolling release billing status](/docs/rest-api/rolling-release/get-rolling-release-billing-status)
  - Type: Reference
  - Summary: GET /v1/projects/{idOrName}/rolling-release/billing — Get the Rolling Releases billing status for a project. The team level billing status is used to determine if the...
  - Topics: rest api, rolling-release

- [Get rolling release configuration](/docs/rest-api/rolling-release/get-rolling-release-configuration)
  - Type: Reference
  - Summary: GET /v1/projects/{idOrName}/rolling-release/config — Get the Rolling Releases configuration for a project. The project-level config is simply a template that will be used for...
  - Topics: rest api, rolling-release

- [Delete rolling release configuration](/docs/rest-api/rolling-release/delete-rolling-release-configuration)
  - Type: Reference
  - Summary: DELETE /v1/projects/{idOrName}/rolling-release/config — Disable Rolling Releases for a project means that future deployments will not undergo a rolling release. Changing the config never...
  - Topics: rest api, rolling-release

- [Update the rolling release settings for the project](/docs/rest-api/rolling-release/update-the-rolling-release-settings-for-the-project)
  - Type: Reference
  - Summary: PATCH /v1/projects/{idOrName}/rolling-release/config — Update \(or disable\) Rolling Releases for a project. When disabling with the resolve-on-disable feature flag enabled, any active rolling release...
  - Topics: rest api, rolling-release

- [Get the active rolling release information for a project](/docs/rest-api/rolling-release/get-the-active-rolling-release-information-for-a-project)
  - Type: Reference
  - Summary: GET /v1/projects/{idOrName}/rolling-release — Return the Rolling Release for a project, regardless of whether the rollout is active, aborted, or completed. If the feature...
  - Topics: rest api, rolling-release

- [Update the active rolling release to the next stage for a project](/docs/rest-api/rolling-release/update-the-active-rolling-release-to-the-next-stage-for-a-project)
  - Type: Reference
  - Summary: POST /v1/projects/{idOrName}/rolling-release/approve-stage — Advance a rollout to the next stage. This is only needed when rolling releases is configured to require manual approval.
  - Topics: rest api, rolling-release

- [Complete the rolling release for the project](/docs/rest-api/rolling-release/complete-the-rolling-release-for-the-project)
  - Type: Reference
  - Summary: POST /v1/projects/{idOrName}/rolling-release/complete — Force-complete a Rolling Release. The canary deployment will begin serving 100% of the traffic.
  - Topics: rest api, rolling-release

### sandboxes

- [List sandboxes](/docs/rest-api/sandboxes/list-sandboxes)
  - Type: Reference
  - Summary: GET /v1/sandboxes — Retrieves a paginated list of sandboxes belonging to a specific project. Results can be filtered by creation time using the...
  - Topics: rest api, sandboxes

- [Create a sandbox](/docs/rest-api/sandboxes/create-a-sandbox)
  - Type: Reference
  - Summary: POST /v1/sandboxes — Creates a new sandbox environment for executing code in an isolated virtual machine. A sandbox can be initialized from various...
  - Topics: rest api, sandboxes

- [List snapshots](/docs/rest-api/sandboxes/list-snapshots)
  - Type: Reference
  - Summary: GET /v1/sandboxes/snapshots — Retrieves a paginated list of snapshots for a specific project.
  - Topics: rest api, sandboxes

- [Get a sandbox](/docs/rest-api/sandboxes/get-a-sandbox)
  - Type: Reference
  - Summary: GET /v1/sandboxes/{sandboxId} — Retrieves detailed information about a specific sandbox, including its current status, resource configuration, and exposed routes.
  - Topics: rest api, sandboxes

- [List commands](/docs/rest-api/sandboxes/list-commands)
  - Type: Reference
  - Summary: GET /v1/sandboxes/{sandboxId}/cmd — Retrieves a list of all commands that have been executed in a sandbox, including their current status, exit codes, and...
  - Topics: rest api, sandboxes

- [Execute a command](/docs/rest-api/sandboxes/execute-a-command)
  - Type: Reference
  - Summary: POST /v1/sandboxes/{sandboxId}/cmd — Executes a shell command inside a running sandbox. The command runs asynchronously and returns immediately with a command ID that...
  - Topics: rest api, sandboxes

- [Kill a command](/docs/rest-api/sandboxes/kill-a-command)
  - Type: Reference
  - Summary: POST /v1/sandboxes/{sandboxId}/{cmdId}/kill — Sends a signal to terminate a running command in a sandbox. The signal can be used to gracefully stop \(SIGTERM\)...
  - Topics: rest api, sandboxes

- [Stop a sandbox](/docs/rest-api/sandboxes/stop-a-sandbox)
  - Type: Reference
  - Summary: POST /v1/sandboxes/{sandboxId}/stop — Stops a running sandbox and releases its allocated resources. All running processes within the sandbox will be terminated. This action...
  - Topics: rest api, sandboxes

- [Extend sandbox timeout](/docs/rest-api/sandboxes/extend-sandbox-timeout)
  - Type: Reference
  - Summary: POST /v1/sandboxes/{sandboxId}/extend-timeout — Extends the maximum execution time of a running sandbox. The sandbox must be active and able to accept commands. The...
  - Topics: rest api, sandboxes

- [Update network policy](/docs/rest-api/sandboxes/update-network-policy)
  - Type: Reference
  - Summary: POST /v1/sandboxes/{sandboxId}/network-policy — Replaces the network access policy of a running sandbox. Use this to control which external hosts the sandbox can communicate...
  - Topics: rest api, sandboxes

- [Get a command](/docs/rest-api/sandboxes/get-a-command)
  - Type: Reference
  - Summary: GET /v1/sandboxes/{sandboxId}/cmd/{cmdId} — Retrieves the current status and details of a command executed in a sandbox. Use the \`wait\` parameter to block until...
  - Topics: rest api, sandboxes

- [Stream command logs](/docs/rest-api/sandboxes/stream-command-logs)
  - Type: Reference
  - Summary: GET /v1/sandboxes/{sandboxId}/cmd/{cmdId}/logs — Streams the output of a command in real-time using newline-delimited JSON \(ND-JSON\). Each entry includes the output data and stream...
  - Topics: rest api, sandboxes

- [Read a file](/docs/rest-api/sandboxes/read-a-file)
  - Type: Reference
  - Summary: POST /v1/sandboxes/{sandboxId}/fs/read — Downloads the contents of a file from a sandbox's filesystem. The file content is returned as a binary stream with...
  - Topics: rest api, sandboxes

- [Create a directory](/docs/rest-api/sandboxes/create-a-directory)
  - Type: Reference
  - Summary: POST /v1/sandboxes/{sandboxId}/fs/mkdir — Creates a new directory in a sandbox's filesystem. By default, parent directories are created recursively if they don't exist \(similar...
  - Topics: rest api, sandboxes

- [Write files](/docs/rest-api/sandboxes/write-files)
  - Type: Reference
  - Summary: POST /v1/sandboxes/{sandboxId}/fs/write — Uploads and extracts files to a sandbox's filesystem. Files must be uploaded as a gzipped tarball \(\`.tar.gz\`\) with the \`Content-Type\`...
  - Topics: rest api, sandboxes

- [Get a snapshot](/docs/rest-api/sandboxes/get-a-snapshot)
  - Type: Reference
  - Summary: GET /v1/sandboxes/snapshots/{snapshotId} — Retrieves detailed information about a specific snapshot, including its creation time, size, expiration date, and the source sandbox it was...
  - Topics: rest api, sandboxes

- [Delete a snapshot](/docs/rest-api/sandboxes/delete-a-snapshot)
  - Type: Reference
  - Summary: DELETE /v1/sandboxes/snapshots/{snapshotId} — Permanently deletes a snapshot and frees its associated storage. This action cannot be undone. After deletion, the snapshot can no...
  - Topics: rest api, sandboxes

- [Create a snapshot](/docs/rest-api/sandboxes/create-a-snapshot)
  - Type: Reference
  - Summary: POST /v1/sandboxes/{sandboxId}/snapshot — Creates a point-in-time snapshot of a running sandbox's filesystem. Snapshots can be used to quickly restore a sandbox to a...
  - Topics: rest api, sandboxes

### sandboxes-v2-beta

- [List sandboxes](/docs/rest-api/sandboxes-v2-beta/list-sandboxes)
  - Type: Reference
  - Summary: GET /v2/sandboxes — Retrieves a paginated list of named sandboxes belonging to a specific project. Results can be sorted by creation time or...
  - Topics: rest api, sandboxes-v2-beta

- [Create a named sandbox](/docs/rest-api/sandboxes-v2-beta/create-a-named-sandbox)
  - Type: Reference
  - Summary: POST /v2/sandboxes — Creates a named sandbox environment. Named sandboxes have a unique name within a project and support automatic snapshotting on shutdown.
  - Topics: rest api, sandboxes-v2-beta

- [List snapshots](/docs/rest-api/sandboxes-v2-beta/list-snapshots)
  - Type: Reference
  - Summary: GET /v2/sandboxes/snapshots — Retrieves a paginated list of snapshots for a specific project.
  - Topics: rest api, sandboxes-v2-beta

- [Get a snapshot](/docs/rest-api/sandboxes-v2-beta/get-a-snapshot)
  - Type: Reference
  - Summary: GET /v2/sandboxes/snapshots/{snapshotId} — Retrieves detailed information about a specific snapshot, including its creation time, size, expiration date, and the source session it was...
  - Topics: rest api, sandboxes-v2-beta

- [Delete a snapshot](/docs/rest-api/sandboxes-v2-beta/delete-a-snapshot)
  - Type: Reference
  - Summary: DELETE /v2/sandboxes/snapshots/{snapshotId} — Permanently deletes a snapshot and frees its associated storage. This action cannot be undone. After deletion, the snapshot can no...
  - Topics: rest api, sandboxes-v2-beta

- [List sessions](/docs/rest-api/sandboxes-v2-beta/list-sessions)
  - Type: Reference
  - Summary: GET /v2/sandboxes/sessions — Retrieves a paginated list of sessions belonging to a specific sandbox. Results are sorted by creation time and paginated using...
  - Topics: rest api, sandboxes-v2-beta

- [Get a session](/docs/rest-api/sandboxes-v2-beta/get-a-session)
  - Type: Reference
  - Summary: GET /v2/sandboxes/sessions/{sessionId} — Retrieves detailed information about a specific session, including its current status, resource configuration, and exposed routes.
  - Topics: rest api, sandboxes-v2-beta

- [Get a named sandbox](/docs/rest-api/sandboxes-v2-beta/get-a-named-sandbox)
  - Type: Reference
  - Summary: GET /v2/sandboxes/{name} — Retrieves a named sandbox by name, including its current sandbox and routes. If the sandbox is stopped and resume is...
  - Topics: rest api, sandboxes-v2-beta

- [Update a sandbox](/docs/rest-api/sandboxes-v2-beta/update-a-sandbox)
  - Type: Reference
  - Summary: PATCH /v2/sandboxes/{name} — Updates the configuration of a sandbox. Only the provided fields will be modified; omitted fields remain unchanged.
  - Topics: rest api, sandboxes-v2-beta

- [Delete a sandbox](/docs/rest-api/sandboxes-v2-beta/delete-a-sandbox)
  - Type: Reference
  - Summary: DELETE /v2/sandboxes/{name} — Deletes a sandbox by name. If sandboxes are currently running, they will be stopped first. This operation deletes all sandbox...
  - Topics: rest api, sandboxes-v2-beta

- [List commands](/docs/rest-api/sandboxes-v2-beta/list-commands)
  - Type: Reference
  - Summary: GET /v2/sandboxes/sessions/{sessionId}/cmd — Retrieves a list of all commands that have been executed in a session, including their current status, exit codes, and...
  - Topics: rest api, sandboxes-v2-beta

- [Execute a command](/docs/rest-api/sandboxes-v2-beta/execute-a-command)
  - Type: Reference
  - Summary: POST /v2/sandboxes/sessions/{sessionId}/cmd — Executes a shell command inside a running session. The command runs asynchronously and returns immediately with a command ID that...
  - Topics: rest api, sandboxes-v2-beta

- [Get a command](/docs/rest-api/sandboxes-v2-beta/get-a-command)
  - Type: Reference
  - Summary: GET /v2/sandboxes/sessions/{sessionId}/cmd/{cmdId} — Retrieves the current status and details of a command executed in a session. Use the \`wait\` parameter to block until...
  - Topics: rest api, sandboxes-v2-beta

- [Kill a command](/docs/rest-api/sandboxes-v2-beta/kill-a-command)
  - Type: Reference
  - Summary: POST /v2/sandboxes/sessions/{sessionId}/cmd/{cmdId}/kill — Sends a signal to terminate a running command in a session. The signal can be used to gracefully stop \(SIGTERM\)...
  - Topics: rest api, sandboxes-v2-beta

- [Stream command logs](/docs/rest-api/sandboxes-v2-beta/stream-command-logs)
  - Type: Reference
  - Summary: GET /v2/sandboxes/sessions/{sessionId}/cmd/{cmdId}/logs — Streams the output of a command in real-time using newline-delimited JSON \(ND-JSON\). Each entry includes the output data and stream...
  - Topics: rest api, sandboxes-v2-beta

- [Stop a session](/docs/rest-api/sandboxes-v2-beta/stop-a-session)
  - Type: Reference
  - Summary: POST /v2/sandboxes/sessions/{sessionId}/stop — Stops a running session and releases its allocated resources. All running processes within the session will be terminated. This action...
  - Topics: rest api, sandboxes-v2-beta

- [Extend session timeout](/docs/rest-api/sandboxes-v2-beta/extend-session-timeout)
  - Type: Reference
  - Summary: POST /v2/sandboxes/sessions/{sessionId}/extend-timeout — Extends the maximum execution time of a running session. The session must be active and able to accept commands. The...
  - Topics: rest api, sandboxes-v2-beta

- [Update network policy](/docs/rest-api/sandboxes-v2-beta/update-network-policy)
  - Type: Reference
  - Summary: POST /v2/sandboxes/sessions/{sessionId}/network-policy — Replaces the network access policy of a running session. Use this to control which external hosts the session can communicate...
  - Topics: rest api, sandboxes-v2-beta

- [Read a file](/docs/rest-api/sandboxes-v2-beta/read-a-file)
  - Type: Reference
  - Summary: POST /v2/sandboxes/sessions/{sessionId}/fs/read — Downloads the contents of a file from a session's filesystem. The file content is returned as a binary stream with...
  - Topics: rest api, sandboxes-v2-beta

- [Create a directory](/docs/rest-api/sandboxes-v2-beta/create-a-directory)
  - Type: Reference
  - Summary: POST /v2/sandboxes/sessions/{sessionId}/fs/mkdir — Creates a new directory in a session's filesystem. By default, parent directories are created recursively if they don't exist \(similar...
  - Topics: rest api, sandboxes-v2-beta

- [Write files](/docs/rest-api/sandboxes-v2-beta/write-files)
  - Type: Reference
  - Summary: POST /v2/sandboxes/sessions/{sessionId}/fs/write — Uploads and extracts files to a session's filesystem. Files must be uploaded as a gzipped tarball \(\`.tar.gz\`\) with the \`Content-Type\`...
  - Topics: rest api, sandboxes-v2-beta

- [Create a snapshot](/docs/rest-api/sandboxes-v2-beta/create-a-snapshot)
  - Type: Reference
  - Summary: POST /v2/sandboxes/sessions/{sessionId}/snapshot — Creates a point-in-time snapshot of a running session's filesystem. Snapshots can be used to quickly restore a session to a...
  - Topics: rest api, sandboxes-v2-beta

### security

- [Update Attack Challenge mode](/docs/rest-api/security/update-attack-challenge-mode)
  - Type: Reference
  - Summary: POST /v1/security/attack-mode — Update the setting for determining if the project has Attack Challenge mode enabled.
  - Topics: rest api, security

- [Put Firewall Configuration](/docs/rest-api/security/put-firewall-configuration)
  - Type: Reference
  - Summary: PUT /v1/security/firewall/config — Set the firewall configuration to provided rules and settings. Creates or overwrite the existing firewall configuration.
  - Topics: rest api, security

- [Update Firewall Configuration](/docs/rest-api/security/update-firewall-configuration)
  - Type: Reference
  - Summary: PATCH /v1/security/firewall/config — Process updates to modify the existing firewall config for a project
  - Topics: rest api, security

- [Read Firewall Configuration](/docs/rest-api/security/read-firewall-configuration)
  - Type: Reference
  - Summary: GET /v1/security/firewall/config/{configVersion} — Retrieve the specified firewall configuration for a project. The deployed configVersion will be \`active\`
  - Topics: rest api, security

- [Read active attack data](/docs/rest-api/security/read-active-attack-data)
  - Type: Reference
  - Summary: GET /v1/security/firewall/attack-status — Retrieve active attack data within the last N days \(default: 1 day\)
  - Topics: rest api, security

- [Read System Bypass](/docs/rest-api/security/read-system-bypass)
  - Type: Reference
  - Summary: GET /v1/security/firewall/bypass — Retrieve the system bypass rules configured for the specified project
  - Topics: rest api, security

- [Create System Bypass Rule](/docs/rest-api/security/create-system-bypass-rule)
  - Type: Reference
  - Summary: POST /v1/security/firewall/bypass — Create new system bypass rules
  - Topics: rest api, security

- [Remove System Bypass Rule](/docs/rest-api/security/remove-system-bypass-rule)
  - Type: Reference
  - Summary: DELETE /v1/security/firewall/bypass — Remove system bypass rules
  - Topics: rest api, security

- [Read Firewall Actions by Project](/docs/rest-api/security/read-firewall-actions-by-project)
  - Type: Reference
  - Summary: GET /v1/security/firewall/events — Retrieve firewall actions for a project
  - Topics: rest api, security

### teams

- [List team members](/docs/rest-api/teams/list-team-members)
  - Type: Reference
  - Summary: GET /v3/teams/{teamId}/members — Get a paginated list of team members for the provided team.
  - Topics: rest api, teams

- [Invite a user](/docs/rest-api/teams/invite-a-user)
  - Type: Reference
  - Summary: POST /v2/teams/{teamId}/members — Invite a user to join the team specified in the URL. The authenticated user needs to be an \`OWNER\` in...
  - Topics: rest api, teams

- [Request access to a team](/docs/rest-api/teams/request-access-to-a-team)
  - Type: Reference
  - Summary: POST /v1/teams/{teamId}/request — Request access to a team as a member. An owner has to approve the request. Only 10 users can request...
  - Topics: rest api, teams

- [Get access request status](/docs/rest-api/teams/get-access-request-status)
  - Type: Reference
  - Summary: GET /v1/teams/{teamId}/request/{userId} — Check the status of a join request. It'll respond with a 404 if the request has been declined. If no...
  - Topics: rest api, teams

- [Join a team](/docs/rest-api/teams/join-a-team)
  - Type: Reference
  - Summary: POST /v1/teams/{teamId}/members/teams/join — Join a team with a provided invite code or team ID.
  - Topics: rest api, teams

- [Update a Team Member](/docs/rest-api/teams/update-a-team-member)
  - Type: Reference
  - Summary: PATCH /v1/teams/{teamId}/members/{uid} — Update the membership of a Team Member on the Team specified by \`teamId\`, such as changing the _role_ of the...
  - Topics: rest api, teams

- [Remove a Team Member](/docs/rest-api/teams/remove-a-team-member)
  - Type: Reference
  - Summary: DELETE /v1/teams/{teamId}/members/{uid} — Remove a Team Member from the Team, or dismiss a user that requested access, or leave a team.
  - Topics: rest api, teams

- [Get a Team](/docs/rest-api/teams/get-a-team)
  - Type: Reference
  - Summary: GET /v2/teams/{teamId} — Get information for the Team specified by the \`teamId\` parameter.
  - Topics: rest api, teams

- [Update a Team](/docs/rest-api/teams/update-a-team)
  - Type: Reference
  - Summary: PATCH /v2/teams/{teamId} — Update the information of a Team specified by the \`teamId\` parameter. The request body should contain the information that will...
  - Topics: rest api, teams

- [List all teams](/docs/rest-api/teams/list-all-teams)
  - Type: Reference
  - Summary: GET /v2/teams — Get a paginated list of all the Teams the authenticated User is a member of.
  - Topics: rest api, teams

- [Create a Team](/docs/rest-api/teams/create-a-team)
  - Type: Reference
  - Summary: POST /v1/teams — Create a new Team under your account. You need to send a POST request with the desired Team slug, and...
  - Topics: rest api, teams

- [Update Team Directory Sync Role Mappings](/docs/rest-api/teams/update-team-directory-sync-role-mappings)
  - Type: Reference
  - Summary: POST /v1/teams/{teamId}/dsync-roles — Update the Directory Sync role mappings for a Team. This endpoint allows updating the mapping between directory groups and team...
  - Topics: rest api, teams

- [Delete a Team](/docs/rest-api/teams/delete-a-team)
  - Type: Reference
  - Summary: DELETE /v1/teams/{teamId} — Delete a team under your account. You need to send a \`DELETE\` request with the desired team \`id\`. An optional...
  - Topics: rest api, teams

- [Delete a Team invite code](/docs/rest-api/teams/delete-a-team-invite-code)
  - Type: Reference
  - Summary: DELETE /v1/teams/{teamId}/invites/{inviteId} — Delete an active Team invite code.
  - Topics: rest api, teams

- [Update a microfrontends group](/docs/rest-api/teams/update-a-microfrontends-group)
  - Type: Reference
  - Summary: PATCH /v1/teams/{teamId}/microfrontends/{groupId} — Updates the name \(and slug\) of a microfrontends group.
  - Topics: rest api, teams

- [Delete a microfrontends group](/docs/rest-api/teams/delete-a-microfrontends-group)
  - Type: Reference
  - Summary: DELETE /v1/teams/{teamId}/microfrontends/{groupId} — Deletes a microfrontends group from the team associated with the group ID.
  - Topics: rest api, teams

### user

- [List User Events](/docs/rest-api/user/list-user-events)
  - Type: Reference
  - Summary: GET /v3/events — Retrieves a list of "events" generated by the User on Vercel. Events are generated when the User performs a particular...
  - Topics: rest api, user

- [List Event Types](/docs/rest-api/user/list-event-types)
  - Type: Reference
  - Summary: GET /v1/events/types — Returns the list of user-facing event types with descriptions.
  - Topics: rest api, user

- [Get the User](/docs/rest-api/user/get-the-user)
  - Type: Reference
  - Summary: GET /v2/user — Retrieves information related to the currently authenticated User.
  - Topics: rest api, user

- [Delete User Account](/docs/rest-api/user/delete-user-account)
  - Type: Reference
  - Summary: DELETE /v1/user — Initiates the deletion process for the currently authenticated User, by sending a deletion confirmation email. The email contains a link...
  - Topics: rest api, user

### webhooks

- [Creates a webhook](/docs/rest-api/webhooks/creates-a-webhook)
  - Type: Reference
  - Summary: POST /v1/webhooks — Creates a webhook
  - Topics: rest api, webhooks

- [Get a list of webhooks](/docs/rest-api/webhooks/get-a-list-of-webhooks)
  - Type: Reference
  - Summary: GET /v1/webhooks — Get a list of webhooks
  - Topics: rest api, webhooks

- [Get a webhook](/docs/rest-api/webhooks/get-a-webhook)
  - Type: Reference
  - Summary: GET /v1/webhooks/{id} — Get a webhook
  - Topics: rest api, webhooks

- [Deletes a webhook](/docs/rest-api/webhooks/deletes-a-webhook)
  - Type: Reference
  - Summary: DELETE /v1/webhooks/{id} — Deletes a webhook
  - Topics: rest api, webhooks
