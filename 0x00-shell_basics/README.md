#!/bin/bash
pwd - "print working directory"
ls - "Display the contents list of your current directory"
cd ~ - "changes the working directory to the user’s home directory"
ls -l - "Display current directory contents in a long format"
ls -la - "Display current directory contents, including hidden files (starting with .)"
ls -lan - "Display current directory contents. Long format with user and group IDs displayed numerically And hidden files (starting with .)"
mkdir /tmp/my_first_directory - "Create a script that creates a directory named my_first_directory in the /tmp/ directory"
mv /tmp/betty /tmp/my_first_directory/ - "Move the file betty from /tmp/ to /tmp/my_first_directory"
rm /tmp/my_first_directory/betty - "Delete the file betty. The file betty is in /tmp/my_first_directory"
rm -r /tmp/my_first_directory - "Delete the directory my_first_directory that is in the /tmp directory and not empty"
cd - - "changes the working directory to the previous one"
ls -la . .. /boot - "Write a script that lists all files in the current directory and the parent of the working directory and the /boot directory, in long format"
file /tmp/iamafile - "a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script"
ln -s /bin/ls __ls__ - "Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory"
cp -u *.html .. - "script that copies all HTML files from the current working directory to the parent directory, but only if the files don't exist in the parent directory or are newer than the ones in the parent directory"
mv [A-Z]* /tmp/u/ - "command that moves all files beginning with an uppercase letter to the directory /tmp/u."
rm *~ - "The command to delete all files in the current working directory that end with the character ~"
mkdir -p welcome/to/school - "the creation of nested directories with a single command"
ls -1apv - "list all files and directories of the current directory, separated by new lines, directories ending with a slash /, files and directories starting with a dot ., with verbose output that shows additional information"
