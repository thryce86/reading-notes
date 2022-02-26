I have been using bash off and on for like 4 years so I know this.

didnt know about 

Escape Characters
Another method is to use what is called an escape character, which is a backslash ( \ ). What the backslash does is escape (or nullify) the special meaning of the next character.


Can never remember the wildcards 

Here is the basic set of wildcards:

* - represents zero or more characters
? - represents a single character
[] - represents a range of characters


find every file whose name includes a digit in it we could do the following:

ls *[0-9]*


We may also reverse a range using the caret ( ^ ) which means look for any character which is not one of the following.
ls [^a-k]*


Move all files of type either jpg or png (image files) into another directory.
mv public_html/*.??g public_html/images/




chmod [permissions] [path]  #this command sucks to deal with 

Linux permissions dictate 3 things you may do with a file, read, write and execute. They are referred to in Linux by a single letter each.

r read - you may view the contents of the file.
w write - you may change the contents of the file.
x execute - you may execute or run the file if it is a program or script.

