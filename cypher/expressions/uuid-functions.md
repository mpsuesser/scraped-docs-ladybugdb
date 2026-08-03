---
url: https://raw.githubusercontent.com/LadybugDB/ladybug-docs/main/src/content/docs/cypher/expressions/uuid-functions.md
title: "Uuid Functions"
description: ""
access_date: 2026-08-03T17:27:27.470Z
current_date: 2026-08-03T17:27:27.470Z
---

UUID functions are used to create Universally Unique Identifiers (UUIDs).

<div class="scroll-table">

| Function                | Description      | Example     | Result |
| ----------- | ----------- | ----------- | ----------- |
| `UUID(string)` | creates a UUID object from a string | `UUID('{a0eebc99-9c0b-4ef8-bb6d-6bb9bd380a11}')` | `a0eebc99-9c0b-4ef8-bb6d-6bb9bd380a11` |
| `gen_random_uuid()` | creates a random UUID object | `gen_random_uuid()` | `a0eebc99-9c0b-4ef8-bb6d-6bb9bd380a11` (or similar) |

</div>
