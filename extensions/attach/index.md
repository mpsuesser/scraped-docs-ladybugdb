---
url: https://raw.githubusercontent.com/LadybugDB/ladybug-docs/main/src/content/docs/extensions/attach/index.mdx
title: "Tabular data sources"
description: "Attach to external databases and data sources including PostgreSQL, DuckDB, SQLite, Delta Lake, and Iceberg tables."
access_date: 2026-08-03T19:40:03.494Z
current_date: 2026-08-03T19:40:03.494Z
---

import { Tabs, TabItem } from '@astrojs/starlight/components';

Ladybug supports attaching to the following types of tabular data sources and databases:

- [External Ladybug databases](lbug.md): Attach to an external Ladybug database
(possibly on a remote file system) and query that database in **read-only** mode via Cypher.
- [PostgreSQL](postgres.md): Attach to PostgreSQL databases.
- [DuckDB](duckdb.md): Attach to DuckDB databases.
- [SQLite](sqlite.md): Attach to SQLite databases.
- [Iceberg](iceberg.md): Attach to Iceberg tables.
- [Delta Lake](delta.md): Attach to Delta Lake tables.
- [Unity Catalog](unity.md): Attach to Delta Lake tables in a [Unity Catalog](https://www.databricks.com/product/unity-catalog).
