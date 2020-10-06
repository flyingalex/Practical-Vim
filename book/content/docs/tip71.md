---
title: 71. Edit the Contents of a Macro
type: docs
weight: 71
---

### 71. Edit the Contents of a Macro

If you want to edit the content in the register,you can use `:put {register}` to put the content into the vim,then edit it,finally `0"{register}y$dd` can put it back to the register. 
