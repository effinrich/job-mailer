# Infisical — Design Engineer, Platform (campaign)

- **Role angle:** FIRST Design Engineer — own user-facing experience, build reusable React/TS components, perf + a11y + responsive, lead FE architecture for new product lines (PKI/SSH/KMS).
- **Company:** Infisical — open-source secrets management / developer security. YC. SF + remote (US).
- **Comp:** $140–200K + 0.10–0.50% equity.
- **Apply:** Ashby → jobs.ashbyhq.com/infisical/ee25fbbb-c3c6-4c51-a664-1539350616b9 (or infisical.com/careers)
- **Stack:** React, TypeScript (3+ yrs), frontend architecture.
- **Status:** `researching` (not yet applied)
- **Fit:** 9/10 — founding-DS + a11y + OSS = his exact shape.

## Why them
"First design engineer" = own the UI bar from scratch, exactly Rich's founding-DS
profile. A11y is explicitly called out — his hand-built ARIA edge. Open-source security
tooling matches his OSS ethos (ForgeKit MIT) + dev-tooling domain. Trust in security
products is won/lost in the UI — clarity is the job.

## Tailoring — emphasize
1. Standing up reusable component systems from zero (50–200 components).
2. **A11y by hand** — ARIA contract, focus mgmt, screen-reader testing (role calls it out).
3. Leading FE architecture across multiple product lines (Nx monorepos).
4. OSS maintainer instincts (ForgeKit MIT, build-in-public).
De-emphasize: deep security-protocol internals (frame as "learn fast; MCP = permissions thinking").

## The hook
"Being your first Design Engineer — owning the UI of a fast-growing OSS security
platform — is a mandate I'd take seriously. Security earns trust through clarity, and
the UI is where that's won or lost."

## CHANNEL 1 — Ashby apply + cover letter (do first)
Cover letter: `~/Documents/resume/RichTillman_CoverLetter_Infisical.docx` (generated, FACTS-clean).

## Founders (who to email + why)
- **Vlad Matsiiako — CEO** 🇺🇦 Ukrainian (surname -ko ending; ex-**Figma** + bunq; Cornell MEng ORIE = data-driven). Public/narrative-driven. **← EMAIL HIM.** Ex-Figma = speaks design-eng natively; first-design-eng is the CEO's strategic hire; rewards concrete metric-backed pitch.
- **Maidul Islam — CTO** Bangladeshi-American (NYC). Ex-AWS, Node.js, full-stack. Backend/infra builder, heads-down, less public. Wrong target for a design-eng pitch.

## ✅ CHANNEL 2 — Cold email → vlad@infisical.com (Gmail draft id r-6164643269683383878)
Vlad-specific: leads with his Figma background, Agent-Vault resonance (Rich builds MCP
for Claude-Code agents), #6783 feature pitch, stack match (TanStack Router + Storybook).
SEND once Infisical application submitted. (Draft below = the original generic version, kept for reference.)

### (reference) generic cold email draft
> Subject: Design Engineer (Platform) — first-DS, a11y, OSS (Rich Tillman)
>
> Hi [name] — I applied to be your first Design Engineer. Owning the UI of an
> open-source security platform from the component layer up is exactly the mandate I
> want. ~10 yrs on the design–engineering seam: 50–200 component React/TS systems built
> from zero, accessibility by hand (I know the ARIA contract), and open-source dev
> tooling (ForgeKit, MIT, ~5,700 npm installs). Live: richtillman.xyz · forgekit.cloud.
> Happy to do a work sample. Thanks — Rich · github.com/effinrich

## CHANNEL 3 — LinkedIn connect (≤300; find Infisical founder/recruiter)
> Hi [Name] — applied for Design Engineer (Platform). I've stood up 50–200 component
> React/TS design systems from scratch, do a11y by hand, and ship open-source dev tooling
> (ForgeKit). Being your first design engineer is squarely my shape. Portfolio:
> richtillman.xyz. Would love to be on your radar.

