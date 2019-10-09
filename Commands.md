<h1 align="center">Linux/Unix Commands</h1>

## listing files
-`ls`\
-If you want to see the list of files on your UNIX or Linux system, use the `ls` command

## Creating & Viewing Files
-To create a new file, use the command\
1.`cat > filename`\
2.Add content\
3.Press `ctrl + d` to return to command prompt.\
-To view a file, use the command\
`cat filename`

## Searching for content in a file/ files in a directory
- To search for a word in a file using terminal,use the command ```grep```
- For eg., if you want to search for the word GNU in a file named ```GNU.txt```,type ``` grep GNU GNU.txt```
- This will show all lines which have the word ```GNU``` in that file
- To search over multiple files in a directory, use ```grep``` with ```-r``` flag, like ``` grep -r GNU .```. Here ```-r``` stands for recursive search and ```.``` specifies the search root to be the current directory.

## Viewing Files and Directories in a given directory
- Standard syntac -> ls <directory_name> -<flags>
- If no directory_name, the command displays the files and directories in the current working directory
- if no flag is assigned, then it displays a list of all the non hidden files and directories in the given dirrectory.
- eg of few flags: ls -l, ls -a, ls -al.
- -l flag diplays detailed list of the file and directories, specifying information about each file and folder.
- -a flag displays even the hidden files.
- -al does the job of -a and -l

