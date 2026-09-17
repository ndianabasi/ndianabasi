# Ndianabasi Udonkang

**Senior Backend / Full-Stack Software Engineer · Technical Founder, [Gotedo](https://about.gotedo.com)**

I design, build, and operate production systems across backend, frontend, desktop, mobile, DevOps, and observability. 10+ years shipping customer-facing products and internal tools — including large API backends, self-hosted infrastructure, and production AI agents.

[Website](https://ndianabasi.com) · [Blog](https://ndianabasi.com/technical-blog) · [LinkedIn](https://www.linkedin.com/in/ndianabasi/) · [X](https://x.com/_ndianabasi) · [Gotedo](https://about.gotedo.com) · [Email](https://ndianabasi.com/contact)

---

## What I work on

- **AI agents** — LangChain, LangGraph, CrewAI, AutoGen, LlamaIndex. Multi-agent systems, RAG, conversation memory, tool orchestration.
- **Backend** — Node.js / TypeScript (expert), Golang. APIs, SSR, queues, OAuth2/OIDC from RFC, media pipelines.
- **Frontend & clients** — Vue, React, Next.js, React Native, Electron, Wails. Web, desktop (Linux/Windows/macOS), and mobile (Play Store / App Store).
- **Data** — PostgreSQL (design, tuning, PITR/WAL, HA), Redis, MySQL, SQLite. Prefer raw SQL when control and performance matter.
- **DevOps & observability** — Docker, Nginx, GitHub Actions, self-hosted fleets, Grafana, Prometheus, Jaeger / OpenTelemetry, Sentry.

---

## Selected production work

### [Gotedo Platform](https://about.gotedo.com) — Technical Lead / Senior Full-Stack Engineer (2019–Present)

Built and self-hosted the platform that powers Gotedo Vineyard, Gotedo Social, Gotedo Streams, Accounts, Billing, and related services.

- Node.js API backend: **300+ PostgreSQL tables**, **600+ routes**, **10,000+ functional tests**
- Custom **OAuth2 / OpenID Connect** identity server ([accounts.gotedo.com](https://accounts.gotedo.com))
- Billing & subscriptions comparable to Stripe / Chargebee
- Golang media processing service (images, video, audio — Cloudinary-class pipeline)
- Livestreaming (Gotedo Streams), realtime notifications (WebSocket + push), content moderation
- React Native social app (50+ screens) published to Google Play and the App Store
- Cross-platform desktop presentation software (Wails): multi-monitor, licensing, self-update, FFmpeg / libvips / libsql
- 100% self-hosted production: Docker deploys, Nginx L4/L7, PostgreSQL PITR, Fail2ban, Grafana / Prometheus / Jaeger
- Mentored five engineers from internship to junior / intermediate

### [Cavai Advertising](https://www.cavai.com) (Norway) — Senior Backend / Full-Stack Engineer (Nov 2021 – Feb 2024)

- Scaled ad creative serving from **100K to 1M+ requests/day**
- Multi-level access control and account management for large-scale onboarding
- Grew backend tests from **0 to 5,000+**; introduced CI/CD
- SOC2 / ISO 27000 audit logging; Cloudflare + AWS analytics pipelines

### Earlier

- **FURNISH.NG** — Founder & CTO (2016–2021): Magento ecommerce, dedicated Linux, Nginx / Redis / Elasticsearch, AWS
- **Donkan Designs** — Website developer (2014–2016), including the first Lagos City Marathon site

---

## Open-source contributions

| Project | Links |
| --- | --- |
| AI Auto-Translate Plugin for Strapi | [github.com/ndianabasi/strapi-plugin-ai-auto-translate](https://github.com/ndianabasi/strapi-plugin-ai-auto-translate) |
| PgBoss Plugin for Strapi | [github.com/ndianabasi/strapi-plugin-pgboss](https://github.com/ndianabasi/strapi-plugin-pgboss) |
| FFmpeg Sidecar for Gotedo Impress | [github.com/Gotedo/gotedo-impress-ffmpeg-sidecar](https://github.com/Gotedo/gotedo-impress-ffmpeg-sidecar) |
| Responsive Image Generation for AdonisJS | [npm](https://www.npmjs.com/package/adonis-responsive-attachment) · [GitHub](https://github.com/ndianabasi/adonis-responsive-attachment) |
| Cloudflare Storage Plugin for AdonisJS | [npm](https://www.npmjs.com/package/adonis-drive-r2) · [GitHub](https://github.com/ndianabasi/adonis-drive-r2) |
| Cloudflare Storage Plugin for Strapi | [github.com/Gotedo/strapi-provider-cloudflare-r2](https://github.com/Gotedo/strapi-provider-cloudflare-r2) |
| File Attachment Plugin for AdonisJS | [github.com/Gotedo/adonisjs-attachment](https://github.com/Gotedo/adonisjs-attachment) |
| Vue-tel-input | [github.com/Gotedo/vue-tel-input](https://github.com/Gotedo/vue-tel-input) |
| Unoserver for LibreOffice Automations | [github.com/Gotedo/unoserver](https://github.com/Gotedo/unoserver) |
| AdonisJS i18n | [github.com/Gotedo/i18n](https://github.com/Gotedo/i18n) |
| Argon2 Plugin for GlAuth (LDAP via PostgreSQL) | [github.com/Gotedo/glauth-postgres-argon2](https://github.com/Gotedo/glauth-postgres-argon2) |
| Bible Chapter Verse Parser | [github.com/Gotedo/Bible-Chapter-Verse-Parser](https://github.com/Gotedo/Bible-Chapter-Verse-Parser) |
| Satori-HTML | [github.com/Gotedo/satori-html](https://github.com/Gotedo/satori-html) |
| Akpoho Invoicing Software (full-stack) | [github.com/ndianabasi/akpoho-invoicing-software](https://github.com/ndianabasi/akpoho-invoicing-software) |
| Google Contacts Clone (full-stack) | [github.com/ndianabasi/google-contacts](https://github.com/ndianabasi/google-contacts) |

Teaching write-up for the Contacts clone: [30-part full-stack series](https://ndianabasi.com/technical-blog/series/clnwu9bc991hiu3wo2vwmw45/full-stack-google-contacts-clone-with-node-js-adonisjs-framework-and-vue-js-quasar-framework) (AdonisJS + Quasar/Vue). More notes at [ndianabasi.com/technical-blog](https://ndianabasi.com/technical-blog).

---

## Stack (working set)

`TypeScript` `JavaScript` `Golang` `Bash` · `Node.js` `AdonisJS` `Strapi` `Vue` `React` `React Native` `Next.js` `Wails` `Electron` · `PostgreSQL` `Redis` `PgBoss` `BullMQ` · `Docker` `Nginx` `GitHub Actions` · `Cloudflare R2` `SeaweedFS` · `Grafana` `Prometheus` `Jaeger` `Sentry` · `WebRTC` `WebSockets` · `LangChain` `LangGraph` `Playwright` `Crawlee` `FFmpeg`

---

## How I work

I stay with products whose vision I believe in. I own outcomes end-to-end — architecture, implementation, tests, deploy, and 3 a.m. incidents. I review a lot of code (5,000+ PRs) and I train people who can eventually replace me.

## Education

- B.Eng. Mechanical Engineering, Federal University of Technology, Owerri (2005–2010).