## Repo recon (2026-06-15)
- 27k+ stars, TypeScript-heavy. **Frontend stack = TanStack Router + Storybook + strict TS + Vite** (`tsr.config.json`, `.storybook`). = RICH'S EXACT STACK (richtillman.xyz on TanStack Start + Storybook). Huge alignment — call it out.
- Live frontend issue (show-don't-tell PR target): #1411 "Signup button cutoff on desktop" — `good first issue` + `help wanted` + `👀 frontend`. Visible UI fix = perfect design-eng proof. Also #6639 (login crash on stale cookie), #6124 (stale FE assets).

## CHANNEL 0 — Loom video (optional in app, HIGH leverage — "put a face to it")
1–2 min, spoken-natural. Grounded in the stack match + first-DS mandate + a11y + OSS:

> Hi — I'm Rich. I'm applying to be Infisical's first Design Engineer, and I wanted to
> put a face to it.
>
> Two reasons I'm genuinely excited. First, the mandate — owning the user-facing
> experience of an open-source security platform from the component layer up. Security
> tooling earns trust through clarity, and the UI is where that's won or lost. That's
> exactly the work I want.
>
> Second, I dug into your repo, and you're on TanStack Router, Storybook, and strict
> TypeScript — that's almost exactly my stack. My own site runs on TanStack Start and
> Storybook, and I've spent the last year on ForgeKit, an open-source MCP toolchain in
> the same world.
>
> On fit: I've stood up 50-to-200 component React design systems from scratch — the
> documented patterns a team builds on. I implement accessibility by hand because I
> actually know the ARIA contract, which your role calls out directly. And I think in
> reusable, well-documented primitives — the posture an open-source tool needs at the
> UI layer.
>
> I'd love to lay that foundation for your newer product lines. Thanks for watching.

(~190 words ≈ 1.5 min. Trim the ForgeKit line if running long. Record on richtillman.xyz
or the Storybook open in the background for visual proof.)

## Repo verdict (deep recon 2026-06-17)
IN FLUX but WELL-GOVERNED (not messy/unowned):
- 2 backends: `backend` (Node/TS) + `backend-go` (Go) → strategic migration, not chaos.
- Frontend mid Next→TanStack migration: `pages/` (old) + `routes/`+`routeTree.gen.ts` (new TanStack Router). Naming churn (`const.ts`/`const/`/`consts/`).
- Governance solid: CONTRIBUTING, SECURITY, PR template, **20 CI workflows**, per-area CLAUDE.md, conventional commits. 15 PRs merged / ~2 days, **multiple maintainers**, externals DO merge.
- **Frontend owner = @scott-ray-wilson** (engage his work; he'd review a FE PR).
- Open issues ~90% backend/security → clean FE targets scarce (FE kept tight).

## ROADMAP angle (cover-letter / Loom GOLD)
- Expanding into **AI-workload security** — shipped **Agent Vault**: an HTTP credential
  proxy + vault for AI agents *like Claude Code*. Rich builds MCP tooling FOR Claude Code
  → deep resonance (he's their exact user + builder audience).
- Also PKI/certs + PAM (privileged access). New Go server.
- TWO killer angles for Rich:
  1. "You're mid Next→TanStack migration — I live on TanStack Router; I've done this exact move."
  2. "You're building Agent Vault for Claude-Code agents — I build MCP servers for that same audience (ForgeKit)."

## PR target — REVISED
- #1411 = DEAD (Feb-2024, 16c, picked-over, FE rearchitected). Skip.
- Issue-fix PRs weak here (FE targets scarce; the few need full-app repro = risk).
- IF a code artifact wanted: SAFE + on-brand = a **Storybook-isolatable a11y/component
  improvement** (they have `.storybook` + 40 `.stories.tsx`; testable WITHOUT backend;
  a11y = Rich's design-eng calling card; they accept "improvement:" PRs). Needs clone + Storybook run.
- Lower-risk alt: skip PR, lean Loom + cold email (Agent-Vault + migration angles). Strong + safe.

## Next
- Loom (Channel 0) → add the Agent-Vault + migration lines if running short on the generic version.
- Cold email → CEO/CTO pick (vlad@ / maidul@infisical.com), once applied. Weave Agent-Vault resonance.
- PR: only if Rich wants the Storybook a11y route (testable). Else hold.

## History
- 2026-06-13 — created, cover letter generated. Not yet applied. Apply via Ashby first.
