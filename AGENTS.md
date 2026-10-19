# Research workspace instructions

Write manuscript prose in academic English. Explain work to the user in Chinese
unless requested otherwise. Primary domains: mechanical engineering, gear dynamics,
dynamic gear contact, multiphysics coupling, thermal lubrication, surface texturing.
Primary deliverable: Microsoft Word `.docx`.

Read `references/domain-checklist.md` for domain-specific review criteria. Apply
relevant skills under `.agents/skills/` when their workflows fit the task.

Never fabricate references, DOI metadata, data, uncertainty, simulation results,
experimental validation, or novelty. Label unverified claims and missing evidence.
Use supplied evidence; separate observations, interpretations, and hypotheses.
Do not claim a literature search or full document inspection unless performed.

Preserve source documents and raw datasets. Write revised documents and derived
outputs to new filenames. Preserve units, symbols, reference numbering, equations,
and cross-references. Record substantive technical changes for user review.
Never silently change scientific meaning or replace equations with approximations.
Do not claim native tracked revisions unless the produced OOXML contains verified
revision markup. Report unreadable content and rendering limitations.

Do not place credentials in this repository. No remote submission, email, or journal
upload without explicit authorization. Use the existing isolated checkout; do not
create a Git worktree unless explicitly requested.

## Imported skills routing

The Nature Skills suite in `.agents/skills/` replaces the original four skills:
nature-writing for drafting, nature-polishing for revision, nature-reviewer for
mock peer review, nature-response for reviewer responses, and nature-figure for
figures. Keep the English/Word and mechanics-domain requirements above when
using these skills. Journal-specific Nature rules apply only when the target
journal or user request calls for them. Check optional tools and credentials
only when required by a selected task; importing does not configure integrations.
See third_party/nature-skills/README.md for provenance and the replacement map.
