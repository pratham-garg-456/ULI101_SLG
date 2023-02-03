\============================================================================================

**Week: 1**

1. ` `**cd** 		-> change directory
1. ` `**pwd**		-> present working directory
1. ` `**ls** 		-> list the files in the current directory

` `**ls -l** 		-> list the files but in long listing (detailed manner)

` `**ls -a**		-> list the files including hidden files.

` `**ls -la** 		-> list the files including hidden file but in long listing.

1. ` `**cal** 		-> shows the calender (current month).

` `**cal 2 2023**	-> shows the calender but of specific month and year.

` `**cal 2023**	-> shows the whole calender of 2023 year.

` `**cal 1**		-> 

`        `#Bonus calender in matrix range from from 1 - 9999 

1. ` `**date** 		-> current date and time (respect to server)
1. ` `**who**		-> people connected to the same node.
1. ` `**w** 		-> detailed view of the who command including the server up-time.
1. ` `**whoami**	-> current username
1. ` `**who am i** 	-> same thing as who but just for us.
1. ` `**clear** 		-> clears the screen. 
1. ` `**exit** 		-> logout from matrix.

` `**logout**	-> same thing

\============================================================================================

**Week: 2**

1. ` `**tree**		-> show the tree view of current present working directory.

` `**tree -C**	-> it shows the tree but in color.

1. ` `**mkdir**	-> make directory.

` `**mkdir** **-p**	-> create parent and sub/child directories both.

1. ` `**rmdir** 	-> remove directory (empty).
1. ` `**rm** 		-> remove file.

` `**rm -r**		-> remove directory (including non-empty) and file.

1. ` `**cp** 		-> copy files. 

` `**cp -r** 		-> copy directories (including empty and non-empty) and files.

1. ` `**mv**		-> move files or directories (both empty and non-empty).

` `**# -i**        Prompt for confirmation if the destination path exists. can be used with cp mv rm. 

1. ` `**touch**		-> create text file.
1. ` `**vi**		-> text editor.

` `**ESC**		-> command mode.

` `**i** 		-> insert mode.

` `**:w**		-> Save.

` `**:x**		-> Save and exit.

` `**:q**		-> exit if no changes made.

` `**:q!**		-> exit & discard any changes.

1. ` `**nano**		-> text editor.
1. ` `**cat**		-> text reader.

` `**more**

` `**less**

` `**head**

` `**tail**

1. ` `**file**		-> tell the type of file. (Helpful for the files which don’t have any e
1. ` `**find**		-> search for the files in a directory hierarchy.

` `Ex:                      find ~ -name “output.txt”

1. ` `**diff** 		-> compare files line by line.

` `**diff f1 f2 -y**   -> compare two files side by side.

1. ` `**sort** 		-> sort lines of text file.
1. ` `**uniq** 		-> omits same lines.
1. ` `**grep** 		-> matches the pattern.

\========================================================================



**Week: 3**

1. ` `**Absoulute path		->** /home/pgarg13/slg/output.txt
1. ` `**Relative path**		-> output.txt
1. ` `**Relative to home path**	-> ~/slg/output.txt
1. ` `**File name expansions**
   1. **\***	-> 0 or more characters
   1. **?**	-> exactly one character(any)
   1. **[ ]**	-> one character from the range
   1. **[! ]**	-> except those characters in the range
1. ` `**echo**				-> display a line of text.

` `**echo red**			-> display text red.

**echo red\***			-> show the files  starting with red.

**echo $USER**			-> show current username.

**echo '\* $USER \*'**		-> display \* $USER \*   //single quotes strong quotes

**echo “\* $USER \*”**		-> display \* pgarg13 \* // double quotes weak quotes

1. ` `**fc** -l				-> list previous 16 commands
1. ` `**history** 			-> list all the commands
1. ` `**who | wc -l**			-> gives the number of users or we can say lines.

