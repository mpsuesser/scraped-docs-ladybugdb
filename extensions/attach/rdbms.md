---
url: https://raw.githubusercontent.com/LadybugDB/ladybug-docs/main/src/content/docs/extensions/attach/rdbms.mdx
title: "Attaching external RDBMS systems"
description: "Overview of relational database extensions for connecting to PostgreSQL, DuckDB, and SQLite databases."
access_date: 2026-08-03T19:40:03.494Z
current_date: 2026-08-03T19:40:03.494Z
---

import { CardGrid, LinkCard } from '@astrojs/starlight/components';

Ladybug supports directly scanning from a variety of relational databases using the `LOAD FROM` statement.
Because RDBMSs are a common source of structured data, Ladybug provides a set of 
extensions to allow users to both scan data from external RDBMSs without having to copy it
into Ladybug and also to simplify copying data from an external RDBMS into Ladybug.

The currently available relational database extensions are shown below:

Extension Name | Description | Minimum Version
:---:|:---:|:---:
[`adbc`](../adbc.md) | Scan from any ADBC-compatible database | 1.10.0
[`duckdb`](duckdb.md) | Scan from an attached DuckDB database | 0.10.0
[`postgres`](postgres.md) | Scan from an attached PostgreSQL database | 14.0
[`sqlite`](sqlite.md) | Scan from an attached SQLite database | 3.3.0

:::note[Note]
The `adbc` extension is a generic adapter that works with any database exposing an [ADBC driver](https://arrow.apache.org/adbc/). Prefer a dedicated extension (DuckDB, PostgreSQL, SQLite) when one is available, as dedicated extensions offer additional features such as arbitrary SQL pass-through via `SQL_QUERY`.
:::
