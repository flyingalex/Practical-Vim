### 68. Append Commands to a Macro

`:reg {register}` can check what content in the register.

Sometimes you forget a command when record a macro,you can record it again by the Upper char.For example, `qa{command}q` record the macro in `a`,then you can use `qA{new command}a` to append commmands to the `a` macro.
