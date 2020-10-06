---
title: 29. Duplicate or Move Lines Using ‘:t’ and ‘:m’ Commands
type: docs
weight: 29
---

### 29. Duplicate or Move Lines Using ‘:t’ and ‘:m’ Commands

>:[range]copy {address}

You can `copy` command to copy lines

|Command |Effect|
|--------|------|
|:6t. |Copy line 6 to just below the current line|
|:t6 |Copy the current line to just below line 6|
|:t. |Duplicate the current line (similar to Normal mode yyp)|
|:t$ |Copy the current line to the end of the file|
|:'<,'>t0 |Copy the visually selected lines to the start of the file|

>:[range]move {address}

`move` or `m` can move the lines in the files, like the `copy`
