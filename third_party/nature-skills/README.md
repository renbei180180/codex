# Nature Skills import

Source: https://github.com/Yuan1z0825/nature-skills

Upstream commit: `233ed09957d32d8cf45dd96c495663c5c5d8e447`

The complete upstream `skills/` tree is copied byte-for-byte into
`.agents/skills/`: 22 callable skills plus `nature-shared`. Upstream license
and embedded attribution/license files are retained. See LICENSE and each
skill's embedded notices for applicable terms. Local workspace guidance remains
in the root AGENTS.md and references/domain-checklist.md.

Replacement map:

| Previous skill | Replacement |
| --- | --- |
| paper-writing | nature-writing |
| paper-revision | nature-polishing |
| scientific-review | nature-reviewer; nature-response for rebuttals |
| research-figures | nature-figure |

`nature-proposal-writer` is invoked as `researchwrite` in upstream metadata.
`nature-shared` supports the other skills and is not a standalone workflow.
`files.sha256.json` records imported-file SHA-256 hashes for integrity checks.

## Runtime scope

Importing these skills does not configure all their optional runtimes. Local Word
and Python plotting tools remain available. Literature retrieval, institutional
browser access, Zotero, external MCP servers, image-generation providers, R,
Office rendering and other optional integrations must be checked when needed.
Do not send manuscripts or data to external services without user authorization.
Do not assume Nature-specific requirements apply to a mechanics journal.
