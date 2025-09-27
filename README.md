# KAAN MERT KOC

Istanbul, Turkey | +90 531 712 3188 | kaanmertkocbus@gmail.com
LinkedIn: https://www.linkedin.com/in/kaan-mert-koc-2a57b5202/
GitHub: https://github.com/kaanmertkoc

## Summary

Senior full-stack engineer shipping SEO-first SSR (server-side rendering) web
apps, high-traffic APIs, and mobile apps with TypeScript, Next.js, React
Native/Expo, Strapi, Firebase, and Go. Delivered 1.4M+ visits, 3.0M pageviews,
2.0M req/mo APIs (p95 96 ms), and 280K+ TRY GMV on lean, reliable infra; Core
Web Vitals (CWV) green on core pages. INP (Interaction to Next Paint) < 200 ms on key templates.

## Skills

- Frontend: React, Next.js/NextJS (App Router/SSR/ISR), TypeScript,
  React Query/TanStack, Redux/Zustand, CSS-in-JS, accessibility (a11y),
  Core Web Vitals
- Mobile: React Native, Expo (EAS), In-App Purchases, deep links, push (FCM),
  TestFlight, Play Console
- Backend: Node.js, Bun, Go (chi), REST/RESTful APIs, Webhooks,
  Firebase Cloud Functions, Firestore (NoSQL), PostgreSQL, SQLite, Drizzle ORM
- Infra/DevOps: Docker, Docker Compose, Vercel, VPS, Nginx, Coolify,
  GitHub Actions, CI/CD, CDN and caching (SSR/ISR/CDN), logging and monitoring
- CMS/Search: Strapi (self-hosted), Meilisearch
- Auth/Security: NextAuth, OAuth 2.0, JWT, SSO, RBAC, rate limiting,
  feature flags
- Commerce/Payments: Shopify, Stripe, iyzico
- Media/Storage/CDN: Bunny CDN, Cloudflare R2
- Analytics/SEO: Google Analytics, Google Search Console, Plausible, JSON-LD,
  Technical SEO
- Observability and Testing: Sentry, Firebase Crashlytics, Jest, Vitest,
  Playwright, Detox, E2E testing

## Experience

### Cosmopolitan Turkey - CTO, Full-Stack, DevOps | Aug 2024 - Present

- Growth on a new domain (100% organic): 1.4M visits, 3.0M pageviews in
  <12 months; 2.14 views/visit; 67% bounce; 1m43s avg duration; ~907K from
  Google; zero marketing budget.
- SEO: JSON-LD sitewide and AI metadata (gpt-4o-mini via Strapi). Google
  Search Console: 1.01M clicks / 15.9M impressions (12 months).
- Architecture: Next.js SSR on Vercel (prod) and Coolify preview; custom
  Strapi CMS; block-based page builder and per-page "Fancy Page" controls.
- Performance and reliability: cache + on-change revalidation; SSR TTFB
  p50 100 ms / p95 500 ms; zero downtime. CWV: LCP <2.5s, CLS <0.1,
  INP <200 ms on key templates; a11y checks (axe) in CI.
- Cosmo Quiz API: 1.3M solves in 5 months; 10M+ events, 1.3M sessions;
  2.0M req/mo. Stack: Bun, Hono, TypeScript, Drizzle, SQLite, Nginx (Docker).
  Latency p50 48 ms / p95 96 ms; errors <0.02%; availability 99.9%.
- Personalization and analytics: Readlists; Node/Sharp cover-image microservice
  to Bunny CDN; Go log server (chi) and Go analytics (SQLite); nightly
  Cloudflare R2 backups via custom Go backup-service.
- Search: Meilisearch + AI semantic "Similar Documents" (20 per page).
- Newsletters: 7 lists via Benchmark Email API; 10K subscribers.
- Subscribe: SSR + server-side isSubscribed gating; iyzico subscription router
  (20+ endpoints); magazine reader pipeline (PDF split/sign/upload to Bunny
  CDN); single-issue purchase via Shopify. Metrics: 13K visits, 32K pageviews,
  170 subs (106 active).
- Shop: Shopify + Next.js SSR; webhook-driven cache revalidation;
  variant-per-cover URLs; 23K visits, 51K pageviews, 1,305 orders,
  280K TRY revenue in <5 months. Orders visible in user profiles.
- Auth/Admin: cross-domain SSO with NextAuth; Admin portal (React, Vite,
  TanStack, shadcn) with RBAC (JWT-embedded routes), analytics dashboards.
- CI/CD and quality: GitHub Actions pipelines; Playwright E2E on checkout/auth;
  Sentry monitoring.

### Aposto! - Mobile -> Web -> Full-Stack Engineer | Istanbul, New York | Sep 2021 - Apr 2025

- Shipped Aposto! mobile app (50+ screens): offline podcast, read list,
  Turkish/English, dark/light; releases via TestFlight and Play Console.
- 100K+ downloads; 3.05M App Store impressions; featured by Apple (2022);
  Top 3 in Turkey (Media).
