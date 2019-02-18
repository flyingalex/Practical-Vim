### 96. Find and Replace Across Multiple Files

We need a [plugin](https://github.com/nelstrom/vim-qargs) for this.

An examle in the book,replace `Pragmatic` with `Practical` in all the project files:
```
/Pragmatic\ze Vim
:vimgrep /<C-r>// **/*.txt
:Qargs
:argdo %s//Practical/g
:argdo update
```

`vimgrep` will put all the matched file into the quickfix list.
`Qargs` will put all files in the quickfix list into the arguments list.
