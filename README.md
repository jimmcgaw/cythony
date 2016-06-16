# Doin' Some Cython

Just for fun (and to learn a bit of C) I'm learning how to integrate C code libraries and 
subroutines into Python via the Cython language.

## Install

Not much to this. "Hello World" in root requires a:

``` $ pip install -r requirements.txt ```

then a 

``` $ make hello ```

Drop into a Python shell. Run this:

``` python> import hello ```

and it should print "Hello World". You can edit this in "hello.pyx".

The Makefile is just an old-fashioned wrapper around Python's distutils script in setup.py.