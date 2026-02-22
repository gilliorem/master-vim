## PRACTICE MOVING

*IMPORTANT*
Before we start moving around, let's make our life easier by showing the line numbers
so Switch to command mode by pressing <shift-;> 
you shoud see your cursor on the last line in right after the `:` 
type 'set number'

Ahhh, isn't it better like that ?

- Follow the `_` and `|` and cross out the `o` (using 'x')


           ^
Use '< h j k l >' to move.
         v	

NOTE:
If the path is looking weird, set your tabindent to 8:
go to command mode: '<shift-;>'
type: 'set tabstop=8'

_________
	|
	|
	|
	|
	|________
		|
		|
		|____
		    |
		    |
	   	    |
	____________|
	|
   _____|
   |		  _________
   |		 |	  |
   |_______	 |	  |
	  |	 |	  |
   	  |______|	  |
			  |
			  |
	__________________|
	|
	|
________|
|
|
|
|
|
|
o


1.2 MOVE FASTER
How can you move faster ?
What about trying to move Word by Word ?
Try it out on the following line:

	to move forwards word by word I use 'w' like word.

How does that feel ?
Now, try to move backwards !
Hint: you can use '$' to move to the last char of the line and then you know what to do.

	to move backwards word by word, I use 'b' like backwards.
	much easier thant CTRL-right-arrow, right ?

I realize to show you something really usefull...
I want to go to the first line of the file, how do I do that ?

' gg '

So let's go back on top of our current file using ' gg ' 
Below the first line, let's insert some text: to do so I can press ' o '
' o ' will switch insert mode on a new line below the one I am currently

Once we are done with our changes on top of the file, we can press <shift-g> to go (back) to the last line of the file.

Now you can go back edit faster using VIM, and feeling good !
