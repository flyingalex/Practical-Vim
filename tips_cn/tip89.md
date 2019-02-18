### 89. Eyeball Each Substitution

See the command.
> :[range]s[ubstitute]/{pattern}/{string}/[flags]

You just need to add `c` in the `[flags]` part,then every time when you want to execute the replacement,you will get the info like this in the command part:

```
y/n/a/q/l/^E/^Y
```

|Trigger | Effect|
|--------|-------|
|y| Substitute this match|
|n| Skip this match|
|q| Quit substituting|
|l| "last"—Substitute this match, then quit|
|a| "all"-Substitute this and any remaining matches|
|<C-e>| Scroll the screen up |
|<C-y>| Scroll the screen down|
