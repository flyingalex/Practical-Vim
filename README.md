#PracticalVim

I read the book *[Practical Vim: Edit Text at the Speed of Thought](https://www.amazon.com/Practical-Vim-Edit-Speed-Thought/dp/1680501275/ref=sr_1_1?ie=UTF8&qid=1488958924&sr=8-1&keywords=practical-vim)*, it's pretty awesome! so I want to do a note for this book.I will write all the skills in this article relared to the book.

Please read this article first [Seven habits of effective text editing](http://www.moolenaar.net/habits.html),which is very good for editor using.

The beginner tutorial for vim, run command `vimtutor` in your terminal(install vim fisrt if you don't have this command) and have a fun.

You also can find the [中文](https://github.com/flyingalex/PracticalVim/blob/master/Chinese.md) version

#121 tips

- [x] [1.Meet the Dot Command](#meet-the-dot-command)
- [x] [2.Don't Repeat Yourself](#don't-repeat-yourself)
- [x] [3.Take One Step Back, Then Three Forward](#3.take-one-step-back-then-three-forward)
- [x] [4.Act,Repear,Reverse](#act-repear-reverse)
- [x] [5.Find and Replace by Hand](#find-and-replace-by-hand)
- [x] [6.Meet the Dot Formula](#meet-the-dot-formula)

###1.Meet the Dot Command

`.` means repeat the last change.When you do delete,move,or replace, if you want to do the last operation again, you can just press `.`.You also can use it to repeat the operation like this:Press the `i` become the INSERT MODE, do some modification, then switch the MODE to NORMAL MODE, all the operations between the two modes can use `.` to repeat.Pretty Awesome, isn't it?

###2.Don't Repeat Yourself

Some keys can do many things:

1.Don't use `c$`
> C, Delete from the cursor position to the end of the line.

2.Don't use `cl`
> s, Delete [count] characters [into register x] and start insert (s stands for Substitute).

3.Don't use `^s`
> S, Delete [count] lines [into register x] and start insert.

4.Don't use `^i`
> I, Insert text before the first non-blank in the line [count] times.

5.Don't use `$a`
>A, Append text at the end of the line [count] times.

6.Don't use `A<Enter>`
>o, Begin a new line below the cursor and insert text, repeat [count] times.

7.Don't use `ko`
>O, Begin a new line above the cursor and insert text, repeat [count] times.

###3.Take One Step Back, Then Three Forward

If you want to add space around a operator in several places,you can just do all things only one time, after that, use `;` to move and `.` to repeat the change which was done in the first time.

###4.Act, Repear, Reverse

Edition means change and move all the time.If we can just do them one time,and then repeat them,it will be very effective.But sometimes we also will make a mistake when we repeat them, so undo a operation is very important.Vim provide some operations for this.

| Purpose | Operation | Repeatation | Reverse |
|-----------------------------------|-----------------------|---|---|
|Make a change 						| {edit} 				| . | u |
|Scan line for next character		| f{char} / t{char} 	| ;	| , |
|Scan line for previous character	| F{char} / T{char} 	| ;	| , |
|Scan document for next match		| /pattern <CR> 		| n | N | 
|Scan document for previous match	| ?pattern <CR> 		| n | N |
|Perform substitution				| :s/target/replacement | & | u |
|Execute a sequence of changes 		| qx{changes}q 			| @x| u |

###5.Find and Replace by hand

If you want to replace some in all the matched words.You can press `*` above the word which you want to replace, it will help you to find all the words in the current file, then you can replace it, then you can press `n` go to next word, if some matched words you don't want to change, just press `n`.Remember use `.` after you first change.

###6.Meet the Dot Formula

Use one key to move and one key to operation.


