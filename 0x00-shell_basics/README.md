**File Name**	:	*Description*

0-current_working_directory	:	Prints the absolute path name of the current working directory
1-listit	:	Displays the contents of your current directory
2-bring-me-home	:	Changes the working directory to the user's home directory
3-listfiles	:	Displays current directory contents in a long format
4-listmorefiles	:	Displays current directory contents including hidden files
5-listfilesdigitonly	:	Displays current directory contents in long format, with user and group IDs displayed numerically and hidden files
6-firstdirectory	:	Creates a directory named `my_first_directory` in `/tmp/` directory
7-movethatfile	:	Moves the file `betty` from `/tmp` to `/tmp/my_first_directory`
8-firstdelete	:	Deletes the file `/tmp/my_first_directory/betty`
9-firstdirdeletion	:	Deletes the directory `/tmp/my_first_directory`
10-back	:	Changes the working directory to the previous one
11-lists	:	Lists all files, including hidden files, in the current directory and the parent of the working directory and the `/boot` directory, in this order, in long format
12-file_type	:	Prints the type of the file named `iamafile` in the `/tmp` directory
13-symbolic_link	:	Creates a symbolic link to `/bon/ls` named `__ls__`
14-copy_html	:	Creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copies those that do not exist in the parent of the working directory or were newer versions in the parent of the working directory
100-lets_move	:	Moves all files beginning with an uppercase letter to the directory `/tmp/u`
101-clean_emacs	:	Deletes all files in the current working directory that end with the character `~`
102-tree	:	Creates the directories `welcome/`, `welcome/to`, `welcome/to/school` in the current directory
103-commas	:	Lists all the files and directories of the current directory, separated by commas (`,`)
school.mgc	:	Used with the command `file` to detect `School` data files. `School` data files always contain the string `SCHOOL` at offset 0
