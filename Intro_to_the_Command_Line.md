Command Line
============

Introduction to the POSIX Command Line
======================================

Shaun William Hallee 2014-01-13 Ver 0.1 CC3.0-BY-SA

Programs
--------

### 1. Programs with no arguments

`fortune, hostname, whoami`

### 2. Programs with arguments

`cowsay, ping`

### 3. Stopping a program

\^C

### 4. Programs with options

`cowsay, ping`

The Filesystem
--------------

### 1. Where are we?

pwd

### 2. What can I find here?

ls

### 3. Let's go somewhere else

cd

### 4. Making new directories

mkdir

Interacting with Files
----------------------

### 1. Let's make new files.

touch

### 2. What type of file is this?

file

### 3. CoPying, MoVing, and ReMoving files

cp mv rm echo \> echo \>\> cat less nano

Editing Files with vim
----------------------

vi, vim — standard text editor Esc — enter normal mode :q! — quit without saving hjkl — movement (can also use the arrow keys) — check out vimsnake.com i — insert (before cursor) a — append (after cursor) x — delete character under cursor :w path — write file to path :o path — open file at path :wq (save and quit)

For more, check vimtutor.

Programming in the shell (Python)
---------------------------------

First, let's see what version of Python you have. The following command will tell you what version is the default on your computer.

    python --version

Next, for an interactive Python interpreter, use the python command with no arguments.

    python

To exit back into the shell, enter `quit()`.

Now, lets create a Python script, and run that. You can use either Vim or Nano.

    vim hello_world.py

OR

    nano hello_world.py

Edit the file to say

    print "Hello, World!"

if you have Python version 2.x, or

    print("Hello, World!")

if you have Python version 3.x.

Then you can call `python` with the name of your script as the argument. This will just run your script instead of giving you a Python prompt.

    python hello_world.py

This should just print out `Hello World!` to the terminal.

End
===
