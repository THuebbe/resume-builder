# AGENTS.md — start here

This repo turns a job posting into a tailored, two-page resume for Tobi Huebbe.
Any AI or person working here reads this file first. It only routes.

## Where am I?
- `_shared/` — rules and facts that never change between runs (the factory).
- `skills/` — single-purpose procedures. Each does one job. Stages call them.
- `stages/` — the five-stage pipeline. Each stage folder has a CONTEXT.md contract.
- `applications/` — one folder per posting (the product). Each run writes here.
- `decisions/` — why things were decided, so they don't get re-litigated.
- `_meta/method.md` — how this repo is built (ICM) and how to extend it.

## Where do I go for task X?
- New posting to apply for → `stages/01_intake/CONTEXT.md`, then follow the stages in order.
- Tobi gives a new fact, number or story → `skills/update-fact-bank.md`.
- A rule about wording, layout or ATS changes → edit the file in `_shared/` that owns it, then log it in `decisions/`.
- "Why is it done this way?" → `decisions/` first, then `_shared/precedence.md`.

## Non-negotiables (details live in `_shared/`)
1. Every claim traces to `_shared/fact-bank.md`. No fact, no claim. Gaps become questions for Tobi.
2. Employer is always "Standard Bearings." Never Weimer.
3. Customers are never named on a resume. Describe them ("a pork processor").
4. Truth > readability > ATS > coach style (`_shared/precedence.md`).
5. Nothing moves to the next stage until that stage's Check passes.
6. Human checkpoints: Tobi approves the go/no-go and gap answers (stage 02) and the final PDF (stage 05).

## Dates
Write dates in content as MM-DD-YYYY (resume dates as "Month YYYY"). ISO dates appear only in file and folder names.

## No secrets
No passwords, API keys or customer data beyond what `_shared/fact-bank.md` already holds.
