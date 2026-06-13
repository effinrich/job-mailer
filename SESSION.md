# Session Ritual

This file is how a job-hunt session begins and ends. Claude reads it first every
time and updates the log at the end. It's the thing that makes returning feel
seamless.

## When you sit down ("let's work the job hunt")

Claude will:
1. Read `pipeline.md` and report the board in one breath:
   *"X awaiting your Send, Y follow-ups due, Z replies need a response, N in research."*
2. Surface the **next best actions** — usually: replies to handle, then follow-ups
   due, then drafts awaiting approval, then new research.
3. Wait for you to pick, or just start at the top.

## When you wrap up

Claude will:
1. Update every contact file and `pipeline.md` to true current status.
2. Append a dated entry to the **Session Log** below: what moved, what's pending.
3. Note any follow-up dates that will come due before next time.

## Cadence rule of thumb

- Follow-up #1: ~3–4 business days after sending, if no reply.
- Follow-up #2 (final): ~5–7 days after that.
- After that: `closed-ghost`. Move on; the pipeline stays clean.

---

## Session Log

<!-- newest first; Claude appends here -->

### 2026-06-13 — Radix MCP → standalone public repo
Moved `forgekit-radix-mcp` OUT of forgekit-v2 into its own repo:
- Local: `~/Documents/GitHub/forgekit-radix-mcp` (self-contained configs, npm-based).
- LIVE: https://github.com/effinrich/forgekit-radix-mcp (public, pushed). typecheck +
  6/6 tests + build all green standalone. 26 primitives.
- Removed from forgekit-v2 (reset commit 8c66c99, deleted packages/radix-mcp);
  forgekit-v2 back to clean HEAD 3d780e6, user's WIP untouched.
YOUR steps: `npm publish` from the repo → then post (Channel 8) with npm link.

### 2026-06-13 — Radix MCP expanded + committed + post drafted
- Expanded `forgekit-radix-mcp` 5 → **26 primitives** (added AlertDialog, Accordion,
  Tabs, Checkbox, RadioGroup, Switch, Toast, HoverCard, ContextMenu, Menubar,
  NavigationMenu, Slider, Toggle, ToggleGroup, Collapsible, Avatar, Progress, Label,
  Separator, AspectRatio, ScrollArea). 6/6 tests, build clean, 26 verified live.
