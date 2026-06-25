# 06. Agent Workflow Design

Agent tools can work across multiple steps. Use them only after the task has clear boundaries.

## A simple agent mental model

An agentic workflow usually includes:

- Goal.
- Context.
- Tools.
- Permissions.
- Memory or working notes.
- Checkpoints.
- Stop condition.
- Independent verification.

## Workflow

1. Define the task outcome.
2. Define what the agent may read.
3. Define what the agent may change.
4. Define what requires approval.
5. Define how the output will be checked.
6. Run on a small example first.
7. Review before using the result.

For research tasks, use the v2 sequence:

```text
source pack -> research note -> evidence anchors -> independent audit -> writing/action
```

For Codex or Claude Code, ask the agent to read:

- `AGENTS.md`
- `CLAUDE.md`
- `docs/student-research-workflow.md`
- The workflow file relevant to the task

## Good agent tasks

- Turn a folder of notes into a structured summary.
- Check whether a draft follows a rubric.
- Prepare a literature triage table from provided sources.
- Clean a non-sensitive CSV and report issues.
- Convert checked sources into research notes with evidence anchors.
- Audit a claim-evidence matrix for unsupported claims.

## Bad agent tasks

- Submit work without review.
- Invent missing data.
- Handle confidential data without permission.
- Make consequential decisions without a human checkpoint.
- Cite sources the student has not opened.
- Treat an AI-generated bibliography as verified.

## Minimum agent instruction

```text
Use this repository as a verification-first academic workflow kit.
Do not invent citations, page numbers, quotes, data, or claims.
Keep source status and support status visible.
Ask before changing, publishing, sending, or using sensitive data.
Return what I must verify manually.
```

## HeXie link

Xie provides the workflow and constraints. He provides judgment, ethics, and final responsibility.
