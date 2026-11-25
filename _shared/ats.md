# ATS — keep it machine-readable

reviewed: 11-24-2026

## Do
- Single text flow. Text a parser can read top to bottom in the order a human reads it.
- Standard section names: Professional Summary, Areas of Expertise, Career Highlights,
  Professional Experience, Selected Projects, Technical Skills, Education and Training.
- Areas of Expertise as ONE paragraph, items separated by " | ". 12–16 items.
- Job header line: **Title**, Company, *City, ST* | Month YYYY – Present.
- Months on every date ("April 2016"), or on none. Currently: on all.
- Export as a text-based PDF (selectable text), letter size.
- Keywords appear in the exact phrasing the posting uses, where truthful.

## Don't
- Column grids or tables for keywords (parsers read them in scrambled order).
- Icons, checkmark glyphs, photos, headshots, logos, text boxes.
- Graduation year (age bias), GPA, high school.
- Street address (city, state only), family status, salary expectations.
- Employment-type labels unless a short stint needs explaining.
- Explanations for gaps under a year.
- Jobs older than ~15–20 years (not an issue yet).

## Known risks we accept
- Name and contact info side by side in the header. Most ATS read it fine. For an unknown or
  older portal, use the stacked header fallback (see `layout.md`).

## How to check
Paste the PDF's text into a free ATS checker (Jobscan, Resume Worded). Sections must come out in
order and contact info must parse. Stage 05 records the result.
