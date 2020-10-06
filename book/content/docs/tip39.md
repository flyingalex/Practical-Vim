---
title: 39. Divide Your Workspace into Split Windows
type: docs
weight: 39
---

### 39. Divide Your Workspace into Split Windows

|Command | Effect|
|--------|-------|
|`<C-w>s` | Split the current window horizontally, reusing the current buffer in the new window |
|`<C-w>v` | Split the current window vertically, reusing the current buffer in the new window |
|`:sp[lit]` {file} | Split the current window horizontally, loading {file} into the new window|
|`:vsp[lit]` {file} | Split the current window vertically, loading {file} into the new window |
|`<C-w>w` | Cycle between open windows|
|`<C-w>h` | Focus the window to the left|
|`<C-w>j` | Focus the window below|
|`<C-w>k` | Focus the window above|
|`<C-w>l` | Focus the window to the right|
|`<C-w>=` | Equalize width and height of all windows|
|`<C-w>_` | Maximize height of the active window|
|`<C-w>|` | Maximize width of the active window|
|`[N]<C-w>_` | Set active window height to [N] rows|
|`[N]<C-w>|` | Set active window width to [N] columns|


|Ex Command | Normal Command  | Effect|
|-----------|-----------------|-------|
|`:cl[ose]` | `<C-w>c` | Close the active window|
|`:on[ly]` | `<C-w>o`  | Keep only the active window, closing all others|
