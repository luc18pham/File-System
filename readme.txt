This code allows you to create linked allocated file systems and to add, remove, and modfiy commands
Commands Supported 
"createfs" name : Makes a new file system of that name.
"open" name     : Opens a file system.
"close"         : Closes current file system.
"put" filename  : Puts that file into the file system.
"get" filename  : Gets that file from the file system.
"quit"          : Quits the program.
"savefs"        : Saves the file system and writes it to disk.
"del" filename  : Deletes that file from the file system.
"undel" filename: Restores that file to the file system.
"attrib" (+ or -) (r or h) filename : makes a file read only or hidden or no longer read only or hidden.
"df"            : Says how much space is left in the current file system.
"list"          : Lists all the files in the current file system.