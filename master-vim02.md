1.1 MOVING THE CURSOR

Try this:
Follow the '-' until the 'o' and cross out the 'o'
						         ^
It goes without saying but of course you will use '< h j k l >'
						       v	
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


1.2 Exit
	Exit vim without saving and come back.
	:q<CR>
	
	Reopen the file in vim. *BE MINDFUL*

1.3 Save and exit
	Go through the map one more time and cross out the 'o'	

	Now, save this file and exit vim.
	:wq<CR>

1.4 Remove the extra `;`

int main()
{
	return 0;;
}

1.5 correct the 3 syntax mistakes and delete the doubled line

int mian()
{
	pritnf("VIM MASTER 3\n");
	pritnf("VIM MASTER 3\n");
	retrun 0;
}

1.6 Use SHIFT-a to append  '0;' at the end of the line.

int	main()
{
	return 
}

1.7 switch to command mode, and save this file.
:w<CR>

2. USE OPERATOR AND MOTION
2.1 delete the 2 words 'int argc'

int main(int argc)
{
	printf("I use vim btw\n");	
	return 67;
}


2.2 Undo
Undo the last action (u)
Redo the last action (Ctrl-r)
Undo all the actions in this line (SHIFT-u)


2.3	Change to the end of the line

	a. Place your cursor after 'b'
	b. SHIFT-d to delete to the end of line
	c. type 'i' to go in insert mode
	d. write ';'
	e. go back in normal mode <Esc> or (better) <Ctrl-c>

	a. Place your cursor after 'b'
	b. SHIFT-c to delete to the end of line AND go in insert mode 
	c. write ';'
	e. go back in normal mode <Esc> or (better) <Ctrl-c>

int sum(int a, b)
{
	return a + b + c + d + e;	
}


2.4	Let's talk about 'g'

	a. Try 'gg'
	b. try 'SHIFT-g'
	c. try 'CTRL-g

	do you know something else with 'g' ?


2.5	QUESTIONS:
	How do I go move backwards word by word ?
		to move forwards word by word I use 'w' like word.
		to move backwards word by word, I use 'b' like backwards.
		much easier thant CTRL-right-arrow, right ?
	How do I jump at the end of a word ?	
	How do I switch back to normal mode ?
	
	What is the command to edit a file ?
	What is the command to split my screen ?

	When we want to perform an action in the whole line, what is the pattern ?
	How do you interprete SHIFT-d, SHIFT-c, SHIFT-a, SHIFT-i, (hint: line-oriented)
	How do you read the vim manual ?

	how to list your buffers ?
	how to edit a specific buffer # ?

		


