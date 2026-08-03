---
url: https://raw.githubusercontent.com/LadybugDB/ladybug-docs/main/src/content/docs/cypher/expressions/list-operators.md
title: "List Operators"
description: ""
access_date: 2026-08-03T17:27:27.470Z
current_date: 2026-08-03T17:27:27.470Z
---

The following table shows the operators that can be used with lists.

<div class="scroll-table">

| Operator | Description | Example | Result |
| :----------- | ----------- |  ----------- |  ----------- |
| `+` | concatenates two lists | `RETURN [1,2,3] + [4,5] AS mylist` | `[1,2,3,4,5]` |
| `[start:stop]` | access specific elements in a list | `WITH [1,2,3,4,5] AS mylist RETURN mylist[1:3]` | `[1,2]` |
| `IN` | operator for the `list_contains` function | `1 IN [1,2,3]` | `true` |

</div>
