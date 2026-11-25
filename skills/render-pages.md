# Skill: render-pages

**Job:** Put the approved draft into the v2 template. Nothing else.
**Reads:** `03_draft.md` (as revised after review), `_shared/template/*`, `_shared/layout.md`.
**Writes:** `05_render/page1.dc.html`, `05_render/page2.dc.html`.

## Steps
1. Copy both template pages into the application's `05_render/`.
2. Replace text only. Keep every inline style, including explicit font-size on each element and
   the text-size-adjust rule in the head.
3. Escape `&` as `&amp;` in HTML.
4. Publish to the design canvas (one page per artboard, fixed Letter) or open locally to export.
5. Run `fit-layout.md` if anything overflows.
