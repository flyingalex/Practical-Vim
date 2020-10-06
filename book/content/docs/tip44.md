---
title: 44. Save Files to Nonexistent Directories
type: docs
weight: 44
---

### 44. Save Files to Nonexistent Directories

For example, you open a file by `:e madeup/test.md`, but the `madeup` directory doesn't exists, you will get error like `Can't open file for writing`, because you don't have the `madeup`.What should i do?Fortunately, you can run `:!mkdir -p %:h` first to create the directory, then `:w` can works well.
