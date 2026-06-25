# Prompt: Research Note Extraction

Use this prompt after you have opened a source and confirmed that it is safe to process.

```text
You are helping me create an evidence-aware research note from one source.

Source status:
- I have opened the original source: [yes/no]
- Source type: [peer-reviewed paper / report / policy / dataset / other]
- Sensitivity: [public / de-identified / confidential - do not process]

My research question:
[insert question]

Task:
Create a structured research note using the template below.

Rules:
1. Do not invent citation details, methods, sample, findings, page numbers, or quotes.
2. If the source does not provide an item, write "Not found in provided source."
3. Separate evidence from inference.
4. For each important claim, provide an evidence anchor: page, section, table, figure, paragraph, or short quote if available.
5. Mark uncertain items as NOT_CHECKED.
6. Do not write final essay prose.

Template:
- Full citation or known metadata:
- Source status:
- Research question or practical problem:
- Context and setting:
- Data and method:
- Key concepts or theory:
- Main findings:
- Boundary conditions:
- Limitations:
- Practical implications:
- Evidence anchors:
- Questions for follow-up:
- What I should verify manually:
```
