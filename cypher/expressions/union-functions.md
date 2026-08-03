---
url: https://raw.githubusercontent.com/LadybugDB/ladybug-docs/main/src/content/docs/cypher/expressions/union-functions.md
title: "Union functions"
description: "Union functions are used to perform unions on values."
access_date: 2026-08-03T19:01:51.636Z
current_date: 2026-08-03T19:01:51.636Z
---

Union functions are used to perform unions on values.

| Function | Description | Example | Result |
| ----------- | ----------- |  ----------- |  ----------- |
| `union_value(tag := value)` | create a union with given value | `union_value(a := 1)` | `1` |
| `union_tag(union)` | return the tag of union | `union_tag(union_value(a := 1))` | `a` |
| `union_extract(union, tag)` | return the value for given tag | `union_extract(union_value(a := 1), 'a')` | `1` |
