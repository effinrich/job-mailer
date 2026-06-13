# WorkOS — Software Engineer, Frontend (campaign)

- **Role angle:** Software Engineer, Frontend — maintain Radix UI, set UI quality bar, build component patterns product engineers use. $175–250K, remote worldwide.
- **Posting:** jsgurujobs.com/jobs/477 (reseller) → real apply: jobs.ashbyhq.com/workos
- **Email:** multiple targets — see channels below (most need address confirmation)
- **Status:** `drafted` (resume already submitted via Ashby; outreach drafted, not yet sent)
- **Follow-up due:** —

> Multi-channel campaign, not one person. Tracked as a single role push. The final
> Send (and any GitHub/X/LinkedIn action) is always yours.

## Why them (not generic)
WorkOS is one of the few shops where frontend *is* the product — they maintain **Radix
UI** (ex-Modulz team on staff). Rich builds on Radix daily, implements a11y by hand
(knows the ARIA contract), and ships open-source design-to-code tooling (ForgeKit,
5,703+ npm installs) that syncs Figma tokens into Radix/shadcn. The role's literal job
— "contribute to Radix, build the component patterns product engineers rely on, set
the UI quality bar" — is the exact work Rich already does. Tightest fit on the board.

## Research notes
- Role responsibilities map 1:1 to Rich's resume: Radix contribution, reusable
  component patterns, a11y, frontend architecture + data loading, design quality bar.
- Radix maintainers on staff (engage their *work*, do NOT cold-DM for a job):
  Pedro Duarte (@peduarte), Colm Tuite (@colmtuite), Vlad Moroz (@vladyslavmoroz),
  Lochlan Bunn (@loklaan).
- Founder/CEO: Michael Grinich (@grinich). Founder-led, "developer joy" culture.
- ⚠️ Need to find: a WorkOS recruiter/talent name + email (LinkedIn search
  "WorkOS recruiter" / "WorkOS talent"), and a hiring-manager name if shown on Ashby.

## The hook (the make-or-break line)
"WorkOS is one of the few places where frontend *is* the craft — you maintain Radix,
the library I reach for whenever an interaction has to be correct and accessible."

---

## CHANNEL 1 — Radix engagement (highest leverage; GitHub/X action, NOT email)
Do this for real, this week. Beats any cold message.
- File a genuine issue or small PR on `radix-ui/primitives` — a real doc gap, TS types
  nit, or a11y edge case you actually hit. Quality over size.
- OR a substantive reply to @peduarte / @colmtuite when they post on Radix / a11y /
  design systems — add real insight, not "big fan."
- Reference it later in the loop ("sent a small Radix PR last week: [link]").
- ⚠️ Don't mass-DM maintainers asking for a job.

## CHANNEL 2 — Cold email — ✅ IN GMAIL, address VERIFIED, awaiting your Send
> Recipient anna@workos.com verified 100% valid (Anna Meyer, Talent @ WorkOS).
> Gmail draft id r3622363288118336831. Leads with PR #3964 as proof. Just hit Send.

> **Subject:** Frontend application — design systems + Radix/a11y (Rich Tillman)
>
> Hi [name] —
>
> I applied for the Software Engineer, Frontend role and wanted to put a face to it.
> WorkOS is one of the few places where frontend *is* the craft — you maintain Radix,
> the library I reach for whenever an interaction has to be correct and accessible.
>
> Short version: ~10 years on the design–engineering seam — 50–200 component React
> design systems (Storybook + Chromatic), accessibility by hand because I actually
> know the ARIA contract, and lately open-source design-to-code tooling (ForgeKit,
> 5,703+ npm installs) that syncs Figma tokens into Radix/shadcn.
>
> Fastest way to see how I build: richtillman.xyz (live, Radix-based) and
> forgekit.cloud. Happy to do a work sample whenever it's useful.
>
> Thanks for your time,
> Rich · richtillman@pm.me · github.com/effinrich

## CHANNEL 3 — Warm referral ask (#3) — DRAFT READY, needs your network contacts
> Quick ask — I'm going after the Senior/Frontend role at **WorkOS** (the team behind
> Radix UI). It's the most "my-shaped" job I've seen in a while: design systems,
> accessibility, React craft. Do you happen to know anyone there who could pass my
> name along? Happy to send a 3-line blurb + my portfolio (richtillman.xyz). 🙏

