# Hi, I'm Arthur 👋

Full-stack engineer from Brazil. I ship across the whole product: **Kotlin Multiplatform** mobile apps, **React + TypeScript** web apps and **Java 21 / Spring Boot** APIs, with tests and CI on all of them.

📂 **Case studies:** [mirandanc.github.io](https://mirandanc.github.io) · 💼 [LinkedIn](https://www.linkedin.com/in/amnc-development/) · 📫 miranda1991chaves@gmail.com

---

## What I'm working on

I'm a full-stack engineer at **[EasyPDV](https://easypdv.com.br)**, the platform behind autonomous self-checkout mini-markets in condominiums and offices: kiosk checkout, cloud ERP, warehouse operations and payments (PIX, cards). On the public site, the platform reports **500K+ transactions** in **15+ condominiums**. It also powers **[Despensinha](https://despensinha.com.br)**, an autonomous-market network in Northeast Brazil.

That code is private, so most of my green squares come from it. Here is what I built:

| Product | My role | Highlights |
|---|---|---|
| **[Operator app](https://play.google.com/store/apps/details?id=br.com.uniolab.easypdv.operatorapp)**<br>Kotlin Multiplatform (Android + iOS) | Main developer, ~700 of ~900 commits | Picking, restocking, inventory counts and goods receipt for warehouse staff. Continuous camera and handheld barcode scanning, offline-safe photo capture with background upload, push notifications, automated Play Store and iOS release pipeline. |
| **Admin ERP**<br>React 19 + TypeScript | 55+ merged PRs | Announcements with a rich-text editor, video and read receipts. Sales risk dashboard, recurring calendar, ABC-curve reports, supplier-invoice checking on mobile, and a reusable data table with barcode scan-to-search. |
| **Core API**<br>Java 21 + Spring Boot, multi-module | 20+ merged features | **Sales risk analysis:** pluggable detectors with per-signal weights score each self-checkout sale for theft signals, plus bulk re-evaluation as background jobs. Announcements with concurrency-safe receipts and S3 media, real-time alerts over SSE, recurring appointments, faster stock tasks. |
| **Nexus**<br>Bun + Elysia + Prisma, React | Wrote ~97% of the commits | Service that reconciles and syncs products, points of sale and planograms from third-party systems into EasyPDV. Diff and approval before writing, retry and skip accounting, operation reports. |

## Tech I use daily

- **Mobile:** Kotlin, Compose Multiplatform, MVIKotlin, Koin, Ktor, Room, CameraX + ML Kit, Firebase
- **Frontend:** React, TypeScript, Vite, TanStack Query/Table, Formik + Yup, TipTap, Vitest, Testing Library, MSW, Playwright
- **Backend:** Java 21, Spring Boot (Web, Data JPA, Security), MySQL, Liquibase, RabbitMQ, MapStruct, JUnit 5, Testcontainers, WireMock, ArchUnit
- **Also:** Bun, Elysia, Prisma, Node, Python
- **Delivery:** Docker, GitHub Actions, semantic-release, SonarQube, AWS S3, Cloudflare Workers

## How I work

- Tests come with the feature: unit, slice, Testcontainers integration, and concurrency tests where it matters.
- Big features ship as small stacked PRs that are easy to review. Conventional Commits, SonarQube-clean code.
- I write a short design doc before building anything large.
- I use AI coding agents with project rules and custom lint guards that keep them to the team's standards.

## Side projects

- 🧮 **[Crafting Calculator](https://github.com/mirandanc/Crafting-Calculator)** ([live](https://crafting-calculator.miranda-chaves.workers.dev)). Works out whether crafting an item in *World of Warcraft* is profitable. React + TypeScript on Cloudflare Workers, with auction-house prices pulled twice a day from the Battle.net API by GitHub Actions into Workers KV. Tested with Vitest.
- ✅ **[simpleCheckList](https://github.com/mirandanc/simpleCheckList)**. Android checklist app in Kotlin with Jetpack Compose, Clean Architecture (use cases, repositories), Hilt, Room and Retrofit.
- ⏰ **[DotaReminder](https://github.com/mirandanc/DotaReminder)**. Python tool that reads Dota 2 Game State Integration events and plays timed in-game reminders.
