---
url: https://raw.githubusercontent.com/LadybugDB/ladybug-docs/main/src/content/docs/cypher/expressions/comparison-operators.md
title: "Comparison Operators"
description: ""
access_date: 2026-08-03T17:27:27.470Z
current_date: 2026-08-03T17:27:27.470Z
---

The following table describes the standard comparison operators supported by Ladybug. If any of the input arguments is `NULL`, the comparison result will also be `NULL`.

<div class="scroll-table">

| Operator | Description | Example | Result |
| ----------- | ----------- | ----------- | ----------- |
| `<` | less than | `2 < 3` | `true` |
| `>` | greater than | `1 > 5` | `false` |
| `<=` | less than or equal to | `3 <= 3` | `true` |
| `>=` | greater than or equal to | `4 >= 2` | `true` |
| `=` | equal | `NULL = NULL` | `NULL` |
| `<>` | not equal | `5 <> NULL` | `NULL` |

</div>
