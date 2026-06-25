# Workflow: Source Pack to Research Note

Use this workflow when you have several papers, policies, reports, or readings and want to turn them into usable research notes.

## Inputs

- Source files or links.
- A research question.
- `templates/source-pack-manifest.md`.
- `templates/management-research-note.md`.
- `prompts/research-note-extraction.md`.

## Output

One evidence-aware note per source.

## Steps

1. Build the source manifest.
   - Record title, author, year, source type, link, access status, and sensitivity.
   - Mark each source as `opened_full_text`, `metadata_only`, `secondary_summary`, or `not_checked`.

2. Remove unsafe material.
   - Do not upload personal identifiers, HR records, health data, confidential company material, or unauthorized interview transcripts.
   - Use public, synthetic, or properly de-identified material.

3. Extract one note at a time.
   - Use `prompts/research-note-extraction.md`.
   - Do not ask AI to synthesize across all sources before individual notes are reliable.

4. Add evidence anchors.
   - For important findings, record page, section, table, figure, or short quote.
   - If the source does not support the claim, mark it.

5. Run an independent audit.
   - Use `prompts/independent-source-audit.md`.
   - Ask the AI to review the note against the source without trying to improve the prose first.

6. Revise or discard weak claims.
   - Keep `SUPPORTED`.
   - Rewrite or qualify `PARTIAL`.
   - Remove `UNSUPPORTED` and `CONTRADICTED`.

## Stop condition

The workflow is complete only when every claim you plan to use has a source and support status.

## Common failure modes

- Treating abstracts as full evidence.
- Letting AI invent missing methods, samples, or citations.
- Using a secondary summary as if it were the original source.
- Keeping claims marked `NOT_CHECKED`.
- Uploading sensitive data to a personal AI tool.
