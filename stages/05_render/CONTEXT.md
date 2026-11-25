# Stage 05 — Render and export

## Inputs
- This run: `03_draft.md` (post-review)
- Standing: `_shared/template/`, `_shared/layout.md`, `_shared/ats.md`
- Do not load: fact bank, voice, other applications

## Process
1. Run `skills/render-pages.md`.
2. Tobi exports the PDF (desktop app preferred).
3. Run `skills/export-check.md` on the PDF.
4. Fix and re-export until clean.

## Output
`applications/<run>/05_render/` with page1/page2 sources, the final PDF, and `notes.md`
(export check results, ATS checker result, date sent, where sent).

## Check
Tobi approves the final PDF.
