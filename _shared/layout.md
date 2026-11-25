# Layout — the v2 page plan

reviewed: 11-24-2026. Source of truth: `_shared/template/` (approved 11-24-2026).

## Pages
- Two US Letter pages, fixed (816 × 1056 px each), not one flowing document.
  Each page is its own artboard so the break is intentional.
- **Page 1:** header → title bar → rule → Professional Summary → Areas of Expertise →
  Career Highlights → Professional Experience with the ENTIRE current job.
- **Page 2:** running header ("TOBI HUEBBE … PAGE 2 OF 2") → Professional Experience, Continued
  (earlier roles) → Selected Projects (optional per posting) → Technical Skills → Education and Training.
- Target fill: page 1 ≈ 90–100%, page 2 ≈ 65–85%. Never pad page 2 with filler.

## Header
- Name left: Archivo 800, 44px, condensed (font-stretch 72%), uppercase.
- Contact right-aligned, two lines: "West Branch, IA | 319-499-2608" / "email | linkedin".
- Fallback for strict ATS: stacked header (name, then one contact line under it).
- Title bar under the header: two titles, IBM Plex Mono 13px semibold, uppercase, accent color,
  separated by " | ". Default: "Technical Sales Professional | Industrial Account Manager".
- 2px rule under the title bar.

## Section headings
- IBM Plex Mono 12.5px, 600 weight, letter-spacing 0.14em, uppercase, accent color,
  followed by a 1px rule that fills the rest of the line.

## Body
- Archivo 14px, line-height 1.45, color #1B1E22.
- Set font-size explicitly on every p/li/span (exporters may resize unset text).
- Include `-webkit-text-size-adjust:100%; text-size-adjust:100%` on html, body and * —
  phone exports enlarge long paragraphs without it.
- Job overview sentence: italic, #3A4048.
- Dates: IBM Plex Mono 12px, #4D545C, right-aligned on the job header line.
- Bullets: square markers, 18px indent, 5px gap.
- Career Highlights: 3 items, bold label with colon, then one or two lines.

## Color
- Accent: #1D4E89 (blue). Alternates allowed: #9A3B12 rust, #2F5D3A green, #1B1E22 black.
- Muted text: #4D545C. White background. No gradients, no shaded bars.

## Line-break hygiene
- No single word alone on a bullet's last line (rewrite the bullet shorter).
- No section heading at the bottom of a page.
