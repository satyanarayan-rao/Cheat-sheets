# Shortcuts for Vim

Vim is a great text editor, and sometimes it becomes a necessary to know tool becasue it takes less memory and you can do pretty much everything if you this tool well.
Here I am listing few commands and hacks that one can use to do file edits. 

## First thing first

One should aware of different modes of Vim. Of many, two are very famous and are generally used. One the **edit** mode, and the other **command** mode. 

When you open a file using VIM, you are seeing the command mode. You press **i** to enter into insert mode (basically the *edit* mode). You can go to command mode by pressing **ESC**. 

Lets get to some cool stuff of Vim. 

### Cursor movement

* Move word by word 
	+ forward: command mode (**ESC**) and then keep pressing **w**
	+ backward: command mode (**ESC**) and then keep pressing **b**
	 
* Jumps
	+ Start of file: ESC + gg
	+ End of file: ESC + GG
	+ Half page down: ESC + Crtl + d 
	+ Half page up: ESC + Crtl + u
	+ Bring the cursor at middle of screen: ESC + zz
* Deletion
	+ word: ESC + dw (keep pressing dw) 
	+ line: ESC + dd 
	+ 5 lines: ESC + 5dd 
* Copy
	+ word: ESC + yw
	+ line: ESC + yy 
	+ 10 lines: ESC + 10yy 

* Paste  (followed by Copy or Deletion)
	just press p or P to copy after or before cursor
