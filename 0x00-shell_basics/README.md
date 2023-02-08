All the files are made executable by the command, "chmod u+x filname or chmod 755 filename"
0-current_working_directory script file prints the current working directory
1-listit script list the contents of the current directory2-bring_me_home implements a commaned that changes the working directorry to the user's home directory
3-listfiles list files of current directory in long format
4-listmorefiles list all files including hidden ones in current directory
5-listfilesdigitonly displays current directory content in long format, with user and group IDs displayed numerically, and hidden files (starting with .)
6-firstdirectory creates a directory named my_first_directory in the /tmp/ directory
7-movethatfile moves the file betty from /tmp/ to /tmp/my_first_directory.
8-firstdelete deletes the file betty.
9-firstdirdeletion deletes the directory my_first_directory that is in the /tmp directory.
10-back changes the working directory to the previous one.
11-lists lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12-file_type prints the type of the file named iamafile which can be found in the /tmp directory.
13-symbolic_link creates a symbolic link to /bin/ls, named __ls__ in the current working directory.
14-copy_html copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
100-lets_move  moves all files beginning with an uppercase letter to the directory /tmp/u.