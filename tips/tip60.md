### 60. Grok Vim’s Registers

`"{register}` can specify which register you want to use.

`""` is unnamed register.

`"0` is copy register for `y{motion}`.

`"a – "z` is named register.

`"_` is black hole register,which won't save operation.

`"+` can get the content from system clipboard.

`"*` can put things into the system clipboard.

`"=` register can use to do some computation.

|Register | Contents|
|---------|---------|
|`"%` | Name of the current file |
|`"#` | Name of the alternate file| 
|`".` | Last inserted text|
|`":` | Last Ex command|
|`"/` | Last search pattern|

