# Skill: ai-tell-check

**Job:** Read the resume as a recruiter hunting for AI-written text. Nothing else.
**Reads:** the rendered resume text only, plus `_shared/voice.md`. Must not read stages 01–03.
**Writes:** the AI-tell section of `04_review.md`.

## Steps
1. Rate 1 (clearly human) to 10 (clearly AI). Target ≤ 4.
2. Quote every line that reads machine-written and say why (banned word, slogan, rule of three,
   identical bullet shapes, punchline endings, summary restating bullets).
3. Quote what reads human (odd specific numbers, trade detail, honest losses).
4. Propose a rewrite for each flagged line using only facts already on the page.
