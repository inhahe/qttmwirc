This is an IRC client written in Python 2.x, using Twisted and PyQt. I thought the existence of a free graphical (or even non-graphical) IRC client written in Python was sorely lacking out there. 

It's not really finished, it's very rudimentary. It doesn't even have configuration dialogs yet, for example. 

I had written a similar program in 2009, also using Python 2.x, Twisted and PyQt, but I had lost the source code for 6 years, then found it not too long after finally getting around to re-writing it from scratch (i.e. this version). The original version is also on my github, as qtpyrc. This version was also originally called qtpyrc, but I eventually changed the name to qttmwirc. The qt is for PyQt, the second t is for Twisted, the w is for Windows (as this code may or may not have Windows dependencies), the irc is for IRC. I forget what the m is for, it might be for the "Matrix" in Twisted Matrix.

This version is, I think, more developed than the first version was, though I'm pretty sure I coded support for plugins in the first version, which isn't in this version. 

There may be files included that aren't really necessary for the project. I'm not even sure if all the files included are legal for me to distribute. Oh well.

I'm posting these two projects so that people can contribute to them and do the work of making them fully fledged that I'm too lazy to do. =) Maybe someone can even bring together the best parts of both projects into one of these two projects or into a new project. (It would be sad if I'm not the owner of said new project, though. :)) 

It uses t.i.p.irc, but I think I made some custom modifications to irc.py that the program relies on, hence the inclusion of irc.py in the repository. 

I tried to include support for unicode IRC messages, but it doesn't work right and I don't know why. If anyone can fix that I'd appreciate it. :d



