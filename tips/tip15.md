###15. Paste from a Register Without Leaving Insert Mode

First, use `y` copy some words into the copy register, then change the mode from NORMAL to INSERT mode, now you can use `<C-r>0` to paste the words in the copy register to the file, the command
`<C-r>0` may cause line break, you can use `<C-r><C-p>{register}`.
