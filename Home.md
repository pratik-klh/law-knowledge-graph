# Home

Law school knowledge vault.

## Subjects
- [[Civil Procedure]]: Federal civil procedure (PJ, SMJ, venue, Erie, pleadings, joinder, discovery, summary judgment)

## How this vault is organized

| Folder | What goes there |
|---|---|
| `00 Inbox` | Quick captures and unsorted notes. Process them into a subject later. |
| `01 Raw Sources/<Subject>/` | Original `.docx` / `.pdf` files (outlines, class notes, readings). Never edited, only referenced. |
| `02 Subjects/<Subject>/` | The knowledge graph, made of small linked Markdown notes. |
| `03 Templates` | Note templates (Case, Concept, Rule/Statute, Framework). |
| `99 Attachments` | Images and diagrams embedded in notes. |

### Inside each subject folder
```
02 Subjects/<Subject>/
├── <Subject>.md        ← Map of Content (MOC): start here
├── Topics/             ← hub notes, one per major unit (e.g., Personal Jurisdiction)
├── Concepts/           ← one doctrine/idea per note (e.g., Minimum Contacts)
├── Cases/              ← one case per note (facts, issue, holding, significance)
├── Rules & Statutes/   ← FRCP rules, U.S.C. sections, constitutional provisions
└── Frameworks/         ← step-by-step exam analysis checklists and flowcharts
```

### Linking conventions
- Every note has frontmatter: `type`, `subject`, `topic`, `aliases`, `tags`, `source`.
- Tags: `#civpro` plus a type tag like `#civpro/case`, `#civpro/concept`, `#civpro/statute`, `#civpro/framework`, `#civpro/topic`.
- Abbreviations are aliases, so `[[PJ]]`, `[[SMJ]]`, `[[FQJ]]`, `[[Rule 12(b)(6)]]` all resolve.
- Cases link to the concepts they establish. Concepts link back to their leading cases.

## Adding a new raw file
1. Drop the `.docx` into `01 Raw Sources/<Subject>/`.
2. Ask Claude to break it down into the subject folder, following the same structure and templates.
3. Check the **Graph view** (filter by `tag:#civpro` etc.) to see how it connects.
