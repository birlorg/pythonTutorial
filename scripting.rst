Saving Your Work
================

The next big thing we want is to be able to save our program, edit it later and then run it any time without having to type it all in again.  To do this, we need a text editor, so we can save and write our programs out to disk.

Get a text editor like Sublime Text Editor (http://www.sublimetext.com) and then write your python and save it with a .py extension.  You should then be able to double click it and have it run, or better yet, run it from your terminal (python3 <filename.py>).  A more advanced (and free) text editor would be something like Vim (http://www.vim.org) it's what I use normally, but it's not for the faint of heart.

You could use something like Notepad on Windows, but you will find it's much better to have an editor that knows a bit more about programming, it will highlight the program for you, and make everything much easier to work with.
You almost certainly don't want to use something like Word or Pages, while they
are great for documents, they do a terrible job at plain text.

Let's try this!
 Open your editor with a new file named favoritesProgram.py and put in the file::

	favoriteColor = "purple"
	favoriteNumber = 12
	print("My favorite color is", favoriteColor)
	print("My favorite number is", favoriteNumber)

save this file, then go to your terminal, make sure you are in the same directory as the file you just saved (favoritesProgram.py)
and then type this:

on Mac OSX & Linux::

	python3 favoritesProgram.py

on Windows::

	python favoritesProgram.py

You should see something like::

	zie@zoboFab ~/source/birl.org/python $ python3 favoritesProgam.py
	My favorite color is purple
	My favorite number is 12

