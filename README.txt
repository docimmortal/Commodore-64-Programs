QUESTION: How do I export a PRG from an image?

ANSWER:
Method 1:
Vice has a program called c1541, which you want run from the command line.
Syntax: c1541 -attach Name_Of_Image.d64 -read SOURCEFILE DESTINATION.prg
Example: c1541 -attach basic.d64 -read "simon" Simon.prg

If you want to list the contents of the image:
Example: c1541 -attach Name_Of_Image.d64 -list

Method 2:
There is a program for Windows called DirMaster. In DirMaster, you open your image
and then right-click the file you want to save and select Export.

QUESTION: How can I run a prg file on my C64 Ultimate?
You can run it like any other image via the Disk File Browser.