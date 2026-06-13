# Job Hunt Outreach Workbench

A personal, single-user system for running targeted job-search outreach — emailing
the actual humans (hiring managers, founders, team members) at places you want to
work, with a real hook for each one, and never losing track of who you've contacted
or who owes a reply.

It is **not** a cold-email blaster and not a product. It's a *workbench*: a small,
stable set of files that hold the state of your hunt, plus a defined way that Claude
operates on them with you each session. The files are the memory; Claude is the operator.

---

## The mental model

> You point Claude at this folder. Claude reads `SESSION.md` and `pipeline.md`,
> tells you where things stand, and you work the next move together. At the end,
> Claude writes the state back. Next time, you pick up in two minutes, not twenty.

There is no app to run, nothing to deploy, no login. Just text files in a repo.
That's deliberate — it's what makes the hunt *resumable* and *yours*.

## Why there's no UI (the "intuitive UX" is the pattern)

The product feel doesn't come from a screen. It comes from three things being
rigidly consistent, so the system is predictable no matter when you return:

1. **One dashboard.** `pipeline.md` is the home screen — every contact and their
   status in one table. Glance at it, know everything.
2. **One shape for everything.** Every person lives in `contacts/<name>.md` with the
   *same sections in the same order*. Open any one, it feels familiar.
3. **One vocabulary.** A short, fixed set of status words (below). No ambiguity about
   what state anything is in.
4. **One ritual.** Every session starts and ends the same way (see `SESSION.md`).

Consistency is the UX.

---

## File map

```
jobhunt/
├── README.md          ← you are here (the manual)
├── SESSION.md         ← the start/end ritual + running session log
├── pipeline.md        ← THE DASHBOARD: every contact + status, one table
├── you/
│   ├── profile.md     ← who you are, what you want, your voice  (fill this first)
│   └── resume.md      ← your experience, as raw material for hooks
├── contacts/
│   ├── _TEMPLATE.md   ← the canonical shape every contact file copies
│   └── *.md           ← one file per person you're reaching out to
└── voice.md           ← how your emails should sound + structural skeletons
```

## Status vocabulary (the only words that mean "where is this")

| Status            | Meaning                                                        |
|-------------------|----------------------------------------------------------------|
| `researching`     | Identified the target, still gathering the hook                |
| `drafted`         | Email written, sitting in this repo, not yet in Gmail          |
| `in-gmail`        | Draft pushed to your Gmail Drafts folder, awaiting your Send    |
| `sent`            | You sent it                                                    |
| `replied`         | They responded — your move                                     |
| `follow-up-due`   | No reply yet; time for a polite second touch                   |
| `closed-won`      | Led somewhere good (call, intro, interview)                    |
| `closed-no`       | Dead end / explicit no                                          |
| `closed-ghost`    | Multiple touches, silence — archived                           |

## How sending works in this setup

Claude writes the email into the contact file, you approve the text, and Claude
creates it as a **draft in your Gmail** (status → `in-gmail`). You open Gmail, give
it a final read, and hit Send (status → `sent`). The final click is always yours.

---

## First-time setup (5 minutes, once)

1. Fill in `you/profile.md` — what you're looking for, your story, your constraints.
2. Paste your resume content into `you/resume.md`.
3. Tweak `voice.md` if the default tone isn't you.
4. Start a session: tell Claude *"let's work the job hunt"* and add your first
   target(s). Claude takes it from there.
