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

- “Use paper-writing to outline an English paper on textured gear lubrication.”
- “Use paper-revision to revise manuscripts/draft.docx and record substantive changes.”
- “Use scientific-review to critique the contact and thermal coupling assumptions.”
- “Use research-figures to plot my supplied data and export publication figures.”

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
