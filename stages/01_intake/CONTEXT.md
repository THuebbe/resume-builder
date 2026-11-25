# Stage 01 — Intake

## Inputs
- This run: `applications/<run>/00_posting.md`
- Standing: `_shared/targets.md`, `_shared/fact-bank.md` (Snapshot section only)
- Do not load: voice.md, layout.md, ats.md, template/, other applications

## Process
1. Run `skills/extract-requirements.md`.
2. Run `skills/extract-keywords.md`.
3. Run `skills/go-no-go.md`.

## Output
`applications/<run>/01_intake.md` with sections: Go/No-go (first) · Requirements · Keywords.

## Check
Tobi has replied "go" (or "go with risks") to the Go/No-go. No reply = stop here.

## Authority
Reading and writing files in the run folder: go ahead. Applying, contacting anyone: never (Tobi only).
