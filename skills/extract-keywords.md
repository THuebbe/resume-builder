# Skill: extract-keywords

**Job:** Pull the exact phrases an ATS keyword match would look for. Nothing else.
**Reads:** `00_posting.md` (stage 01) or the posting + rendered resume text (stage 04).
**Writes:** the Keywords section of `01_intake.md`, or the coverage table in `04_review.md`.

## Steps
1. List noun phrases and skills as written: job titles, tools (e.g. "CRM", "Prophet 21"),
   product/industry terms ("thermal management", "power transmission"), methods ("account planning").
2. Rank by weight: appears in title or first paragraph (high) → repeated 2+ times (high) →
   in requirements (medium) → in company boilerplate (low).
3. Keep the posting's exact spelling and form. Add common variants in parentheses
   ("Prophet 21 (P21)").
4. Drop soft filler ("team player", "detail oriented", "fast-paced") unless it's the only signal.
5. In stage 04 mode: mark each keyword Present / Variant present / Missing in the resume text.

## Output format
Ranked list, 15–30 items: `keyword — weight — where it appears`.
