# Stage 04 — Blind review

Run this in a **fresh agent or session** that has not seen stages 01–03. The point is that the
work doesn't grade itself.

## Inputs
- This run: `00_posting.md`, `03_draft.md` (resume text only — strip the Fit note)
- Standing: `_shared/voice.md`, `_shared/ats.md`; `_shared/fact-bank.md` for truth-check only
- Do not load: `01_intake.md`, `02_match.md`, chat history

## Process
1. Run `skills/ai-tell-check.md`.
2. Run `skills/ats-check.md`.
3. Run `skills/recruiter-screen.md` (without the fact bank).
4. Run `skills/truth-check.md` (with the fact bank).

## Output
`applications/<run>/04_review.md` — four sections, then a combined fix list ranked by impact.

## Check
AI-tell score ≤ 4, truth-check has zero "Not found" or "stronger than the fact" items, and every
fix is either applied to `03_draft.md` or logged as a question for Tobi.
