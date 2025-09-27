# KAAN MERT KOC

Istanbul, Turkey | +90 531 712 3188 | kaanmertkocbus@gmail.com
LinkedIn: https://www.linkedin.com/in/kaan-mert-koc-2a57b5202/
GitHub: https://github.com/kaanmertkoc

## Summary

Senior full-stack engineer delivering SEO-first server-side rendered (SSR) web
apps, high-traffic APIs, and mobile apps with TypeScript, Next.js, React
Native/Expo, Strapi, Firebase, and Go. Delivered 1.4M+ visits, 3.0M pageviews,
2.0M requests/month APIs (95th percentile latency 96 ms), and 280K+ TRY GMV on
lean, reliable infrastructure. Core Web Vitals (CWV) green on core pages;
INP (Interaction to Next Paint) under 200 ms on key templates.

## Skills

- Frontend: React, Next.js (App Router, SSR, ISR), TypeScript,
  TanStack Query (React Query), Redux, Zustand, CSS-in-JS,
  accessibility (a11y), Core Web Vitals (CWV)
- Mobile: React Native, Expo (EAS), in-app purchases, deep links, push
  notifications via Firebase Cloud Messaging (FCM), TestFlight, Play Console
- Backend: Node.js, Bun, Go (chi), REST APIs, webhooks, Firebase Cloud
  Functions, Firestore (NoSQL), PostgreSQL, SQLite, Drizzle ORM
- Infra/DevOps: Docker, Docker Compose, Vercel, VPS, Nginx, Coolify,
  GitHub Actions, continuous integration and continuous delivery (CI/CD),
  CDN and caching (SSR, ISR, CDN), logging and monitoring (Sentry, Dozzle),
  Google Cloud Platform (GCP) — Cloud Monitoring and Cloud Logging (Logs Explorer) for Firestore and Cloud Functions
- CMS/Search: Strapi (self-hosted), Meilisearch
- Auth/Security: NextAuth, OAuth 2.0, JWT (JSON Web Tokens),
  SSO (single sign-on), RBAC (role-based access control), rate limiting,
  feature flags
- Commerce/Payments: Shopify, Stripe, iyzico
- Media/Storage/CDN: Bunny CDN, Cloudflare R2
- Analytics/SEO: Google Analytics, Google Search Console, Plausible, JSON-LD,
  technical SEO
- Observability and Testing: Sentry, Dozzle, Firebase Crashlytics,
  Google Cloud Monitoring and Cloud Logging (Logs Explorer), Jest, Vitest,
  Playwright, Detox, end-to-end (E2E) testing

## Professional Experience

### Cosmopolitan Turkey — CTO (Hands-on Senior Full-Stack & DevOps) | Istanbul | Aug 2024 – Present

- Growth on a new domain (100% organic): 1.4M visits and 3.0M pageviews in
  under 12 months; 2.14 views per visit; 67% bounce rate; 1m43s average
  duration; approximately 907K from Google; zero marketing budget.
- SEO: JSON-LD sitewide and AI metadata (gpt-4o-mini via Strapi). Google
  Search Console: 1.01M clicks and 15.9M impressions (12 months).
- Architecture: Next.js SSR on Vercel (production) and Coolify for preview;
  custom Strapi CMS; block-based page builder and per-page “Fancy Page”
  controls.
- Performance and reliability: caching and on-change revalidation; SSR time to
  first byte (TTFB) median 100 ms and 95th percentile 500 ms; zero downtime.
  Core Web Vitals: LCP (Largest Contentful Paint) under 2.5 s, CLS
  (Cumulative Layout Shift) under 0.1, INP under 200 ms on key templates;
  accessibility checks (axe) in CI.
- Cosmo Quiz API: 1.3M solves in 5 months; 10M+ events, 1.3M sessions; 2.0M
  requests per month. Stack: Bun, Hono, TypeScript, Drizzle, SQLite, Nginx
  (Docker). Latency median 48 ms and p95 96 ms; error rate under 0.02%;
  availability 99.9%.
- Personalization and analytics: Readlists; Node/Sharp cover-image
  microservice to Bunny CDN; Go log server (chi) and Go analytics (SQLite);
  nightly Cloudflare R2 backups via custom Go backup-service.
- Search: Meilisearch with AI semantic “Similar Documents” (20 per page).
- Newsletters: 7 lists via Benchmark Email API; 10K subscribers.
- Subscribe: SSR with server-side isSubscribed gating; iyzico subscription
  router (20+ endpoints); magazine reader pipeline (PDF split, sign, upload to
  Bunny CDN); single-issue purchase via Shopify. Metrics: 13K visits, 32K
  pageviews, 170 subscriptions (106 active).
- Shop: Shopify with Next.js SSR; webhook-driven cache revalidation;
  variant-per-cover URLs; 23K visits, 51K pageviews, 1,305 orders, 280K TRY
  revenue in under 5 months. Orders visible in user profiles.
- Auth/Admin: cross-domain SSO with NextAuth; Admin portal (React, Vite,
  TanStack, shadcn) with RBAC (JWT-embedded routes) and analytics dashboards.
- CI/CD and quality: GitHub Actions pipelines; Playwright E2E on
  checkout/auth; logging and monitoring with Sentry, Bezsel, and Dozzle.

### Aposto! — Mobile to Web to Full-Stack Engineer | Istanbul | Sep 2021 – Apr 2025

