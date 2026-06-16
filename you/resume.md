# Resume (raw material)

Latest resume content, for finding honest, specific hooks when researching targets.
Source: `~/Documents/GitHub/portfolio/resume/RichTillman_Resume_v3.5.md` (Jun 12 2026,
newest), reconciled with `FACTS.md` (source-of-truth for dates + immutable rules).

> Per FACTS.md: NO Verizon (removed — disaster engagement), NO phone number, NO
> graduation year. EPCVIP + FaceCake folded into "Earlier experience." Dates marked
> ⚠️ in FACTS.md still need primary-source verification before any send.

**Rich Tillman** — Principal Frontend Engineer · Design Systems · AI Developer Tooling
Remote, USA · richtillman@pm.me · linkedin.com/in/effinrich · github.com/effinrich · richtillman.xyz · forgekit.cloud

**Testimonial (Redesign Health, 2023):** "Rich can 'speak design' in a way that few
engineers can — he can explain the engineering to design and the design to
engineering. We have hardcore data engineers working productively on intricate
styling problems, all on the rails Rich laid down." — Matt Stephenson, Director of
Engineering.

## Summary
Senior/Principal Frontend Engineer shipping production React UI apps and design
systems at scale. Modern stack throughout — React 19, TypeScript 5.x (strict),
TanStack Router/Query/Start, Tailwind CSS 4, Figma + Figma Code Connect.
Double-promoted to Engineering Director at Redesign Health (50+ component design
system, 30% dev-time cut). Shipped a 200-component React/React Native library at
Freebird and a $400K/mo browser-based AR app for NARS. Creator of ForgeKit, an MCP
toolchain (5,703+ npm installs) bridging Figma design systems to production React.
Targeting Senior / Staff / Principal FE on React-heavy product + design-system teams.

## Career impact (hook metrics)
- **5,703+** external npm installs — ForgeKit MCP packages, active production adoption
- **$400K/mo** revenue lift — browser-based AR app for NARS Cosmetics
- **200+** component React library (B2B, B2C, React Native) at Freebird
- **500K+** monthly active users across shipped React Native apps
- **50+** design-system components, 30% dev-time reduction (Redesign Health)
- **40%** rendering-overhead reduction via custom hooks + Zustand

## Experience

### Engineering Director — Staff Frontend Engineer & Tech Lead (0→1)
**Redesign Health · Remote · Jul 2022 – May 2024**
- Double-promoted (skip-level) to Eng Director; managed direct reports, ran 1:1s, coordinated delivery across 3 cross-functional teams (15+ members) while staying hands-on.
- Proprietary onboarding method (Storybook + feature-based architecture + custom hooks) — trained 2 backend engineers to production React in 1 month.
- React design system, 50+ components (Storybook + Chromatic) — 30% dev-time reduction across 10–15 eng org.
- 20+ data-viz components (custom hooks + Zustand) — 40% rendering-overhead reduction; Chromatic visual-regression catching regressions pre-merge.
- Fixture-based mock-API strategy unblocked a high-stakes demo on a 2-day deadline.

### Senior Frontend Engineer & Tech Lead (Consultant)
**Pineapple Corporation · Remote · Jan 2022 – Jul 2022**
- Nx monorepo across 8+ apps — 35% VCS efficiency gain (shared libs + `nx affected`).
- Cross-platform Expo / Nx / NativeBase / React Native in TS — 25% iOS/Android perf gain for 100K+ users.
- Storybook + Chromatic workflow, 60+ components — 50% faster stakeholder design reviews.

### Founding Frontend Engineer (0→1)
**PHC Global · Remote · Jul 2021 – Jan 2022**
- Foundational Nx monorepo for B2B fintech dashboard (30+ shared libs, gRPC middleware) — 40% DX improvement.
- Refined UX across 8+ fintech workflows — +35% NPS. Cut infra cost 30%; shipped 8 weeks early on GCP, gRPC, Helm, Kubernetes.

### Lead Frontend Engineer (0→1)
**Freebird · Santa Monica, CA · Sep 2016 – Jan 2021**
- One of the earliest production React UI libraries on Storybook — 200-component system spanning B2B, B2C, React Native; extending to RN eliminated need for separate iOS/Android teams.
- Design–engineering liaison across client, sales, marketing; led offshore teams (India, Philippines).
- Built/maintained B2B/B2C/internal dashboards (React + NestJS) + the RN mobile product.

