# Skill: export-check

**Job:** Inspect the exported PDF before it's sent. Nothing else.
**Reads:** the exported PDF. **Writes:** the Export section of `05_render/notes.md`.

## Steps
1. Render each page to an image and look at it.
2. Check: 2 pages; body text at the intended size (not enlarged); nothing clipped at the bottom of
   page 1; page 2 65–85% full; no lone words on last lines; no heading stranded at a page bottom.
3. Extract the text (pdftotext) and confirm reading order: name → contact → title bar → sections.
4. Note the ATS checker result if Tobi ran one.
5. If text renders oversized, export from desktop, not phone.
