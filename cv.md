# KAAN MERT KOC

Senior Full-Stack Engineer

Istanbul, Turkey → New York, NY | +1 929 625 1934 | [kaanmertkocbus@gmail.com](mailto:kaanmertkocbus@gmail.com)  
[LinkedIn](https://www.linkedin.com/in/kaan-mert-koc) | [GitHub](https://github.com/kaanmertkoc) | [kaanmertkoc.com](https://kaanmertkoc.com)

## Summary

Senior full-stack engineer building AI agents and production software: multi-agent browser testing, LLM-as-judge evaluations, and proof-gated development workflows across TypeScript, Next.js, React Native, and Go. Delivered 1.4M+ visits, 3.0M pageviews, 2.0M requests/month (p95 latency 96ms), and 280K+ TRY GMV. Core Web Vitals green; INP under 200ms on key templates.

## Skills

- AI/Agentic: Claude Code, OpenCode, Codex, Pi, agent customization (skills, subagents, hooks, MCP), multi-agent orchestration, LLM-as-judge evaluations, Vercel AI SDK (structured output), Vercel AI Gateway, Gemini, OpenAI, GitHub Copilot coding agent, MCP integrations (Sentry, Jira, Figma, Playwright), Playwright browser agents, mutation testing
- Frontend: React, Next.js (App Router, SSR, SSG, ISR), TypeScript, TanStack Query, Redux, Zustand, CSS-in-JS, a11y, CWV
- Mobile: React Native, Expo EAS, in-app purchases, deep links, push notifications (FCM), TestFlight, Play Console
- Backend: Node.js, Bun, Go (chi), Hono, tRPC, RESTful APIs, microservices, webhooks, Inngest, Ably, Firebase Functions, Firestore, PostgreSQL, SQLite, Prisma, Drizzle ORM
- Infrastructure: Docker, Docker Compose, Vercel, VPS, Nginx, Coolify, GitHub Actions, CI/CD, CDN/caching, GCP
- CMS/Search: Strapi (self-hosted), Meilisearch
- Auth/Security: Clerk, NextAuth, OAuth 2.0, JWT, SSO, RBAC, rate limiting, feature flags
- Commerce/Payments: Shopify, Stripe, iyzico
- Media/Storage/CDN: Bunny CDN, Cloudflare R2
- Analytics/SEO: Google Analytics, Google Search Console, Plausible, JSON-LD, technical SEO
- Observability/Testing: Sentry, Dozzle, Firebase Crashlytics, Google Cloud Monitoring/Logging, Playwright, Jest, Vitest

## Professional Experience

### Ablefy.io GmbH - Full Stack Developer | Berlin, Germany | Dec 2025 - Present

**AI engineering**

- Agentic QA swarm: built 11 LLM-driven browser agents acting as hosts, members, and guests in real webinars on per-PR previews; Gemini evaluates interactions using vision and structured output. Runs publish video, screenshots, per-agent feedback, and token costs; findings led to product fixes
- Live-event agents: built a seller-journey suite covering an owner, 3 staff roles, and 6 guest personas registering, buying, or dropping off; step-by-step evaluation and an LLM customer judge assess each persona’s experience
- Proof-gated review: co-built the team’s Claude Code harness (triage → spec → TDD → verify → multi-agent PR review); added prover agents that reproduce P0/P1 findings in isolated worktrees and databases, plus mutation checks before acceptance criteria can pass
- Visual PR evidence: built agent-captured before/after screenshots at 3 viewports, provenance manifests, automatic embedding in PR descriptions, and a reviewer skill that audits the evidence
- AI-assisted operations: routed Sentry issues to GitHub Copilot’s coding agent; built a Claude skill to take over stalled Copilot PRs with Sentry root-cause analysis, test-first fixes, and updated PR descriptions
- CI and previews: built per-PR preview environments triggered by comments and a regression-risk gate that automatically runs E2E tests on risky changes

**Product engineering**

- Core engineering: 550+ merged PRs on a multi-tenant community SaaS (Next.js App Router, React 19, tRPC, Prisma/PostgreSQL, Clerk, Inngest); shipped rooms, posts, membership lifecycle, permissions, moderation, and en/de localization through Open Beta
- Live commerce and messaging: webinars and live shopping with realtime product overlays, a drag-and-drop layer editor, and in-stream checkout; direct messaging and moderated live chat with scoped Ably tokens and persisted history
- AI authoring: selection-based edits, AI review, prompt assist, and AI-seeded community onboarding
- Identity and engagement: cross-platform Clerk SSO, user sync and external-ID backfill; localized transactional emails, in-app deep links, and a weekly digest engine with ranking, branding, and opt-out preferences
- Hardening and platform: closed cross-tenant authorization gaps and cleared 74/76 Dependabot alerts (all 32 highs); SEO foundations, Dockerized local development, and Next.js 16, React 19, and rich-text editor upgrades

### Cosmopolitan Turkey - Chief Technology Officer (Hands-on Senior Full-Stack & DevOps) | Aug 2024 - Aug 2025

- Sole engineer: 1.4M visits, 3.0M pageviews in 12 months (zero marketing budget)
- SEO: JSON-LD, AI metadata (gpt-4o-mini/Strapi), 1.01M clicks, 15.9M impressions
- Architecture: Next.js SSR (Vercel/Coolify), custom Strapi CMS, block-based page builder
- Performance: Caching/revalidation, SSR TTFB 100ms/p95 500ms, zero downtime, CWV green
- Cosmo Quiz API: 1.3M solves/5 months, 10M+ events, 2.0M requests/month, Bun/Hono/TypeScript/Drizzle/SQLite, 48ms/p95 96ms, 99.9% uptime
- Search: Meilisearch AI semantic "Similar Documents" (20 per page)
- Subscribe: SSR gating, iyzico router (20+ endpoints), magazine pipeline, Shopify, 170 subscriptions
- Shop: Shopify SSR, webhook revalidation, 1,305 orders, 280K TRY revenue
- Auth/Admin: cross-domain SSO (NextAuth), React/Vite/TanStack admin with RBAC/analytics
- CI/CD: GitHub Actions, E2E tests, observability/alerting

### Aposto!, Mobile, Web, Full-Stack Engineer | Istanbul, Turkey | Sep 2021 - Apr 2025

- Aposto! mobile app (50+ screens): offline podcast, read list, Turkish/English, dark/light modes, TestFlight/Play Console
- 100K+ downloads, 3.05M App Store impressions, Apple featured (2022), Top 3 Turkey (Media)
- aposto.com (Next.js 12/Redux): inbox, reading, authors, authentication, follow/unfollow, share
- About/Newsletters subdomains (Next.js 13 App Router), Lighthouse 98
- Premium subscriptions (Stripe): paywall, card management, shared TypeScript KV library
- Premium Stories: Go (chi)/SQLite, Cloudflare-cached, 100K requests/month
- Admin modernization: CRA/React 16 → Bun/Vite/React Router, TTS editor (ElevenLabs)
- Quality: crash monitoring, E2E paywall tests
- Impact: 100K+ monthly visitors, 1.5M+ users, 100K+ USD revenue, ~10 team

### Sober Digital - Lead Full-Stack Engineer | Istanbul, Turkey | Mar 2024 - Feb 2025

- Shop, editorial site and festival app for a biannual print magazine; 50K+ users, 600K+ TRY GMV
- Next.js 14 SSR e-commerce (Firebase Functions/Firestore, 20+ endpoints, iyzico), custom admin (merch/categories/coupons)
- Festival inventory: QR-coded SKUs, isolated stock pools
- Strapi CMS (self-hosted): issue > sections > content modeling, unified web/mobile
- Expo app: Feed, Events (iyzico ticketing, QR check-in), Explore (mini-games, Spotify), Shop, Perks
- Auth/Growth: NextAuth (web), soft login/registration walls
- Media/Performance: Bunny CDN, video carousel, GIF galleries
- Ops: Vercel, VPS Strapi, Firebase backend, ~50 USD/month
- Observability: Firestore/Functions dashboards/alerting
- "Sober People" SEO catalog (50+ profiles)

### UrWord - CTO | New York, USA | Aug 2022 - Dec 2023

- Sole developer (NYC integrity/trust platform): backend, database, mobile app, admin site
- 180+ TestFlight builds; Firestore (10K+ documents, security rules)
- Firebase Functions: 12 RESTful endpoints, 150 services (pacts, connections, data sharing, notifications, moderation, analytics)
- Expo/React Native/TypeScript/Redux app (50+ screens, 1,000+ components), admin dashboard

## Awards and Hackathons

- Solana Ideathon 2nd place; Solana Presentation 3rd place; Solana HyperDrive Global Hackathon invitee

## Public Speaking

- Interview on "Business Time" about software development, AI, and tech; aired on TV8 International, YouTube, and Instagram

## Open Source and GitHub Activity

- 4-year GitHub contributor: 11K+ contributions (2022-2025)
- **[iyzico-subscription-ts](https://github.com/kaanmertkoc/iyzico-subscription-ts)**: Modern TypeScript SDK for Iyzico Subscription API, cross-platform compatible (Node.js, Bun, Deno, browsers, serverless), zero dependencies, full TypeScript support

## Education

- Touro University, New York - M.S. Artificial Intelligence, started 2026
- MEF University, Istanbul - B.Sc. Computer Engineering, 2023. IAESTE member; algorithm competition finalist
- UIST "St. Paul the Apostle", Ohrid - 2021. iOS "Code Tracker" app (GitHub auth, full grade)
