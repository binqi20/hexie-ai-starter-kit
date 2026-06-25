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

## Workflow

1. Define the task outcome.
2. Define what the agent may read.
3. Define what the agent may change.
4. Define what requires approval.
5. Define how the output will be checked.
6. Run on a small example first.
7. Review before using the result.

## Good agent tasks

- Turn a folder of notes into a structured summary.
- Check whether a draft follows a rubric.
- Prepare a literature triage table from provided sources.
- Clean a non-sensitive CSV and report issues.

## Bad agent tasks

- Submit work without review.
- Invent missing data.
- Handle confidential data without permission.
- Make consequential decisions without a human checkpoint.

## HeXie link

Xie provides the workflow and constraints. He provides judgment, ethics, and final responsibility.

