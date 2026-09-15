# Architecture chooser

Answer in order. Stop as soon as one level solves the problem.

## 1. Can files solve it?

- Is the context small enough for a person to maintain?
- Is one owner responsible for changes?
- Can exact search or a clear index find the answer?
- Are permissions simple?

If yes, use Markdown. Run the workflow before adding infrastructure.

## 2. Has structured data earned its place?

Consider a database when you need concurrent writes, strict schemas, permissions,
relationships, transactions, or repeatable reporting. Do not add one because the
project “might scale.” Name the constraint it solves today.

## 3. Has semantic retrieval earned its place?

Test semantic retrieval when people ask conceptually similar questions using
different words and exact search misses useful material. Compare it against a simple
baseline. Measure answer quality, recall, latency, and maintenance cost.

## 4. Has an agent earned autonomy?

An agent needs:

- a recurring job;
- a defined outcome;
- bounded tools and permissions;
- an evaluator;
- a stop condition;
- an escalation owner;
- a destination receipt.

If one is missing, keep the workflow human-led or deterministic.

