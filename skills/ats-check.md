# Skill: ats-check

**Job:** Check machine readability and keyword coverage. Nothing else.
**Reads:** rendered resume text, `00_posting.md`, `_shared/ats.md`. Calls `extract-keywords.md`.
**Writes:** the ATS section of `04_review.md`.

## Steps
1. Run `extract-keywords.md` in stage-04 mode: Present / Variant / Missing for each keyword.
2. Coverage = Present ÷ total high-weight keywords. Target ≥ 70%, but never by adding untrue keywords.
3. Check every "Don't" in `ats.md`.
4. List Missing keywords Tobi could truthfully claim → these become gap questions, not edits.