**Earlier experience:** pioneered browser-based AR with computer vision in JavaScript
(Lead Web Developer, FaceCake Marketing Technologies, Oct 2010 – Sep 2016). NARS
try-on campaign drove ~$400K/mo revenue lift. Detail on request.

## Current work & selected projects

### AI Training & Evaluations — Mercor · micro1 · Handshake (concurrent contracts)
**Remote · Nov 2025 – Present**
- Authored programming prompts + evaluation rubrics for an AI lab's frontend benchmark suite — head-to-head model comparisons vs frontier LLMs (Anthropic, OpenAI, Google, Meta) — React component architecture, TS strict patterns, Storybook-driven dev.
- Built AI-driven developer UI for interactive coding environments: React 19, TanStack Start, Chakra UI, Storybook 10+, Nx.
- Advised eng teams on integrating AI-assisted workflows (Claude Code, Cursor) into production.

### ForgeKit — Open-Source MCP Suite (npm, 5,703+ installs)
**Oct 2025 – Present**
- ForgeKit was scaffolded *by* ForgeKit — CLI, two MCP servers, Storybook integration, CI/CD bootstrapped using prior versions of itself; every release ships through its own pipeline. Recursive proof of production-readiness.
- **ForgeKit Core CLI** (forgekit.cloud) — scaffolds production-ready Nx monorepos (React, Storybook, Vitest, Playwright, CI/CD); targets Chakra UI, shadcn/ui, Tamagui across web + RN.
- **ForgeKit Figma MCP** (npm: forgekit-figma-mcp) — extracts Figma variables/design tokens; generates typed theme configs for Chakra, Tailwind, shadcn.
- **ForgeKit Storybook MCP** (npm: forgekit-storybook-mcp) — exposes Storybook metadata/argTypes to AI coding agents; automates story/doc/test generation.

### richtillman.xyz — personal site (live, 2025 – Present)
- Modern stack production teams adopt now: React 19, TS strict, TanStack Router/Query/Start (SSR/edge), Tailwind CSS 4, Radix UI. Deployed on Cloudflare via official Vite plugin (edge-rendered).
- Storybook 10+ component library (a11y, docs, themes addons); React Hook Form + Zod; Recharts. Toolchain: Vite 7, oxlint + oxfmt (Rust), lefthook.
- Source: github.com/effinrich/portfolio.

### Tidy App — React Native / Expo (internal beta, 2024 – Present)
- Offline-first, ADHD-friendly home-management app (React Native + Expo Router, Gluestack UI / NativeWind), accessibility-first.
- Resilient offline-first data layer (Zustand + TanStack Query) for optimistic UI — instant feedback core to neurodivergent UX.
- Supabase (Auth, PostgREST, Realtime); RevenueCat monetization. Invisible background AI tracking that learns patterns + optimizes scheduling without intrusive prompts.
- Full Figma Code Connect: `figma.config.json`, 8 primitive `.figma.tsx` mappings, 20 component annotations.

## Skills
| Area | Stack |
|------|-------|
| **Frontend** | React 19, TypeScript 5.x (strict), Next.js, React Native, Expo, TanStack Router, TanStack Start |
| **UI & Styling** | Tailwind CSS 4, Chakra UI, shadcn/ui, Tamagui, Ark UI, Radix UI, NativeWind |
| **Design Systems** | Figma, Figma Code Connect, Figma MCP, Storybook 10+, Chromatic, Design Tokens |
| **State & Data** | TanStack Query, Zustand, Supabase, PostgreSQL, tRPC, gRPC |
| **AI & MCP** | Model Context Protocol, Claude Code, Cursor, Anthropic API |
| **Monorepo & DX** | Nx, Nx Agents, Turborepo, pnpm workspaces, Module Federation, GitHub Actions, EAS Build |
| **Testing & a11y** | Vitest, Jest, Playwright, RTL, Storybook a11y, WCAG 2.1 AA |

## Certifications
- Design System Certification — Brad Frost & Dan Mall (Atomic Design methodology)
<!-- NO school/education entry — fully removed per user decision. Do not reintroduce. -->>
