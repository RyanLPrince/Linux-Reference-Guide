# Using Command Prompt

|Command|Description|Common Errors|
|-|-|-|
|cd `<directory's name>`|Change directory to specified directory.| cd: myFile/: No such file or directory|
|cd `<directory's path>`|Navigate to a directory given the directory's path.| cd: myFolder/myFile/: No such file or directory|
|mkdir `<directory's name>`|Make a directory with the given name.|mkdir: cannot create directory ‘myFile’: File exists|
|cp `<source file/directory>` `<destination directory>`|Copy file or directory and place it in the specified destination.||
|mv `<source file/directory>` `<destination directory>`|Move file or directory and place it in the specified destination.||
|ls **OR** dir |Lists all files and directories in the working directory. -t flag lists directories by the time they were last modified.||
|rm|Deletes files. -r flag recursively delete a directory and all of its child directories. -f flag force delete||
|touch <file name> |Creates a new empty file inside the working directory.||
|cat|Concatenate files and print on the standard output.||
|echo|Display a line of text.|
|pwd|Print working directory.||
|*|Wildcard.||
|>| Takes the standard output of the command on the left, and redirects it to the file on the right.|
|>>|Takes the standard output of the command on the left and appends (adds) it to the file on the right.|
|<|Takes the standard input from the file on the right and inputs it into the program on the left.|
|\||"pipe" takes the standard output of the command on the left, and pipes it as standard input to the command on the right. You can think of this as "command to command" redirection.|

* echo "Hello World"> HelloWorld.txt<br>Creates or overrides HelloWorld.txt, placing the text "Hello World" in the document.
