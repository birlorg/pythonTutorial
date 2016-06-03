Setup Your Environment
======================

MAC OS X:
---------
	* Open your web browser and visit: http://www.python.org/download
	* Download the Python 3 distribution (version 3.4.3 at time of this writing)
	* Install the file you just downloaded.
	* Open your Finder, then click on Applications, then click on Utlities, then 'Terminal'.  This should open a white window with black text.
	* Type in: python3
	* then hit enter
	* You should see something like this:
Python 3.4.3 (default, Apr  7 2015, 08:05:21)

[GCC 4.2.1 Compatible Apple LLVM 6.0 (clang-600.0.57)] on darwin

Type "help", "copyright", "credits" or "license" for more information.

>>>

	* The important part is the >>> It's called a 'prompt' It's asking you to type in python!
	* If you don't see the >>> then get my attention please!
	

Windows 7+:
-----------
	* Open your web browser and visit: http://www.python.org/download
	* Download the Python 3 distribution (version 3.4.3 at time of this writing)
	* Install the file you just downloaded.
	* Run PowerShell from the Start menu. Search for it and you can just press Enter to run it. You should get a blue window with white text.
	* type in: python
	* then hit enter
	* You should see something like this:
Python 3.4.3 (v3.4.3:9b73f1c3e601, Feb 24 2015, 22:43:06) [MSC c.1600 32 bit (intel)] on win32

Type "help", "copyright", "credits" or "license" for more information.

>>>	

	* If you get something in red that says "the term 'python' is not recognized...
	* then type this in to powershell:

    [Environment]::SetEnvironmentVariable("Path", "$env:Path;C:\Python34", "User")

	* then restart Powershell (or maybe the entire computer).
	* The important part is the >>> It's called a 'prompt' It's asking you to type in python!
	* If you don't see the >>> then get my attention please!


Windows XP (untested at this point):
------------------------------------
	* download and install powershell for Windows XP
	* URL for the download: http://www.microsoft.com/en-us/download/details.aspx?id=7217
	* then follow the instructions for Windows 7+ above.

Linux:
------
	* Every linux is a little bit different so I don't have magical type this instructions, sorry.
	* I assume you know how to install programs.  Install python3, make it so you can start a terminal and type: python3 and get the python >>> prompt.
	* The important part is the >>> It's called a 'prompt' It's asking you to type in python!
	* If you don't see the >>> then get my attention please!


Python Shell Environment:
-------------------------

Don't worry if all of this below doesn't make sense, we will cover more about what these things are later on.

Command line recall:  If you press the up arrow,  it will go "up" in your history, and let you see previous python instructions and save them. The down arrow does the opposite, if you are already in history.

Help: there is built-in help, that can be useful, it's a "function". to use it, type in help(object) where object is the thing you want help on. up and down arrows should work, and press q to quit help. for instance:

>>> help(help)

There is also a function called :class:`python:dir` dir, that will give you a list of attributes on an object, call it with dir(object) where object is the thing you want to know more about.

>>> dir(5)


to exit the >>> prompt press CTRL + D at the same time, or type in exit()

>>> exit()


Very basic help about the "terminal" is available here: http://learnpythonthehardway.org/book/appendixa.html
