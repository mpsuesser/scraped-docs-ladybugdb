---
url: https://raw.githubusercontent.com/LadybugDB/ladybug-docs/main/src/content/docs/cypher/expressions/struct-functions.md
title: "Struct Functions"
description: ""
access_date: 2026-08-03T17:27:27.470Z
current_date: 2026-08-03T17:27:27.470Z
---

`STRUCT`s are commonly known as dictionaries, mappings, or key-value pairs. The key is a `STRING` and the value can be any data type. The following operators work on `STRUCT`s:

<div class="scroll-table">

| Operator | Description | Example | Result |
| ----------- | ----------- |  ----------- |  ----------- |
| `{key:value,}` | Creates a struct of key-value pairs | `{name: 'Alice', age: 20}` | `{NAME: Alice, AGE: 20}` |
| `struct.field_name` | Alias of struct_extract | `{name: 'Alice', age: 20}.name` | `'Alice'` |

</div>

The functions that can be used with structs are as follows:

<div class="scroll-table">

| Function | Description | Example | Result |
| ----------- | ----------- |  ----------- |  ----------- |
| `struct_extract(struct, 'field_name')` | Extracts named field from struct | `struct_extract({name: 'Alice', age: 20}, 'name')` | `'Alice'` |

</div>
