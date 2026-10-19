# Gear Research Writing Workspace

A workspace for English journal manuscripts in gear dynamics, dynamic contact,
multiphysics coupling, thermal lubrication, and surface texturing. Microsoft Word
(`.docx`) is the primary manuscript format.

## Layout

- `manuscripts/`: source manuscripts and separately named revised copies.
- `references/`: verified reference metadata, authorized PDFs, and journal guidelines.
- `data/`: original data and documented derived datasets; preserve originals.
- `figures/`: reproducible scripts, generated figures, and captions.
- `reviews/`: scientific reviews, edit logs, and responses to reviewers.
- `.agents/skills/`: reusable writing, revision, review, and figure workflows.

Ask Codex to use a skill by name, for example:

- “Use nature-writing to outline an English paper on textured gear lubrication.”
- “Use nature-polishing to revise manuscripts/draft.docx and record substantive changes.”
- “Use nature-reviewer to critique the contact and thermal coupling assumptions.”
- “Use nature-figure to plot my supplied data and export publication figures.”

Install the working tools with `python -m pip install -r requirements.txt`.
Run `python scripts/check_environment.py` to check Word round-trip handling and
scientific plotting. This smoke check does not validate a manuscript or numerical model.
No background service or API credential is required for these local workflows.

## Word workflow

Keep the original file. Write revisions to a new `.docx` file and maintain an edit
log. Automated Word processing can alter complex objects; inspect equations,
fields, citations, references, headers, and embedded figures in Word before submission.
Plain-text replacement does not constitute native Word Track Changes.

Skills guide available tools; they do not independently provide literature search,
commercial solvers, image generation, journal access, or experimental results.
Add target-journal instructions when available. Do not upload confidential or
restricted material unless authorized to use it in this environment.

## Imported Nature Skills

All 22 callable upstream Nature Skills and their shared support package are
installed under `.agents/skills/`. The previous four local skills have been
replaced by the corresponding Nature Skills above. See
[import provenance and replacement map](third_party/nature-skills/README.md).
Use `nature-response` for reviewer replies, `nature-academic-search` for
literature discovery, and `nature-ref-verifier` for reference verification.
These optional workflows require their own available tools/access; they are not
all runtime-configured by the import. The proposal-writing skill is invoked as
`researchwrite`. Follow the exact target journal rather than assuming Nature rules.
