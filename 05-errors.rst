Errors aka Tracebacks
======================

>>> 5/0
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ZeroDivisionError: division by zero

This is an error, also called a Traceback.  This is showing us that Python was unable to carry out the instruction you gave it and why it was unable to do so.  Let's look at it line by line.
The first line is saying hey, This is an error silly! it's also saying the most recent call will come last, so it will show in order, the instructions it was able to complete that led up to the one that broke, and the one that broke at the very end.  Since we are working from the Interactive Shell, it always processes every line, so there is only 1 line here, line 1.  The actual error then comes next. Here it's "ZeroDivisionError", with a message to follow to help lead us in the right direction.

This is a pretty straightforward error, Just like in math, we are not allowed to divide by zero.  So it tells us this.  Let's try a slightly harder error:

>>> 500 */ 4
  File "<stdin>", line 1
    500 */ 4
         ^
SyntaxError: invalid syntax

Here, we see the same Line 1, but then on the next line it shows us the actual line we typed in, and on the next line it shows us a ^ just under where the error is.  and finally on the last line it shows up the actual error "SyntaxError", with a little message about that error (invalid syntax).  Here we can see it understood the * (multiply) just fine, but then it got the / (divide) right after. This is invalid Python and doesn't make sense.  Python is smart enough to catch it, and then tells us what's going on.  To fix this error we need to fix the syntax, and decide if we want multiplication OR division... Or maybe we forgot a number and we meant:

>>> 500 * 4 / 3
666.6666666666666

There is a lot more to Errors, for instance we can "catch" the error in Python and then do something else, but that's a more advanced topic, we will leave for a different class.
