# Method — how this repo is built

Based on Interpretable Context Methodology (ICM): Van Clief & McDermott, arXiv 2603.16021,
github.com/RinDig/Interpretable-Context-Methodology. Same conventions as THuebbe/benchbuilt-ops.

## The idea in brief
- Folders are the agent architecture. One agent reads different files for different jobs.
- AGENTS.md only routes. CLAUDE.md just points to it, so any AI reads the same file.
- Five layers: AGENTS.md (where am I) → root CONTEXT.md (where do I go) → stage CONTEXT.md
  (what do I do) → `_shared/` references (rules that never change) → `applications/` (this run).
- Every stage has a contract: Inputs (this run + standing references + do-not-load list),
  Process (numbered steps), Outputs, and exactly one Check.
- Every stage ends in a file a person can open and edit. Nothing moves on until the Check passes.
- Factory vs. product: `_shared/` and `skills/` are the factory; `applications/` is the product.
- One home per fact. Link, don't copy. A fact about Tobi lives only in `_shared/fact-bank.md`.
- Don't over-structure. Add a stage or skill only after a job repeats.

## Our additions
1. **Skills folder.** Single-purpose procedures (`skills/*.md`) that stages call by name. A skill
   does one job and says what it reads and writes. Reused skills (keywords) live once.
2. **Precedence file.** When rules conflict: truth > human readability > ATS > coach style.
3. **Decision log.** `decisions/` records why, with dates, so settled questions stay settled.
4. **Fact status tags.** Every fact-bank line carries [verified], [approx] or [confirm].
5. **Blind review.** Stage 04 must run in a fresh agent/session that has not seen stages 01–03.
6. **MM-DD-YYYY in content.** ISO dates only in file and folder names.

## Extending
- New rule about wording/format → the owning `_shared/` file + a `decisions/` entry.
- New repeated task → a new `skills/` file, then reference it from the stage contract.
- When a correction is made during a run, fix the source file too, not just the output.
- Old runs that no longer matter → `_archive/`.
