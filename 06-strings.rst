Strings in Python
=================

	* A string is a character, or sequence of characters (like words and sentences).
	* A number can be a string if it’s wrapped in quotes
	* All strings should be wrapped in quotes "This is a string"
	* Some of the operators we learned earlier work with strings too!
	* What operators do you think would make sense?
	* how about +?

>>> "This is a string"
>>> "This is a " + "string"
>>> "a dozen of something is 12 things"


>>> "this is" in "this is a string"
>>> "is this" in "this is a string"


Strings are made up of characters:

>>> "h" + "e" + "l" + "l" + "o"
'hello'

Each character gets an index:

 H E L L O

 0 1 2 3 4
 
In Python, Indexes always start at 0:

>>> "hello"[0]
'h'
>>> "hello"[4]
'o'
>>> "Hello World!"[2]
'l'
>>> "Hello World!"[5]
' '

String Operators:
	* concatenation (joining words together): +
	* multiplication with numbers: *
	* compare equal: ==
	* compare not equal: !=
	* compare in: in
	* compare not in: not in

String Rules:
	* Each character’s position is called its index.
	* Indexes start at 0.
	* Spaces inside the string are counted.

Print
-----

>>> "This" + "isn’t" + "great."
'Thisisn’tgreat.'

>>> "This " + "is " + "better."
'This is better.'

>>> print("this", "is", "much", "better")
this is much better

:func:`python:print` is a "function", which is a way to group a bunch of instructions together.  print is a built-in function, that means Python gives it to us for free. We will cover more about functions in a different class.. for now, just put whatever you want to print inside the () with print inside of it. print will take almost anything and print it for us!

>>> print(6+6, "eggs makes a dozen.")
12 eggs makes a dozen.


for more information on strings, you can type help(str) into the python shell OR visit :class:`python:str`
