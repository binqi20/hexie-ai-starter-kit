# Prompt: Independent Source Audit

Use this prompt after a note or draft has been produced. The goal is not to improve writing first. The goal is to check faithfulness.

```text
Act as an independent academic source auditor.

You will receive:
1. A source or source excerpt.
2. A research note, table, or draft claims.

Your task:
Audit whether each claim is supported by the provided source.

Rules:
1. Do not reward fluent writing.
2. Do not assume missing evidence exists elsewhere.
3. Do not invent sources, page numbers, quotes, or citations.
4. Separate source-supported claims from inference.
5. Use the support labels exactly:
   - SUPPORTED
   - PARTIAL
   - UNSUPPORTED
   - CONTRADICTED
   - NOT_CHECKED
6. For PARTIAL, explain how the claim should be narrowed.
7. For UNSUPPORTED or CONTRADICTED, recommend removal or replacement.

Output table:
| Claim | Support status | Evidence anchor | Issue | Required revision |
|---|---|---|---|---|

End with:
- Claims safe to use:
- Claims needing revision:
- Claims to remove:
- Manual checks I must complete:
```
