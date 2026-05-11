# app — Scaffold Stop (Confirmed)

**Status:** Stopped at Xcode default scaffold. No intent to develop further.
ContentView is intact — nothing to restore. This repo exists as a record,
not as a product in flight.

---

## What this repo is

A SwiftUI iOS app named `app`, created from the Xcode default template on
2026-02-09. No customization was ever made to the UI.

- `app/appApp.swift` — Xcode-generated `@main` entry point, unchanged.
- `app/ContentView.swift` — Xcode-generated boilerplate (globe + "Hello,
  world!"), unchanged.
- `app.xcodeproj/` — Xcode-generated project file.

The repository name and the on-disk location are both deliberately
generic. The location `/Users/d/Projects/Misc:NoGoPRJs/app` indicates
"miscellaneous, no-go projects" — i.e., the directory was always
intended as a parking lot for ideas that did not survive a first-pass
viability check.

---

## Why the portfolio operating system asked

The portfolio operating system surfaced a packet titled "restore
ContentView or confirm scaffold stop". The wording covers both
possible failure modes:

1. **ContentView was lost or deleted** — restore needed.
2. **No further development is planned** — scaffold stop confirmed.

This file documents that the answer is **(2)**. ContentView still
exists at `app/ContentView.swift` and reflects the original Xcode
template. There is nothing to restore.

---

## Why no further development

- No product hypothesis was committed to disk past the template.
- The repository name "app" is a placeholder; there is no business
  domain, no spec, no audience, no problem statement.
- Codex-OS scaffolding branches (`codex/chore/bootstrap-codex-os`,
  `codex/remediate-tests-docs-contracts-v1`) exist but were never
  merged. They added AGENTS.md and verify-command scaffolding only —
  no product code.
- Active iOS energy on the operator's portfolio is going to other
  iOS apps (Afterimage, Calibrate, Cartograph, Chromafield,
  GhostRoutes, Liminal, Nocturne, Redact, RoomTone, Seismoscope,
  Terroir, Wavelength).

Spending another session here would crowd out work on those apps for
no gain.

---

## Reactivation criteria

Re-open development only if all three of these are true at the same
time:

1. **A product hypothesis exists** — written down, one paragraph,
   answers "what does this app do for whom?"
2. **The hypothesis is not better served by an existing iOS project**
   in the portfolio. If it overlaps with any of the apps listed
   above, extend that app instead.
3. **The hypothesis is worth at least a 4-hour first session** — if
   it's smaller than that, build it as a feature inside an existing
   app rather than a standalone repo.

If all three are met, the first reactivation move is to rename the
repository from `app` to something descriptive. Until then, the
generic name is itself a signal that nothing has been chosen.

---

## What this stop does NOT mean

- Not archived in any formal sense — the repo stays on GitHub as a
  template artifact.
- Not deleted — local checkout remains for reference.
- Not a judgment of the Xcode template (template is fine; just not a
  product).

It just means: **stop returning to this row in portfolio reviews
expecting it to move.** It will not move until reactivation criteria
land.

---

## Notes for portfolio operating system

- Mark this row as `Cold Storage` with disposition
  `scaffold — no product hypothesis, intentionally stopped`.
- Stop counting overdue-review days against this row.
- Resurface only if a new packet explicitly references "the app at
  Misc:NoGoPRJs/app" with a defined product hypothesis attached.

---

## Last known state

| Field | Value |
|---|---|
| Last commit on `main` | `5bbe04f` Initial Commit (Xcode template) |
| iOS target SDK | (whatever Xcode 26.x default was on 2026-02-09) |
| UI surface | One SwiftUI screen, default globe + "Hello, world!" |
| Tests | None |
| CI | None |
| Codex-OS scaffolding | Present on `codex/*` branches, unmerged |
