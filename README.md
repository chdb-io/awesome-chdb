# Awesome chDB

A curated list of [chDB](https://github.com/chdb-io/chdb) resources — language bindings, frameworks, integrations, notebooks, talks, and benchmarks.

chDB is an in-process OLAP SQL engine powered by ClickHouse, embedded as a Python / Bun / Node.js / Go / Rust / C library. It runs ClickHouse's full SQL dialect with 1000+ functions, queries Parquet / CSV / JSON files in place, references DataFrames directly in SQL via the `Python(df)` table function, and federates to remote ClickHouse clusters with `remoteSecure()` — all without spinning up a server.

> Status: this list is being seeded. More entries will be added incrementally. PRs welcome — see [Contributing](#contributing).

## Contents

- [Language bindings](#language-bindings)
- [Frameworks and agent integrations](#frameworks-and-agent-integrations)
- [Notebooks and tutorials](#notebooks-and-tutorials)
- [Talks and articles](#talks-and-articles)
- [Benchmarks](#benchmarks)
- [Contributing](#contributing)

## Language bindings

- [chdb (Python)](https://github.com/chdb-io/chdb) — the primary chDB library.
- [chdb-go](https://github.com/chdb-io/chdb-go) — Go bindings and CLI.
- [chdb-bun](https://github.com/chdb-io/chdb-bun) — Bun runtime bindings.
- [chdb-node](https://github.com/chdb-io/chdb-node) — Node.js native bindings.
- [chdb-rust](https://github.com/chdb-io/chdb-rust) — Rust FFI binding.
- [chdb-ruby](https://github.com/chdb-io/chdb-ruby) — Ruby library with SQLite3-compatible API.
- [chdb-zig](https://github.com/chdb-io/chdb-zig) — Zig wrapper.
- [chdb-dotnet](https://github.com/chdb-io/chdb-dotnet) — experimental .NET binding.
- [chdb-java](https://github.com/chdb-io/chdb-java) — Java binding.

## Frameworks and agent integrations

- [chdb-mcp](https://github.com/chdb-io/chdb-mcp) — chDB as a Model Context Protocol server for Claude, Cursor, ChatGPT, and other agent clients.
- [langchain-chdb](https://github.com/chdb-io/langchain-chdb) — LangChain provider with vector store, document loader, and agent toolkit.
- [chdb-sqlalchemy](https://github.com/chdb-io/chdb-sqlalchemy) — SQLAlchemy dialect for ORM stacks and `SQLDatabaseToolkit`.
- [chdb-superset](https://github.com/chdb-io/chdb-superset) — Apache Superset demo with chDB as the backend.
- [chdb-lambda](https://github.com/chdb-io/chdb-lambda) — AWS Lambda container template.

## Notebooks and tutorials

- [chDB cookbook](https://github.com/chdb-io/cookbook) — runnable notebooks for agent, analytics, and ML patterns.
- [chDB demos](https://github.com/chdb-io/chdb/tree/main/examples) — TPC-H, MovieLens DNN, vector search, Hugging Face Parquet, and more.
- [Getting Started Tutorial (Hex)](https://app.hex.tech/partnerships/app/chDB-Tutorial-032XsQ4qoKtlXxcw49joav/latest) — first-class chDB integration walkthrough.

## Talks and articles

- [chDB 4.0: pandas-compatible DataStore + Hex partnership](https://clickhouse.com/blog/chdb.4-0-pandas-hex) — "Write Pandas, run ClickHouse, ship from Hex" (2026-03).
- [chDB's journey to zero-copy](https://clickhouse.com/blog/chdb-journey-to-zero-copy) — end-to-end zero-copy via SIMD→NumPy (2026-01).
- [Analyzing Wimbledon 2025 with chDB](https://clickhouse.com/blog/analyzing-wimbledon-2025-chdb) — point-by-point tennis analytics by Mark Needham (2025-07).
- [chDB v2: pandas DataFrames 87× faster](https://clickhouse.com/blog/chdb-pandas-dataframes-87x-faster) — Native Python table engine deep-dive (2024-08).
- [chDB review by Anton Zhiyanov](https://antonz.org/chdb/) — "It's as if SQLite and ClickHouse had an offspring" (2023-12).
- [chDB: an embedded ClickHouse — rocket engine on a bicycle](https://clickhouse.com/blog/chdb-embedded-clickhouse-rocket-engine-on-a-bicycle) — origin story by Auxten (2023-09).

## Benchmarks

- [ClickBench — embedded engines dashboard](https://benchmark.clickhouse.com/) — chDB vs DuckDB vs DataFusion vs ClickHouse-local.
- [DataFrame benchmark — chDB / Pandas / DuckDB / Polars](https://benchmark.clickhouse.com/) — analytical workload comparison.

## Contributing

Open a PR adding your entry to the matching category. Each entry should be a single line: `- [Title](URL) — short description`. New categories accepted when there are at least three resources to populate them.

## License

This list is published under [CC0-1.0](LICENSE). Linked projects retain their own licenses.

## Related

- chDB documentation: https://clickhouse.com/docs/chdb
- LLM-friendly index: https://clickhouse.com/docs/chdb/llms.txt
- Community: https://discord.gg/D2Daa2fM5K
- Twitter / X: [@chdb_io](https://twitter.com/chdb_io)

### Awesome lists featuring chDB

- [samber/awesome-olap](https://github.com/samber/awesome-olap) — curated OLAP databases, data lake tools, and columnar engines.
- [vinta/awesome-python](https://github.com/vinta/awesome-python) — curated Python frameworks, libraries, and resources.
