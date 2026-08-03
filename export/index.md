---
url: https://raw.githubusercontent.com/LadybugDB/ladybug-docs/main/src/content/docs/export/index.mdx
title: "Export data"
description: "Export query results from Ladybug to CSV, Parquet, and JSON file formats using the COPY TO command."
access_date: 2026-08-03T18:23:42.333Z
current_date: 2026-08-03T18:23:42.333Z
---

import { LinkCard } from '@astrojs/starlight/components';

The `COPY TO` command allows you to export query results directly to the specified file format. This
is useful when you want to persist the results of a query to be used in other systems, or for
archiving purposes.

## `COPY TO` CSV

<LinkCard
  title="Export CSV"
  href="/export/csv"
/>

## `COPY TO` Parquet

<LinkCard
  title="Export Parquet"
  href="/export/parquet"
/>

## `COPY TO` JSON

<LinkCard
  title="Export JSON"
  href="/export/json"
/>
