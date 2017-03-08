#PracticalVim

I read the book *[Practical Vim: Edit Text at the Speed of Thought](https://www.amazon.com/Practical-Vim-Edit-Speed-Thought/dp/1680501275/ref=sr_1_1?ie=UTF8&qid=1488958924&sr=8-1&keywords=practical-vim)*, it's pretty awesome! so I want to do a note for this book.I will write all the skills in this article relared to the book.

Please read this article first [Seven habits of effective text editing](http://www.moolenaar.net/habits.html),which is very good for editor using.

The beginner tutorial for vim, run command `vimtutor` in your terminal(install vim fisrt if you don't have this command) and have a fun.

You also can find the [中文](https://github.com/flyingalex/PracticalVim/blob/master/Chinese.md) version

#121 tips

- [x] [1.Meet the Dot Command](#Meet-the-Dot-Command)
- [ ] 2.Don't Repeat Yourself
- [ ] 3.Take One Step Back, Then Three Forward
- [ ] 4.Act,Repear,Reverse
- [ ] 5.Find and Replace by Hand
- [ ] 6.Meet the Dot Formula

###1.Meet the Dot Command

`.` means repeat the last change.When you do delete,move,or replace, if you want to do the last operation again, you can just press `.`.You also can use it to repeat the operation like this:Press the `i` become the INSERT MODE, do some modification, then switch the MODE to NORMAL MODE, all the operations between the two modes can use `.` to repeat.Pretty Awesome, isn't it?
