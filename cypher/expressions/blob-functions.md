---
url: https://raw.githubusercontent.com/LadybugDB/ladybug-docs/main/src/content/docs/cypher/expressions/blob-functions.md
title: "Blob Functions"
description: "Blob functions are used to create and manipulate blob data."
access_date: 2026-08-03T18:55:54.420Z
current_date: 2026-08-03T18:55:54.420Z
---

:::note[Note]
Scroll to the right to see the full table.
:::

<div class="scroll-table">

| Function | Description | Example | Result |
| ----------- | --------------- | ----------- | ----------- |
| `BLOB(string)` | creates a BLOB object using string | `blob('\xAA\xBD')` | `'\xAA\xBD'` |
| `encode(string)` | converts the given string to blob. UTF-8 characters are converted using literal encoding | `encode('this 中文')` | `'this \xE4\xB8\xAD\xE6\x96\x87'` |
| `decode(blob)` | converts the given blob to string. Throws an exception if blob is not a valid UTF-8 string | `decode('this \xE4\xB8\xAD\xE6\x96\x87')` | `'this 中文'` |
| `octet_length(blob)` | returns the number of bytes of the given blob object | `octet_length('\xAA\xDE\xAD')` | `3` |

</div>
