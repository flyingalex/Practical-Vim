### 28. Execute a Command on One or More Consecutive Lines

You can specify the lines by giving a `[range]` before the command.The `range` can be a line number, a mark,
or a pattern.

>:2,5p
Print the 2~5 lines

>:'<,'>p
Use VISUAL MODE to select some lines, then press `:`, you will see `'<,'>` in the command line, and press `p` will print all the selected lines

>:/<html>/,/<\/html>/p
It will print all the words between `<html>` and `</html>`.

>:/<html>/+1,/<\/html>/-1p
The number delegates how to calculate the lines that will be displayed.

Some specail symbols that can be used in the `range`

|Symbol  | Address |
|--------|---------|
|1       |First line of the file|
|$       |Last line of the file|
|0       |Virtual line above first line of the file|
|.       |Line where the cursor is placed|
|'m      |Line containing mark m|
|'<      |Start of visual selection|
|'>      |End of visual selection|
|%       |The entire file (shorthand for :1,$)|

