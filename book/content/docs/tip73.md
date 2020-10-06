---
title: 73. Use the \v Pattern Switch for Regex Searches
type: docs
weight: 73
---

### 73. Use the \v Pattern Switch for Regex Searches

When you use regex search, you can put `\v` before the pattern, so you don't need to transfer the special char in the pattern,no backslash make it more readable, right?

No `\v`
```
/#\([0-9a-fA-F]\{6}\|[0-9a-fA-F]\{3}\)
```

Include`\v`
```
/\v#([0-9a-fA-F]{6}|[0-9a-fA-F]{3})
```
