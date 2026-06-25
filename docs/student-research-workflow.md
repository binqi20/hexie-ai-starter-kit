# Student Research Workflow

This guide turns a loose AI chat into a small academic workflow.

The logic is adapted from Dr. Binqi Tang's public `management-research-notes` workflow, but simplified for student use:

1. Build a source pack.
2. Extract one evidence-backed research note per source.
3. Attach evidence anchors to important claims.
4. Run an independent audit pass.
5. Synthesize only checked claims into writing or action.

This toolkit does not validate your work automatically. It gives you habits, prompts, and templates that make verification easier.

## The five-stage workflow

| Stage | What the student does | What AI can help with | Human responsibility |
|---|---|---|---|
| Source pack | Collect papers, policies, datasets, notes, or readings. | Organize files and create a manifest. | Decide relevance, access rights, and data safety. |
| Research note | Create one structured note per source. | Extract question, method, findings, limits, implications. | Check the note against the source. |
| Evidence anchors | Link claims to page numbers, sections, tables, or short quotes. | Suggest anchors and missing evidence. | Open the source and confirm each anchor. |
| Independent audit | Review support status claim by claim. | Mark supported, partial, unsupported, contradicted, or not checked. | Resolve weak claims before using them. |
| Writing/action | Draft a memo, report, presentation, or decision note. | Improve structure, clarity, comparison, and tone. | Own the final argument and citation trail. |

## Source status labels

Use these labels in every source pack.

| Label | Meaning | Allowed use |
|---|---|---|
| `opened_full_text` | You have opened and can read the original source. | Strongest basis for notes and citations. |
| `metadata_only` | You have title, authors, abstract, DOI, or catalogue data, but not full text. | Useful for triage only. |
| `secondary_summary` | You are using a blog, news story, video, or AI summary about the source. | Do not cite as if it were the original source. |
| `not_checked` | You have not verified the source yet. | Do not use for final claims. |

## Support status labels

Use these labels in audits and claim-evidence matrices.

| Label | Meaning |
|---|---|
| `SUPPORTED` | The claim is directly supported by the source. |
| `PARTIAL` | The claim is directionally supported but needs nuance or narrower wording. |
| `UNSUPPORTED` | The source does not support the claim. Remove or rewrite it. |
| `CONTRADICTED` | The source says the opposite or conflicts with the claim. Do not use it. |
| `NOT_CHECKED` | The claim has not yet been verified. Do not rely on it. |

## Minimum viable research sprint

Use this when you have 45 to 60 minutes.

1. Pick one question.
2. Add five candidate sources to `templates/source-pack-manifest.md`.
3. Choose two sources to read closely.
4. Create two notes with `templates/management-research-note.md`.
5. Fill one `templates/claim-evidence-matrix.md`.
6. Run `prompts/independent-source-audit.md`.
7. Rewrite the conclusion using only `SUPPORTED` or carefully qualified `PARTIAL` claims.

## HeXie logic

- Xie: manifest, note template, evidence anchors, audit table, disclosure log.
- He: research question, interpretation, ethical boundaries, final argument.
- Coupling: use AI to make the workflow more disciplined, not to remove responsibility.
