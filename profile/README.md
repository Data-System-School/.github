# Data System School

**Modern data system, taught for the agent era.**

> [!NOTE]
> **🚧 Under active development.** We're actively building the curriculum toward a public launch in the coming months. Watch this org to follow along — stay tuned.

AI can write your SQL, suggest indexes, and sketch architectures. But when the query is slow in production, the pipeline silently drops data, or an architecture decision locks you into years of tech debt — AI can't own that. You can. Data System School builds the judgment to debug, verify, and make high-stakes decisions about databases, query engines, storage, and distributed data systems.

## The labs

The core curriculum is a hands-on lab course: nine phases plus a final project, from measurement and query plans through storage, transactions, OLAP, distributed systems, streaming, and the lakehouse. Intuition first, rigor second.

- **Start from concepts and intuition.** Each phase opens with notes that build the mental model first — the mechanisms and trade-offs, not a tools tour.
- **Learn by playing, not just reading.** Every phase ships an interactive playground that makes its core trade-off measurable — poke it, run the guided experiments, watch the numbers move.
- **Run experiments on real systems.** DuckDB, Postgres, SQLite, Kafka, CockroachDB — compared within their category, because the deltas are where the learning lives.
- **Build toy versions to internalize.** A query engine, storage engine, transaction manager, distributed KV, stream processor, table format, and RAG pipeline — each grown one concept at a time.
- **See it in the wild.** Every phase ends with a real-world case study — Discord's messages table crossing three storage engines, GitHub's 43-second partition, the Databricks–Snowflake benchmark war — a named company hitting the phase's trade-off, with every claim sourced.
- **Finish with a system autopsy.** Dissect a data system you've never used, and back every claim with an experiment.

Labs run in a one-click dev container with automated grading and a personal course site for every learner.

## Open resources

Free and interactive, no signup:

| Project | What it is |
|---------|------------|
| [Data Systems Timeline](https://data-system-school.github.io/data-system-timeline/) | A visual chronology of data-system breakthroughs from the 1960s to 2026 — the people, papers, and systems, and the concrete problem each one solved. |
| [Blackwell, Decoded](https://data-system-school.github.io/nv-blackwell-arch-decoded/) | A plain-spoken, interactive course on NVIDIA's Blackwell architecture — the chips, engines, and rack-scale systems built for the age of AI reasoning. |
| [Inference Infrastructure, Animated](https://data-system-school.github.io/inference-infrastructure-animated-tutorials/) | Eleven animated modules, from a single attention head to a production serving stack — play, pause, and step through every concept. |
