---
title: 87. Meet the Substitute Command]
type: docs
weight: 87
---

### 87. Meet the Substitute Command]

```
:[range]s[ubstitute]/{pattern}/{string}/[flags]
```

> The substitute command allows us to find and replace one chunk of text with another.

Some `flags` show below:

> 1.The g flag makes the substitute command act globally.

> 2.The c flag gives us the opportunity to confirm or reject each change.

> 3.The n flag suppresses the usual substitute behavior.

> 4.The & flag simply tells Vim to reuse the same flags from the previous substitute command.


Some special chars in the `pattern`

|Symbol | Represents|
|-------|-----------|
|\r|Insert a carriage return|
|\t|Insert a tab character|
|`\\`|Insert a tab character|
|\1|Insert the first submatch|
|\2|Insert the second submatch (and so on, up to \9)|
|\0|Insert the entire matched pattern|
|&|Insert the entire matched pattern|
|~|Use {string} from the previous invocation of :substitute|
|\={Vim script}|Evaluate {Vim script} expression; use result as replacement {string}|