- Committed scoped → forgekit-v2 `8c66c99` on branch `clean-n-update` (only
  packages/radix-mcp; left user's WIP untouched). NOT pushed.
- Build-in-public post (X + LinkedIn) drafted → contact file Channel 8, HELD until
  `npm publish` (need live link `[LINK]`).
YOUR remaining steps: (a) verify anna@workos.com → Send draft; (b) `npm publish`
forgekit-radix-mcp; (c) post Channel 8 with the live link; (d) push clean-n-update if wanted.

### 2026-06-13 — all 3 WorkOS moves done
1. ✅ PR #3964 open + healthy (changeset-bot only; awaiting @chaance). Monitoring.
2. ✅ Recruiter found: Anna Meyer (Talent @ WorkOS, linkedin.com/in/annaemeyer).
   Gmail draft created (id r3622363288118336831) → anna@workos.com (BEST-GUESS pattern,
   VERIFY before Send). Cold email now leads with PR #3964 as proof.
3. ✅ Built `forgekit-radix-mcp` v0.1.0 at forgekit-v2/packages/radix-mcp. 3 tools
   (list_primitives/get_primitive/get_a11y_contract), 5 primitives w/ a11y contracts,
   6/6 tests, build clean, stdio server verified. NOT published/committed yet.
Open follow-ups: verify Anna's email → Send; npm publish radix-mcp + build-in-public
post; optional commit to forgekit-v2 (note: repo has pre-existing context-mcp/mcp-core
install error, unrelated to new pkg).

### ▶ (superseded) RESUME HERE (post-OMC-restart) — do all 3
WorkOS push. Context: `contacts/workos-frontend.md` (all drafts + channels + Radix-MCP
spec in Ch.7). Resume repo now at `~/Documents/resume` (standalone). Radix fork on
GitHub: effinrich/primitives, branch `fix/tooltip-window-refocus` (local clone was
`/tmp/primitives` — may be wiped on reboot; re-clone if gone).

1. **Watch PR** https://github.com/radix-ui/primitives/pull/3964 — check for @chaance
   review/CI. If comments: respond fast + well (that exchange = the interview). Use
   `gh pr view 3964 -R radix-ui/primitives --comments`.
2. **Find recruiter email** — search WorkOS recruiter/talent (Chrome MCP on logged-in
   LinkedIn, or Rich supplies name). Then finalize Channel-2 cold email (NOW reference
   PR #3964: "shipped a small Radix tooltip fix last week") + push to Gmail Drafts via
   Gmail MCP. Rich hits Send.
3. **Build Radix MCP MVP** — per Ch.7 spec: MCP server `list_primitives` /
   `get_primitive(name)` exposing props (from TS types) + a11y contract, for ~5
   primitives (Dialog, Tooltip, Select, DropdownMenu, Popover). Could extend ForgeKit
   or new `radix-primitives-mcp`. Then build-in-public post + reference in outreach.


### 2026-06-13 — WorkOS campaign opened
Role: SWE Frontend @ WorkOS ($175–250K, remote ww, maintain Radix). Resume already
submitted via Ashby. Built `contacts/workos-frontend.md` — full multi-channel kit:
Radix engagement (GitHub/X), cold email, referral ask, LinkedIn connect + InMail,
follow-up — all drafted per voice.md. Pipeline row added, status `drafted`.
BLOCKED on real addresses to push Gmail drafts: recruiter/talent email (channels
2/4/5), Rich's network contacts (3). Non-email actions (Radix PR, LinkedIn) are his.
✅ Radix PR opened: https://github.com/radix-ui/primitives/pull/3964 (tooltip #1800,
7/7 tests + lint/typecheck green). Razzle-dazzle Radix-MCP suggestion + concrete
example drafted in contact file Ch.7 (decide build after PR lands). Fork clone +
node_modules at /tmp/primitives. Next: find WorkOS recruiter email; reference PR in
outreach; decide on building the Radix MCP MVP.

### 2026-06-13 — resume FACTS cleanup (portfolio repo)
Purged FACTS violations across `~/Documents/GitHub/portfolio/resume/`:
- DELETED orphans: `RichTillman_Resume_ATS.docx` (Verizon + phone + school yrs + "AI
  Expert" + "15+ years"), `RichTillman_Resume_v3.5.docx`, `RichTillman_Resume_v3.5.md`.
- FIXED `build-resume.mjs` summary: dropped "15+ years" → adopted THE_ONE's year-free
  summary. Regenerated `RichTillman_Resume.docx` (clean) + `RichTillman_Resume.pdf`
  via LibreOffice (clean; ⚠️ rendered 4pp — re-export from Pages/Word for tight 2pp).
- FIXED `cover-letter.mjs` (dropped "EPCVIP" mention) → regenerated WorkOS + PrizePicks
  cover letter docx (both clean).
- Verified clean: `build-resume.cjs` (no textual violations).
- ⚠️ NOT verifiable/edited (binary Apple Pages, May 20, may hold old violations):
  `RichTillman_Resume.pages`, `Rich_Tillman_Principal_Staff_..._AI_Frontend_Resume-new.pages`
  → open in Pages, check/fix manually, or delete if superseded.
- ⚠️ NOT edited (intentional, personal verbal prep, not a resume artifact):
  `Flick-Interview-Prep.md` — contains "15 years" + "Verizon" as interview talking
  points. User's call whether to scrub.
Canonical resume now = `RichTillman_Resume.docx` (built from `build-resume.mjs`).
MOVED resume folder out of portfolio repo (was gitignored) →
`/Users/richtillman/Documents/resume/`. Now self-contained: added `package.json`
(docx dep) + `bun install`; build/cover scripts verified from new path. Deleted all
Flick files (`Flick-Interview-Prep.md`), stripped Flick refs from CLAUDE.md +
emptied resume `.gitignore`. Portfolio `.gitignore` had its `resume` line removed.
`.pages` files kept untouched per user.

### 2026-06-13 — setup (revised)
Refilled `you/profile.md` + `you/resume.md` from NEWEST source:
`portfolio/resume/RichTillman_Resume_v3.5.md` (Jun 12, richest) reconciled with
`portfolio/resume/FACTS.md` (source-of-truth for dates + immutable rules).
Title now **Principal Frontend Engineer · Design Systems · AI Dev Tooling**.
⚠️ CONFLICT FLAGGED for user: user pointed at `RichTillman_Resume_ATS.docx`, but it's
OLDER (16:34 vs v3.5 17:02) and VIOLATES FACTS.md — it still lists Verizon (FACTS:
"fully removed, disaster engagement"), a phone number, "15+ years", "AI Expert", and
grad years, all forbidden. Did NOT copy those. User to confirm which version is canon.
Date-verification: several roles still ⚠️ in FACTS.md — verify before any send.
Pipeline still empty — 0 contacts. Next: add first target(s) and draft.
Note: WorkOS outreach kit exists at `~/Desktop/resumes/claude-2026-resumes/` — reusable.

### (no sessions yet)
Workbench scaffolded. Next step: fill `you/profile.md` and `you/resume.md`, then
add the first target.
