# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > REPLACE THIS TEXT WITH YOUR RESPONSE

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

ls - lists all files in a directory that are not hidden  
ls -a - lists all files including hidden files  
ls -l - lists long format (with permissions)  
ls -lh - list long format with readable file size  
ls -lah - list long format with all files (including hidden) with readable file size  
ls -t - list files sorting by date and time  
ls -Glp - list files without group names, in a long listing, appending a / to directories   


---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

ls -R - recursively displays the contents of all subdirectories in a directory
ls -r - displays files in reverse order.  Good if you know the file you are looking for starts with a z.
ls -L - displays files in a directory referenced by a symbolic link. Great to use when installing CUDA.
ls -p - displays directorys with a / at the end.  A bit easier to see directories
ls -1 - puts one file/directory per line. Can be easier to read

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

xargs reads in data input and executes the command one or more times on the input read. An example would be to type:  
xargs find -name  
"*.sh" control-D  
and the output would be: myshellscript.sh

 