## CHANNEL 4 — LinkedIn connect to Anna Meyer (Talent @ WorkOS) — ≤300 chars, you send
> Hi Anna — applied for the Frontend Engineer role. ~10 yrs in design systems + a11y;
> I build on Radix daily. Just opened a small a11y PR to radix-ui/primitives (#3964) to
> show rather than tell. Portfolio: richtillman.xyz. Would love to be on your radar.

  (Profile: linkedin.com/in/annaemeyer — connect with this as the note.)

## CHANNEL 5 — LinkedIn InMail / longer DM to Anna (you send) — use if connect accepted or for a richer first touch
> Hi Anna — I just applied for the Software Engineer, Frontend role and wanted to
> introduce myself directly. ~10 years on the design–engineering seam: I've built
> 50–200 component React design systems (Storybook + Chromatic), I implement
> accessibility by hand because I know the ARIA contract, and I ship open-source
> design-to-code tooling (ForgeKit, 5,703+ npm installs) that syncs Figma tokens into
> Radix/shadcn.
>
> Two proof points instead of a pitch: I just opened a small a11y fix to Radix itself
> (radix-ui/primitives #3964), and I built an MCP server that teaches AI coding agents
> the Radix accessibility contract (github.com/effinrich/forgekit-radix-mcp). WorkOS is
> the rare place where frontend quality *is* the product — exactly the work I want.
>
> Two-minute look at how I build: richtillman.xyz and forgekit.cloud. Glad to do a work
> sample or talk through the component patterns your product engineers rely on. Thanks — Rich

## CHANNEL 6 — Follow-up nudge (5–7 days after applying, only if no reply)
> Hi [Name] — circling back on my Frontend application. Since I wrote, I [shipped a
> small Radix PR / wrote up an accessible-combobox build]: [link]. Still very keen on
> WorkOS — let me know if a work sample or quick chat would help. Thanks — Rich

## CHANNEL 7 — "Razzle-dazzle" suggestion: Radix Primitives MCP (the differentiator)

> Not a cold pitch — a real artifact that bridges Chance (craft) and WorkOS strategy
> (MCP-forward). Build a small MVP, post build-in-public, reference in outreach. The
> existing community "Radix Claude Code Skill" proves demand; the a11y-contract
> coverage is Rich's edge over it.

**The problem it solves:** AI coding agents (Claude Code, Cursor) hallucinate Radix
prop names, miss required ARIA wiring, and reach for the wrong primitive. There's no
authoritative, machine-readable source of Radix component APIs + their accessibility
contracts for agents.

**What it exposes (MCP server, à la `forgekit-storybook-mcp`):**
- Every primitive's parts, props, types, defaults (from source/types — accurate, not scraped)
- The **a11y contract per primitive**: required ARIA, keyboard interactions, focus
  management expectations, common misuse → the differentiator nobody else ships
- Composition patterns + correct examples (so agents stop inventing APIs)
- Optional: lint-style "is this Radix usage accessible?" checks for agents

**Why it lands at WorkOS specifically:**
- WorkOS is all-in on MCP (AuthKit MCP, FGA tool-scoping, the MCP-2026 content).
- Note it pairs with **AuthKit MCP** for secured agent access to design-system tooling
  — speaks leadership's language while the a11y depth speaks Chance's.
- It's literally the resume's thesis (ForgeKit) aimed at the library they own.

**MVP scope (ship small, sharp):**
1. MCP server: `list_primitives`, `get_primitive(name)` → props/types/a11y contract for
   ~5 primitives (start: Dialog, Tooltip, Select, DropdownMenu, Popover).
2. Source-of-truth = the primitives' own TS types + a hand-authored a11y-contract layer.
3. Tight README + a 60-sec build-in-public post (X/LinkedIn): "taught my coding agent
   the Radix a11y contract." Tag nobody; be useful.

**How to present (ranked):**
- Build-in-public post → organic, recruiter-findable artifact.
- Optionally open a Radix **GitHub Discussion** proposing it (gauge maintainer interest
  before over-investing). Do NOT cold-DM Chance about it.
- Reference in the cold email / InMail: "shipped a small Radix MCP last week: [link]."

**Concrete example — what an agent gets back:**

Agent (Claude Code / Cursor) is wiring a tooltip and calls the MCP:
```
tool: get_primitive
args: { "name": "Tooltip" }
```
Returns (the a11y-contract layer is the part nobody else ships):
```jsonc
{
  "name": "Tooltip",
  "import": "import { Tooltip } from 'radix-ui';",
  "parts": ["Provider", "Root", "Trigger", "Portal", "Content", "Arrow"],
  "props": {
    "Root": {
      "open?": "boolean",
      "defaultOpen?": "boolean",
      "onOpenChange?": "(open: boolean) => void",
      "delayDuration?": "number = 700",
      "disableHoverableContent?": "boolean"
    },
    "Provider": { "delayDuration?": "number = 700", "skipDelayDuration?": "number = 300" }
  },
  "a11y_contract": {
    "role": "Content renders role=tooltip; Trigger gets aria-describedby when open",
    "keyboard": [
      "Tab/Shift+Tab: focus the trigger → opens instantly (no delay)",
      "Escape: closes the open tooltip"
    ],
    "focus": "Opens on trigger focus AND pointer hover; closes on blur/leave. A tooltip is NOT a label — never put essential info only in a tooltip.",
    "requires": "Tooltip.Provider must wrap the app (or a subtree) once.",
    "common_mistakes": [
      "Using Tooltip for interactive content (use Popover/HoverCard instead)",
      "Wrapping a disabled button directly — disabled elements don't fire focus/hover; wrap in a span",
      "Omitting Tooltip.Provider → delay/skip behavior silently breaks"
    ]
  },
  "correct_example": "<Tooltip.Provider>\n  <Tooltip.Root>\n    <Tooltip.Trigger asChild><button>Save</button></Tooltip.Trigger>\n    <Tooltip.Portal>\n      <Tooltip.Content sideOffset={4}>Save your changes<Tooltip.Arrow /></Tooltip.Content>\n    </Tooltip.Portal>\n  </Tooltip.Root>\n</Tooltip.Provider>",
  "source": "radix-ui/primitives@latest · types + maintained a11y notes"
}
```
The payoff line for the post / outreach: *"My coding agent stopped hallucinating Radix
props — and now it knows a tooltip isn't a label."* That single example sells it: props
from source (accurate) + the a11y contract + misuse guardrails an LLM otherwise gets
wrong. Exactly the WorkOS thesis (frontend quality = product) in agent form.

**Status:** ✅ BUILT + COMMITTED. `forgekit-radix-mcp` v0.1.0 at
`~/Documents/GitHub/forgekit-v2/packages/radix-mcp` (committed 8c66c99 on branch
clean-n-update, scoped). Tools: list_primitives, get_primitive, get_a11y_contract.
**26 primitives** with full a11y contracts. 6/6 tests, tsup build clean, stdio server
verified live (26 listed).
Not yet (YOUR steps): `npm publish` → then post (Channel 8 below).

### CHANNEL 8 — Build-in-public post — ✅ READY TO FIRE
npm LIVE: https://www.npmjs.com/package/forgekit-radix-mcp (v0.1.0). Repo:
https://github.com/effinrich/forgekit-radix-mcp. Links below are final. Tag nobody —
be useful. Post on X + LinkedIn; reference it later in the WorkOS loop.

**X / Twitter:**
> AI agents hallucinate Radix props and skip the ARIA contract.
>
> So I built an MCP server that gives Claude/Cursor each primitive's parts, props, and
> a11y contract — keyboard, focus, and the misuse to avoid (a tooltip isn't a label).
>
> 26 primitives. MIT. 👇
> https://www.npmjs.com/package/forgekit-radix-mcp

**LinkedIn:**
> Coding agents are great at Radix — until they aren't. They hallucinate props, drop
> required parts, and miss the a11y contract (a Tooltip used as a label, a Select with
> an empty-string item value).
>
> Props you can infer from types. The accessibility contract you can't — it's
> hand-authored. So I built **forgekit-radix-mcp**: an MCP server that hands AI coding
> agents each Radix primitive's parts, props, and — the part nobody ships — its a11y
> contract: roles, keyboard, focus, and the mistakes to avoid.
>
> 26 primitives. Now an agent wiring a Dialog knows Title is required for the accessible
> name, and that a Tooltip isn't where essential content goes.
>
> MIT, part of ForgeKit. https://www.npmjs.com/package/forgekit-radix-mcp
>
> #accessibility #react #radixui #ai #mcp

## History
- 2026-06-13 — created. Resume already submitted via Ashby. All outreach drafted.
  Blocked on: recruiter/talent email (Channels 2,4,5), your network contacts (3).
- 2026-06-13 — tooltip PR (#1800) in progress (fork: effinrich/primitives,
  branch fix/tooltip-window-refocus). Razzle-dazzle Radix MCP suggestion drafted (Ch.7).
- 2026-06-13 — ✅ PR OPENED: https://github.com/radix-ui/primitives/pull/3964
  fix(tooltip): don't reopen on window/tab refocus. Local: 7/7 tests, typecheck+lint clean.
  Next: watch for @chaance review; reference the PR in cold email/InMail once recruiter found.
