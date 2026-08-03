---
url: https://raw.githubusercontent.com/LadybugDB/ladybug-docs/main/src/content/docs/cypher/expressions/list-operators.md
title: "List Functions"
description: "List functions are used to create and manipulate lists."
access_date: 2026-08-03T19:40:03.494Z
current_date: 2026-08-03T19:40:03.494Z
---

The following table shows the operators that can be used with lists.

<div class="scroll-table">

| Operator | Description | Example | Result |
| :----------- | ----------- |  ----------- |  ----------- |
| `+` | concatenates two lists | `RETURN [1,2,3] + [4,5] AS mylist` | `[1,2,3,4,5]` |
| `[start:stop]` | access specific elements in a list | `WITH [1,2,3,4,5] AS mylist RETURN mylist[1:3]` | `[1,2]` |
| `IN` | operator for the `list_contains` function | `1 IN [1,2,3]` | `true` |

</div>