- Co-built aposto.com (Next.js 12 + Redux): inbox, reading, authors, auth,
  follow/unfollow, share.
- Launched About and Newsletters subdomains (Next.js 13 App Router);
  Lighthouse 98.
- Premium subscriptions (Stripe): paywall; card add/switch/delete;
  subscription management; shared TypeScript KV paywall lib.
- Services: Categories and Premium Newsletters (Firestore + Next.js API with
  in-memory caching).
- Premium Stories: Go (chi) + SQLite, Cloudflare-cached via Next.js API;
  ~100K+ requests/month.
- Modernized Admin (CRA/React16/CRACO/Yarn -> Bun + Vite + React Router);
  built TTS editor UI (ElevenLabs).
- Quality and observability: Firebase Crashlytics monitoring;
  Detox E2E on paywall flows.
- Impact: 100K+ monthly visitors, 1.5M+ total users, >100K USD revenue;
  team ~10 across FE/BE/DevOps/PM/CTO.

### Sober Digital - Lead Full-Stack Engineer | Mar 2024 - Feb 2025

- Next.js 14 SSR e-commerce on Firebase Cloud Functions + Firestore
  (20+ endpoints) with iyzico; custom admin for merch, categories, coupons
  with limits.
- Festival-only inventory via QR-coded SKUs with isolated stock pools for
  physical events.
- Strapi CMS (self-hosted) modeling issue -> sections -> content; unified
  for web and mobile.
- Expo app: Feed; Events with iyzico ticketing + QR check-in + attendance;
  Explore (mini-games, Radio/Podcasts via Spotify); Shop
  (All/Magazine/Accessories/Clothing); Perks.
- Auth and growth: NextAuth on web; soft login/reg-walls for premium content
  on web and app.
- Media and performance: Bunny CDN; video carousel landing; GIF product
  galleries.
- Ops: Vercel (web), VPS-hosted Strapi, Firebase backend; infra ~50 USD/month
  peak (initial ~30 USD).
- Outcome: 50K+ users; 600K+ TRY GMV; SEO via "Sober People" catalog
  (50+ profiles).

### HyperCut - Co-Founder and Tech Lead | Istanbul | Apr 2023 - Dec 2024

- React Native reels editor: hypes, search/filter, auth, paywall, IAP,
  premium subscriptions with Firebase Cloud Functions, storage, and auth.
- Content pipeline: upload, storage optimization, processing.
- Landing site and admin dashboard with Next.js 14. BTM-backed
  (Istanbul Chamber of Commerce startup hub).

### ScheduleIt - Co-Founder and CTO | Oct 2023 - Dec 2024

- Automation web app for recurring tasks; 2nd at Solana Ideathon, 3rd at
  Solana Presentation; invited to Solana HyperDrive Global Hackathon.
- Next.js 14 frontend + Firebase Cloud Functions backend; scheduled jobs
  integrating WhatsApp Business API, Firebase Mail Sender, CoinMarketCap API.

### UrWord - CTO | New York | Aug 2022 - Dec 2023

- Sole developer for NYC integrity/trust platform: backend, database, mobile
  app, and admin site.
- 180+ TestFlight builds; Firestore with 10K+ docs and security rules; Firebase
  Cloud Functions with 12 REST endpoints across ~150 services (pacts,
  connections, user data sharing, notifications, moderation, analytics).
- Expo/React Native/TypeScript/Redux app (50+ screens, 1,000+ components) and
  admin web dashboard.

## Additional Experience

- Cheer Media - IT Consultant (part-time) | 2020 - Present: Benchmark Email
  setup; 6 newsletter signup sites (Next.js); 90+ Lighthouse scores.
- KmkocSoftware - Founder and CTO | Jan 2023 - Present: Client dashboard for
  Rational devices; custom API with Firebase Cloud Functions; React dashboard.
- Teamsfam - Backend Lead | Jan 2023 - Mar 2023: Led 2-person backend;
  ExpressJS + TypeScript on Firebase Cloud Functions.
- Kopitek - Frontend Developer | 2020 - 2021: Vue.js admin dashboard; SwiftUI
  iOS app and Java Android app.

## Awards and Hackathons

- Solana Ideathon - 2nd place; Solana Presentation - 3rd place; invited to
  Solana HyperDrive Global Hackathon (ScheduleIt).

## Open Source and GitHub Activity

- 4-year active GitHub contributor. Yearly totals: 1,561 (2022), 4,143 (2023),
  2,509 (2024), 2,885 YTD (2025).
- Notable repo: backup-service (Go backup service with Cloudflare R2) -
  https://github.com/kaanmertkoc/backup-service

## Education

- MEF University, Istanbul, Turkey - B.Sc. Computer Engineering, 2023.
  IAESTE member; finalist in inter-university algorithm competition in Turkey.
- University for Information Science and Technology "St. Paul the Apostle" -
  2021. Built iOS app "Code Tracker" with GitHub authentication; received
  full grade.
