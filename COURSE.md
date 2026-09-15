# AI 101 for Operators

A practical course for founders and business owners who want useful AI without
building an AI lab. The order matters: define the work, supply the right context,
choose the smallest architecture, and earn autonomy through verification.

## Part I: Make the work legible

### 1. The smallest setup that fits

Start with the lowest operating level that solves the current problem. Use the
[`architecture chooser`](02-decide/architecture-chooser.md) before selecting a
database, retrieval system, or agent.

### 2. Clarity before prompting

Write down the outcome, inputs, constraints, forbidden actions, and acceptance
criteria. Better wording cannot rescue an undefined job.

### 3. Context is an operating asset

Give the system current rules, priorities, vocabulary, sources of truth, and
escalation paths. More context is not automatically better context.

## Part II: Earn the architecture

### 4. When Markdown is enough

Use the templates in [`01-files`](01-files/) while a person can maintain the
truth and exact search or navigation still finds what the workflow needs.

### 5. When structured data earns its place

Add a database when concurrency, strict schemas, permissions, relationships,
transactions, or repeatable reporting become real constraints.

### 6. When semantic retrieval earns its place

Test semantic retrieval when people search by meaning and exact search misses
useful material. Compare answer quality, recall, latency, and maintenance cost
against the simpler baseline.

### 7. Tools, skills, workflows, and agents

Separate a single action from a reusable procedure, a deterministic sequence,
and an autonomous loop. Use the least autonomous form that completes the job.

## Part III: Automate responsibly

### 8. Map the process first

Complete the [`workflow inventory`](02-decide/workflow-inventory.md). Identify
the trigger, inputs, decisions, handoffs, outputs, and failure cost before adding
automation.

### 9. Automate, assist, or keep human-led

Automate repeatable work with clear rules and cheap verification. Use assistance
when judgment still matters. Keep sensitive, ambiguous, or expensive decisions
human-led.

### 10. Count verification time

Use the [`verification card`](03-verify/verification-card.md) to compare total
assisted time with the manual baseline. Fast generation is not the same as a
faster completed workflow.

### 11. Bound permissions and escalation

Define tools, authority, stop conditions, and an escalation owner before a
workflow runs. Start with the [`escalation matrix`](03-verify/escalation-matrix.md).

### 12. Keep the system current

Review the sources of truth, remove obsolete rules, record failures, and update
the playbook. A system trained on yesterday's business can execute yesterday's
mistakes very efficiently.

## Suggested pace

- Week 1: complete lessons 1–3 for one recurring workflow.
- Week 2: choose and test the smallest architecture in lessons 4–7.
- Week 3: map, classify, and measure the workflow with lessons 8–10.
- Week 4: add permissions, escalation, and a monthly maintenance review.

Do not advance because a week elapsed. Advance when the current level has a
measured limitation that the next level addresses.
