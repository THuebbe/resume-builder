# Root CONTEXT — the pipeline at a glance

| Stage | Folder | Job | Output (in the application folder) | Human gate |
|---|---|---|---|---|
| 01 | `stages/01_intake` | Read the posting, pull requirements and keywords, call go/no-go | `01_intake.md` | Tobi confirms go |
| 02 | `stages/02_match` | Match requirements to the fact bank, list gaps, pick content | `02_match.md` | Tobi answers gaps |
| 03 | `stages/03_draft` | Write every resume section | `03_draft.md` | — |
| 04 | `stages/04_review` | Blind review by a fresh agent | `04_review.md` | — |
| 05 | `stages/05_render` | Fill the template, export, check the PDF | `05_render/` + PDF | Tobi approves PDF |

## Starting a run
1. Create `applications/YYYY-MM-DD-company-role/`.
2. Save the posting text verbatim as `00_posting.md` (with URL and date found).
3. Open `stages/01_intake/CONTEXT.md` and follow it.

## Shared references every stage may read
- `_shared/fact-bank.md` — the only source of facts about Tobi.
- `_shared/targets.md` — what jobs Tobi wants and his deal-breakers.
- `_shared/voice.md` — how the writing sounds and what it never does.
- `_shared/layout.md` — page plan, sections, fonts, colors.
- `_shared/ats.md` — what keeps the resume machine-readable.
- `_shared/precedence.md` — which rule wins in a conflict.
- `_shared/template/` — the approved v2 pages.

Each stage contract lists exactly which of these it loads. Don't load the rest.