- Shipped Aposto! mobile app (50+ screens): offline podcast, read list,
  Turkish/English, dark/light modes; releases via TestFlight and Play Console.
- 100K+ downloads; 3.05M App Store impressions; featured by Apple (2022);
  Top 3 in Turkey (Media).
- Co-built aposto.com with Next.js 12 and Redux: inbox, reading, authors,
  authentication, follow/unfollow, share.
- Launched About and Newsletters subdomains (Next.js 13 App Router);
  Lighthouse 98.
- Premium subscriptions (Stripe): paywall; card add/switch/delete; subscription
  management; shared TypeScript KV paywall library.
- Services: Categories and Premium Newsletters (Firestore and Next.js API with
  in-memory caching).
- Premium Stories: Go (chi) and SQLite, Cloudflare-cached via Next.js API;
  about 100K requests per month.
- Modernized Admin: migrated from CRA/React 16/CRACO/Yarn to Bun, Vite, and
  React Router; built TTS editor UI (ElevenLabs).
- Quality and observability: Firebase Crashlytics monitoring; Detox E2E on
  paywall flows.
- Impact: 100K+ monthly visitors, 1.5M+ total users, over 100K USD revenue;
  team ~10 across frontend, backend, DevOps, PM, and CTO.

### Sober Digital — Lead Full-Stack Engineer | Istanbul | Mar 2024 – Feb 2025

- Next.js 14 SSR e-commerce on Firebase Cloud Functions and Firestore (20+
  endpoints) with iyzico; custom admin for merch, categories, coupons with
  limits.
- Festival-only inventory via QR-coded SKUs with isolated stock pools for
  physical events.
- Strapi CMS (self-hosted) modeling issue → sections → content; unified for
  web and mobile.
- Expo app: Feed; Events with iyzico ticketing, QR check-in, and attendance;
  Explore (mini-games, Radio/Podcasts via Spotify); Shop
  (All, Magazine, Accessories, Clothing); Perks.
- Auth and growth: NextAuth on web; soft login/registration walls for premium
  content on web and app.
- Media and performance: Bunny CDN; video carousel landing; GIF product
  galleries.
- Ops: Vercel (web), VPS-hosted Strapi, Firebase backend; infrastructure about
  50 USD/month at peak (initial about 30 USD).
- Observability: Configured GCP Cloud Monitoring dashboards and alerting for
  Firestore and Firebase Cloud Functions; used Logs Explorer to investigate
  errors/latency across endpoints.
- Outcome: 50K+ users; 600K+ TRY GMV; SEO via “Sober People” catalog
  (50+ profiles).

### HyperCut — Co-Founder and Tech Lead | Istanbul | Apr 2023 – Dec 2024

- React Native reels editor: hypes, search/filter, authentication, paywall,
  in-app purchases, premium subscriptions with Firebase Cloud Functions,
  storage, and auth.
- Content pipeline: upload, storage optimization, processing.
- Landing site and admin dashboard with Next.js 14. BTM-backed (Istanbul
  Chamber of Commerce startup hub).

### ScheduleIt — Co-Founder and CTO | Oct 2023 – Dec 2024

- Automation web app for recurring tasks; 2nd at Solana Ideathon, 3rd at
  Solana Presentation; invited to Solana HyperDrive Global Hackathon.
- Next.js 14 frontend and Firebase Cloud Functions backend; scheduled jobs
  integrating WhatsApp Business API, Firebase Mail Sender, and CoinMarketCap
  API.

### UrWord — CTO | New York | Aug 2022 – Dec 2023

- Sole developer for NYC integrity/trust platform: backend, database, mobile
  app, and admin site.
- 180+ TestFlight builds; Firestore with 10K+ documents and security rules;
  Firebase Cloud Functions with 12 REST endpoints across ~150 services (pacts,
  connections, user data sharing, notifications, moderation, analytics).
- Expo/React Native/TypeScript/Redux app (50+ screens, 1,000+ components) and
  admin web dashboard.

## Additional Experience

- Cheer Media — IT Consultant (part-time) | Jan 2020 – Jan 2022: Benchmark Email
  setup; 6 newsletter signup sites (Next.js); Lighthouse 90+.
- KmkocSoftware — Founder and CTO | Jan 2023 – Jan 2024: Client dashboard for
  Rational devices; custom API with Firebase Cloud Functions; React dashboard.
- Teamsfam — Backend Lead | Jan 2023 – Mar 2023: Led 2-person backend;
  Express.js with TypeScript on Firebase Cloud Functions.
- Kopitek — Frontend Developer | 2020 – 2021: Vue.js admin dashboard; SwiftUI
  iOS app and Java Android app.

## Awards and Hackathons

- Solana Ideathon — 2nd place; Solana Presentation — 3rd place; invited to
  Solana HyperDrive Global Hackathon (ScheduleIt).

## Open Source and GitHub Activity

- 4-year active GitHub contributor. Yearly totals: 1,561 (2022), 4,143 (2023),
  2,509 (2024), 2,885 YTD (2025).
- Notable repo: backup-service (Go backup service with Cloudflare R2) —
  https://github.com/kaanmertkoc/backup-service

## Education

- MEF University, Istanbul, Turkey — B.Sc. Computer Engineering, 2023.
  IAESTE member; finalist in inter-university algorithm competition in Turkey.
- University for Information Science and Technology "St. Paul the Apostle" — 2021. Built iOS app “Code Tracker” with GitHub authentication; received
  full grade.