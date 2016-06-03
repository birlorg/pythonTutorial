Import
=======

Remember in :doc:`scripting` we covered saving things to files and calling them
 from python.  Let's take this a step further, we can bring our file into an
 interactive python session as well.  Let's do that.  first we need a file
 (here I've called it name.py)  in this file will be our printName function.
 Remember when typing indentations, always press the TAB key to move in 1 indentation.

in file name.py::

    def printName(name):
        """Takes a name (string) and will print out "Your name is:" along with the name capitalized. Returns the capitalized name.

        example: printName("lucy")
        will print: Your name is: Lucy
        """
        name = name.capitalize()
        print("Your name is:", name)
        return name

        Now if we run it::

    zoboFab:python zie$ python printName.py
    zoboFab:python zie$

It doesn't seem to do anything! But it did do things! It actually ran everything
in the file, but the file did not output anything it just defined a function.
Let's import it into our interactive interpreter::

	zoboFab:python zie$ python3
	Python 3.4.3 (default, Apr  7 2015, 08:05:21)
	[GCC 4.2.1 Compatible Apple LLVM 6.0 (clang-600.0.57)] on darwin
	Type "help", "copyright", "credits" or "license" for more information.
	>>> import name
	>>> name.printName('lucy')
	Your name is: Lucy
	'Lucy'

We can even get help on our function::

    >>>help(name.printName)
    Help on function printName in module name:
    
    printName(name)
        takes a name (string) and will print out "Your name is:" along with the name capitalized. Returns the capitalized name.
    
        example: printName("lucy")
        will print: Your name is: Lucy
    >>>


import (another python keyword), let's us import a python file as a "module"
 into python, so we can then use the code inside of that python file.  There
 is a lot more to import and modules, but we are going to skip all that extra
 stuff, and just cover the bare basics.

import takes the name of a python file. For now, it needs to be in the current
directory. the word after import is the name of the file without the .py extension.

some more examples:

filename: superSpectacularMagic.py

the import command would be:  import superSpectacularMagic

filename terribleCode.py

import terribleCode

Or, if we wanted to import both of them:

import superSpectacularMagic, terribleCode

To access functions, or variables that are inside the python file, you need to
preface the function or variable name with the name of the import and a period.
to use our printName function from the file name, we have to call printName as
name.printName  This filename.functionName is a great automagical feature,
because it lets us group a bunch of functions together, and keep them together,
and when reading code, you know where the code came from, because the filename
is there with us the whole time! This is called a "namespace" if you want to
go read more about the feature.
