# Stage 02 — Match

## Inputs
- This run: `01_intake.md`
- Standing: `_shared/fact-bank.md` (all), `_shared/layout.md` (Pages section only)
- Do not load: voice.md, ats.md, template/, other applications

## Process
1. Run `skills/match-facts.md`.
2. Run `skills/gap-questions.md`. Send the questions to Tobi.
3. When answers come back, run `skills/update-fact-bank.md` for each new fact.
4. Re-run `skills/match-facts.md` on items that changed.
5. Run `skills/select-content.md`.

## Output
`applications/<run>/02_match.md` with sections: Match table · Questions (with Tobi's answers) · Selection.

## Check
Every selected item cites a fact-bank ID tagged [verified] or [approx].
