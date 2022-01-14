Create full Operating system on linux, kernel, .e.t.c
===========


I have always wanted to learn how to make an OS from scratch. In college I was taught
how to implement advanced features (pagination, semaphores, memory management, etc)
but:


Inspired by [this document](http://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf)
in reference to [this people i was able to learn from and write mine, modified a lot of stuffs, and added mine, changed a lot of sytax,and made it more readable](https://github.com/cfenollosa/os-tutorial)
and the [OSDev wiki](http://wiki.osdev.org/), I'll try to make short step-by-step READMEs and
code samples for anybody to follow. 

Updated: more sources: [the little book about OS development](https://littleosbook.github.io),


How to use this tutorial
------------------------

1. Start with the first folder and go down in order. They build on previous code,Please do not jump a folder, so there won't be difficulty in learning all

2. Open the README and read the first line, which details the concepts you should be familiar with
before reading the code. 
 
3. Read the rest of the README. It is **very important**.

4. Try to write the code files by yourself after reading the README(this is optional though)

5. Look at the code examples. They are extremely well commented so you could grab and learn more from it

6. (Optional) Experiment with them and try to break things. The only way to make sure you understood something is
trying to break it or replicate it with different commands.


TL;DR: First read the README on each folder, then the code files. If you're brave, try to code them yourself.


Strategy
--------

We will want to do many things with our OS:
- Memory management
- Write a filesystem to store files
- Create a very simple shell
- User mode
- Maybe we will write a simple text editor
- Multiple processes and scheduling
- Boot from scratch, without GRUB 
- Enter 32-bit mode 
- Jump from Assembly to C 
- Interrupt handling
- Screen output and keyboard input 
- A tiny, basic `libc` which grows to suit our needs 

Probably we will go through them in that order, however it's soon to tell.

If we feel brave enough:

- A BASIC interpreter, like in the 70s!
- A GUI
- Networking



Contributing
------------

I was able to build my Operating system and even modified a lot more added a lot more features to mine, edited a lot more stuffs, feel free to use and learn from it

