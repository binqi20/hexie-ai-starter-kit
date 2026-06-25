# HeXie AI Starter Toolkit

A student-facing AI workflow kit for postgraduate study, research, and early professional work.

Created for the **HeXie Management Student Inspiring Lab**:

**Coupling Human and Digital Intelligence: A HeXie Approach to AI in Study and Work**

## Core idea

AI is not mainly a prompt-writing problem. It is a workflow and accountability problem.

Use this repository to couple:

- **He**: human judgment, ethics, interpretation, final claims, and responsibility.
- **Xie**: tools, templates, source packs, prompts, checklists, and review loops.

Do not use the toolkit to outsource your thinking. Use it to make your thinking more structured, evidence-aware, and verifiable.

## What changed in v2

This is no longer just a prompt kit. It is a small student version of a research workflow harness inspired by Dr. Binqi Tang's public [`management-research-notes`](https://github.com/binqi20/management-research-notes) project.

The transferable workflow is:

```text
source pack -> research note -> evidence anchors -> independent audit -> writing/action
```

The full `management-research-notes` repository contains production scripts and validators. This student toolkit does not copy that complexity. It keeps the useful habits: source status, evidence anchors, support labels, independent audit, and AI-use disclosure.

## Start here

1. Open [`START_HERE.md`](START_HERE.md).
2. Choose a workflow:
   - Learning or study: `toolkit/`
   - Research workflow: `docs/` and `workflows/`
   - Agent tools such as Codex or Claude Code: `AGENTS.md` and `CLAUDE.md`
3. Copy one prompt from `prompts/`.
4. Use the relevant template from `templates/`.
5. Verify every important claim against the original source.

## Repository map

| Folder or file | Purpose |
|---|---|
| `START_HERE.md` | 10-minute onboarding. |
| `AGENTS.md` | Instructions for Codex or other agentic tools. |
| `CLAUDE.md` | Instructions for Claude Code or Claude-style workflows. |
| `docs/` | Research workflow guidance and evidence-anchor discipline. |
| `workflows/` | Source-pack, literature-map, and evidence-backed writing workflows. |
| `toolkit/` | Short guides for learning, literature, reading, writing, data, and agents. |
| `prompts/` | Copy-ready prompts for student tasks. |
| `templates/` | Manifests, notes, matrices, checklists, audit reports, and disclosure logs. |
| `examples/pathways/` | GIS, SHR, and SAH example use cases. |
| `examples/non-sensitive-survey.csv` | Small practice dataset. |

## Academic integrity

Follow your module, programme, and university rules. When in doubt, ask your instructor what is allowed.

Safe uses usually include explanation, brainstorming, outline feedback, source comparison, writing critique, and data checking. Risky uses include submitting AI-generated work as your own, inventing citations, hiding AI use when disclosure is required, or uploading sensitive data to personal AI accounts.

## Data safety

Do not upload:

- Personal identifiers.
- Employee records.
- Patient or health data.
- Confidential company data.
- Unpublished interview transcripts without permission.
- Any dataset you are not authorized to share with the AI provider.

Use synthetic, public, or properly de-identified data for practice.

## Default verification habit

Before you trust an AI output, ask:

1. What source supports this claim?
2. Did I open the original source?
3. Is the citation real and relevant?
4. Is the evidence direct, partial, missing, or contradicted?
5. Are the assumptions stated?
6. What would change my conclusion?

## Use with an AI agent

Ask Codex, Claude Code, ChatGPT, or another AI tool:

```text
Read START_HERE.md and AGENTS.md. Help me use this repository on one non-sensitive study or research task. Keep source status, evidence anchors, and independent verification visible.
```

## License

This teaching toolkit is licensed under CC BY 4.0. See [`LICENSE`](LICENSE).
