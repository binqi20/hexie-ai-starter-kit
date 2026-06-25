# Evidence Anchor Guide

An evidence anchor is a short, checkable link between a claim and the source that supports it.

It can be:

- A page number.
- A section heading.
- A table or figure number.
- A paragraph location.
- A short quote.
- A dataset column and row definition.

## Why anchors matter

AI can produce fluent summaries that sound correct. In academic work, sounding correct is not enough. A useful claim must be traceable.

Evidence anchors help you:

- Avoid hallucinated citations.
- Detect overclaiming.
- Separate evidence from inference.
- Improve writing with stronger support.
- Explain your AI use responsibly.

## Good anchors

| Claim | Good anchor |
|---|---|
| The study uses interviews with family business successors. | Page 8, Methods section, "Data collection" paragraph. |
| The intervention was not tested on patient outcomes. | Limitations section, final paragraph. |
| The variable is employee engagement, not job satisfaction. | Table 2, variable definitions. |

## Weak anchors

| Weak anchor | Problem |
|---|---|
| "The paper says this." | Not checkable. |
| AI summary only. | Not the original source. |
| A citation that has not been opened. | Citation may be fake, irrelevant, or misread. |
| A quote without page, section, or context. | Hard to verify later. |

## Anchor discipline

For every important claim, fill:

1. Claim.
2. Source.
3. Anchor location.
4. Short evidence or quote.
5. Support status.
6. Human check completed: yes or no.

If you cannot fill the anchor, do not use the claim as a final claim.

## Short quote rule

Use short quotes only when they help verification. Do not paste long copyrighted passages into AI tools or documents. Prefer page, section, table, and concise paraphrase when possible.

## AI prompt for anchors

Use:

```text
For each claim below, identify the exact source location needed to verify it. If the provided material does not contain support, mark the claim as NOT_CHECKED or UNSUPPORTED. Do not invent page numbers, quotes, or citations.
```
