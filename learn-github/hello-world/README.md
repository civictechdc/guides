# Hello World!

In the happy land of learning to program, [Hello
World!](http://en.wikipedia.org/wiki/%22Hello,_world!%22_program) has
a long tradition, dating back to 1974, when the C programming language
was a baby being incubated at Bell Labs. The program simply outputs
the text "Hello World!" and is relatively easy to implement in any
language, and thus is a good starting point for learning a new
programming language.

## Python: hello-world.py

    #!/usr/bin/env python3
    # -*- coding: utf-8 -*-

    print("Hello World! (in Python)")

Comments start with `#` and continue to the end of the line. They are,
for the most part, ignored by the computer, and can contain whatever
text you want.

However, if the first line of your program begins with `#!` some
operating systems will take advantage and attempt to determine the
application -- in this case, the interpreter -- that should handle the
file. It is a bit like adding `.py` to the filename. In the above
example, the first line tells Unix-like systems (Linux, Mac OS X, etc)
that the code should be interpreted with Python 3.x (3.0 and beyond).

The second line is less common. Without getting too bogged down in
details, it tells some systems how to handle characters that are outside
of the American character set (alphabetical, numeric, and punctuation). 

Adding the first two lines to each `.py` file is good practice --
though `python3` should be simply `python` if you are not yet coding
for Python 3.x. (That said, you probably should be trying to move to
Python 3.x.)

The `print()` function prints to the screen the arguments between the
parentheses.

A good set of resources for continuing your Python journey can be
found in the [DC Python Meetup](http://www.meetup.com/DCPython/)
Python Lab
[Hackpad](https://pythondc.hackpad.com/Resources-3e0FfVoNQep) as well
as attending the Python Lab events at MLK Library on Saturday
afternoons.

## Ruby: hello-world.rb
