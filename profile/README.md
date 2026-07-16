# Data System School

**Mechanistic understanding first — then the production judgment it unlocks.**

> [!NOTE]
> **🚧 Under active development.** We're actively building the curriculum toward a public launch in the coming months. Watch this org to follow along — stay tuned.

AI can write your SQL, suggest indexes, and sketch architectures. But when the query is slow in production, the pipeline silently drops data, or an architecture decision locks you into years of tech debt — AI can't own that. You can — but only once you understand how these systems actually work underneath, not just how to call them. Data System School builds that mechanistic understanding first, then the judgment that rests on it, across two programs.

## Data Systems Foundations

**The core program**

> **Build the mechanistic understanding that production judgment depends on.**

Learn how data systems actually work — measure them, build their core mechanisms, and dissect ones you've never seen. It's a hands-on lab course: nine phases plus a final project, from measurement and query plans through storage, transactions, OLAP, distributed systems, streaming, and the lakehouse. Every phase runs the same loop — **Predict → Observe → Isolate → Build → Compare → Transfer**. Intuition first, rigor second.

- **Start from concepts and intuition.** Each phase opens with notes that build the mental model first — the mechanisms and trade-offs, not a tools tour.
- **Learn by playing, not just reading.** Every phase ships an interactive playground that makes its core trade-off measurable — poke it, run the guided experiments, watch the numbers move.
- **Run experiments on real systems.** DuckDB, Postgres, SQLite, Kafka, CockroachDB — compared within their category, because the deltas are where the learning lives.
- **Build toy versions to internalize.** A query engine, storage engine, transaction manager, distributed KV, stream processor, table format, and RAG pipeline — each grown one concept at a time.
- **See it in the wild.** Every phase ends with a real-world case study — Discord's messages table crossing three storage engines, GitHub's 43-second partition, the Databricks–Snowflake benchmark war — a named company hitting the phase's trade-off, with every claim sourced.
- **Finish with a system autopsy.** Dissect a data system you've never used, and back every claim with an experiment.

Foundations runs in a one-click dev container with automated grading and a personal course site for every learner.

## Production Systems Judgment

**The advanced program — coming**

Apply those models where the job actually gets hard: incomplete evidence, contradictory signals, cross-layer failures, and high-risk production changes — migrations, rollouts, rollbacks, incidents. The question shifts from *why does this system behave this way?* to *which mechanism is causing this, right now?* For senior engineers and Foundations graduates.

## Open resources

Free and interactive, no signup:

| Project | What it is |
|---------|------------|
| [Data Systems Timeline](https://data-system-school.github.io/data-system-timeline/) | A visual chronology of data-system breakthroughs from the 1960s to 2026 — the people, papers, and systems, and the concrete problem each one solved. |
| [Blackwell, Decoded](https://data-system-school.github.io/nv-blackwell-arch-decoded/) | A plain-spoken, interactive course on NVIDIA's Blackwell architecture — the chips, engines, and rack-scale systems built for the age of AI reasoning. |
| [Inference Infrastructure, Animated](https://data-system-school.github.io/inference-infrastructure-animated-tutorials/) | Eleven animated modules, from a single attention head to a production serving stack — play, pause, and step through every concept. |
