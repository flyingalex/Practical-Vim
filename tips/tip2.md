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
