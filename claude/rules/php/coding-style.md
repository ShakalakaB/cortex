---
paths:
  - "**/*.php"
  - "**/composer.json"
---

# PHP Coding Style

---

> This file extends [coding-style.md](../coding-style.md) with PHP specific content.

## Eloquent Over Raw SQL

+ Prefer Eloquent queries over raw SQL. 
+ Prefer Eloquent relations over joins. 
+ Only use raw SQL or joins when Eloquent/Eloquent relations are not possible or would negatively impact performance.
