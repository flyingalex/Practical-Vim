### 94. Perform Arithmetic on the Replacement

An example in the book,downgrade the number of `h` element:
```html
<h2>Heading number 1</h2>
<h3>Number 2 heading</h3>
<h4>Another heading</h4>
```

Command one:
> /\v\<\/?h\zs\d
This command will match the number in the `h` element.

> :%s//\=submatch(0)-1/g
This command,`//` match last used pattern,`submatch(0)` will get the value of match.
