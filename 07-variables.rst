Variables
=========

Variables give us a way to store a value. Or to say it another way, a variable is a name that refers to a value. The computer does not put any meaning into the variable names, they are just names to the computer and don't mean anything special.


>>> 12 * 12
144
>>> pencils = 12 * 12
>>> pencils
144
>>> color = "pink"
>>> color
'pink'
>>> print(color)
pink

We can change what a variable stores:

>>> color = "yellow"
>>> color
'yellow'
>>> color = "purple"
>>> print(color)
purple
>>> print("My favorite color is", color)
My favorite color is purple

Variables are great to store something to be used later.  Variables can not contain spaces, I recommend what's called "Camel Case" for variable names, where capital letters are used instead of spaces, for instance Camel Case could be rewritten as camelCase.  Another common way to deal with the no spaces rule is to use the _ character instead of a space.  An example would be: yellow_pencils  Also, do not begin variables with a number.

Don't be afraid to have long-ish variable names, your brain will thank you.

Variable rules:
	* no spaces in your variable names.
	* start your variable off with a letter a-Z.
	* do not start your variable with a number or any symbol.
	* In general keep your variable names to words and name them for what they store.
	* Case matters.  favoriteColor and FavoriteColor are different variables.

Also, you can not use one of these words as variable names::

	False None True and as
	assert break class continue
	def del elif else except
	finally for from global
	if import in is
	lambda nonlocal not or
	pass raise return try
	while with yield
  
These are called keywords and they are all special, and mean something unique to Python.