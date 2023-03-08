0-current_working_directory: This script prints the absolute path name of the current working directory.

1-listit: This script displays the list of contents of your current directory.

2-bring_me_home: This script that replaces the working directory with the user's home directory.

3-listfiles: This script displays current directory contents in a long format.

4-listmorefiles: This script displays current directory contents, including hidden files (starting with .). Use the long format.

5-listfilesdigitonly: This script displays directory contents.
	* Long format
	* With user and group IDs displayed numerically
	* And hidden files (starting with .)

6-firstdirectory: This script creates a directory named my_first_directory in the /tmp/ directory

7-movethatfile: This script moves the file betty from /tmp/ to /tmp/my_first_directory

8-firstdelete: This script deletes the file betty.
	* The file betty is in /tmp/my_first_directory

9-firstdirdeletion: This script deletes the directory my_first_directory that is in the /tmp directory

10-back: This script that changes the working directory to the previous one.

11-lists: This script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

12-file_type: This script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run the script.

13-symbolic_link: This script creates a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

14-copy_html: This script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parents of the working directory.

100-lets_move: This script that moves all files beginning with an uppercase letter to the directory /tmp/u

101-clean_emacs: This script that deletes all files in the current working directory that end with the character ~.

102-tree: This script that creates the directories welcome/, welcome/to/, welcome/to/school in the current directory

103-commas: This script write a command that lists all the files and directories of the current directory, separated by commas (,)..
	* Directory names should end with a slash (/)
	* Files and directories starting with a dot (.) should be listed
	* The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
	* Only digits and letters are used to sort; Digits should come first
	* You can assume that all the files we will test with will have at least one letter or one digit
	* The listing should end with a new line


