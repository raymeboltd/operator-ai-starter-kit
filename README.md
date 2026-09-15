# Operator AI Starter Kit

Build the smallest AI system that solves a real operating problem.

You may need a database, semantic search, and specialized agents. You may also
need five Markdown files and a reliable weekly review. Start with the second
option. Add architecture only when a measured constraint earns it.

## Start here

1. Copy the files in [`01-files`](01-files/) into a private working folder.
2. Complete [`02-decide/workflow-inventory.md`](02-decide/workflow-inventory.md)
   for one recurring workflow.
3. Use [`02-decide/architecture-chooser.md`](02-decide/architecture-chooser.md)
   to choose the smallest operating mode.
4. Define success with [`03-verify/verification-card.md`](03-verify/verification-card.md).
5. Run the workflow manually three times before increasing autonomy.

## The architecture ladder

| Level | Use it when | Do not move up yet when |
|---|---|---|
| Markdown | A small team can maintain the truth and exact search finds it | The problem is unclear or the files are simply disorganized |
| Structured database | Concurrent writes, permissions, relationships, or reporting are real constraints | One owner still controls a small body of context |
| Semantic retrieval | Users need meaning-based discovery across a larger unstructured corpus | Exact search and good navigation still answer the questions |
| Bounded agent | A recurring workflow has tools, a measurable outcome, an evaluator, and an escalation path | Success is subjective or failures are expensive and hard to reverse |

The ladder is reversible. Moving down is often an improvement.

## Five files before five agents

- `RULES.md`: boundaries, permissions, and stop conditions.
- `CONTEXT.md`: the business, customer, priorities, and vocabulary.
- `VOICE.md`: how public and internal writing should sound.
- `PLAYBOOK.md`: the approved steps for one recurring workflow.
- `TOOLS.md`: available systems, allowed actions, and manual handoffs.

These files are templates, not a claim that every company should organize itself
the same way. Delete what does not help.

## Definition of done

An assistant saying “done” is not evidence. Verify the destination state:

- Did the record change in the real system?
- Is the output complete and within the stated constraints?
- Can a reviewer identify the source and reproduce the result?
- Is there an owner when the workflow fails?

## Research behind the decisions

- [Anthropic: Building effective agents](https://www.anthropic.com/engineering/building-effective-agents)
- [Anthropic: Demystifying evals for AI agents](https://www.anthropic.com/engineering/demystifying-evals-for-ai-agents)
- [NIST AI Risk Management Framework](https://airc.nist.gov/airmf-resources/airmf/5-sec-core/)
- [Model Context Protocol specification](https://modelcontextprotocol.io/specification/draft/server/index)
- [pgvector documentation](https://github.com/pgvector/pgvector)
- [METR developer productivity study](https://metr.org/Early_2025_AI_Experienced_OS_Devs_Study-paper.pdf)

## What this is

An original, practical starter kit for owners and operators. It does not include
private company data, customer material, paid-course content, or a universal stack.

