### 69. Act Upon a Collection of Files

`args {files' name}` can open a arguments list and `argdo normal @{macro char}` can execute the macro in all files in the arguments list.Be careful!,before you run `argdo normal @{macro char}`, you should run `:edit!` first, which will exclude macro effect in the current file. You also can use the `{number}@{register}` to do this stuff,but in the macro,you should include `:next` at then end of macro.
