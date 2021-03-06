# Using Command Prompt

|Command|Description|
|-|-|
|cd `<directory's name>`|Change directory to specified directory.|
|cd `<directory's path>`|Navigate to a directory given the directory's path.|
|mkdir `<directory's name>`|Make a directory with the given name.|
|cp `<source file/directory>` `<destination directory>`|Copy file or directory and place it in the specified destination.|
|mv `<source file/directory>` `<destination directory>`|Move file or directory and place it in the specified destination.|
|ls **OR** dir |Lists all files and directories in the working directory. -t flag lists directories by the time they were last modified. -a flag view hidden files as well as non-hidden.|
|rm <file name>|Deletes files. -r flag recursively delete a directory and all of its child directories. -f flag force delete. -rf force recurrsively delete a directory. rm * delete all files recurrsivley. rm -rf .hiddenDirectoryName (delete hidden directory)|
|touch \<file name> |Creates a new empty file inside the working directory.|
|cat|Concatenate files and print on the standard output.|
|echo|Display a line of text.|
|pwd|Print working directory.|
|*|Wildcard.|
|>| Takes the standard output of the command on the left, and redirects it to the file on the right.|
|>>|Takes the standard output of the command on the left and appends (adds) it to the file on the right.|
|<|Takes the standard input from the file on the right and inputs it into the program on the left.|
|\||"pipe" takes the standard output of the command on the left, and pipes it as standard input to the command on the right. You can think of this as "command to command" redirection.|
|env|Returns a list of the environment variables for the current user.|
|nano [\<file name>]|Open nano text editor.|

* echo "Hello World"> HelloWorld.txt<br>Creates or overrides HelloWorld.txt, placing the text "Hello World" in the document.
