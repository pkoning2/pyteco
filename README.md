# pyteco - An implementation of TECO in Python

This is a nearly complete implemention of standard TECO, in Python 3.

Unlike other TECO implementations, the characters are Unicode, not 8 bit characters.  You can see this demonstrated in the sample macro bmp.tec.

Currently ANSI compatible screen mode (:W command) is not implemented.  It looks like this could be done using the Python "screen" module but I have not attempted to do so.

The code was written a while ago.  Some of it is not a great example of Python style; in particular, I'm not sure I would use metaclasses in the way I did here.  
