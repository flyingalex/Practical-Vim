### 53. Mark Your Place and Snap Back to It 

>m{a-zA-Z}

`m` and another char can use to mark the current cursor position,then you can ``{mark}` go back to that line wherever you are.

vim also provide some automatic mark.

|Keystrokes | Buffer Contents|
|-----------|----------------|
|`` | Position before the last jump within current file |
|`. | Location of last change|
|`^ | Location of last insertion|
|`[ | Start of last change or yank|
|`] | End of last change or yank|
|`< | Start of last visual selection|
|`> | End of last visual selection|

 I think that i won't use them at any time, hahaha, it's too difficult to remember them.
