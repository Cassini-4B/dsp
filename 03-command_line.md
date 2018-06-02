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

> > ---pwd: show current working directory path
> > ---mkdir: create a directory
> > ---rm -r: deletes directories
> > ---touch: creates new file in current directory
> > ---rm: deletes files
> > ---mv: moves files or renames files
> > ---ls -a: lists hidden files
> > ---cp: copies files from one directory to another


> > ---cd: change directory
> > ---ls: lists all directories/files in current directory
> > ---cat > writes from one file to another
> > ---cat >> appends one file to another
> > ---cat: outputs contents of file to console
> > ---sort: sorts stdin
> > ---uniq: filters out adjacent, duplicate lines in file (adjacent only, so it's good to sort first)
> > ---grep: searches for lines that match a pattern and returns results (like re, stands for global reg ex print)
> > ---sed: find and replace





### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > ls: lists files in current directory
> > ls -a: lists all files, including hidden ones
> > ls -l: lists files using long listing format
> > ls -lh: list using human readable format
> > ls -lah: lists all files in human readable format
> > ls -t: sort by modification time, newest first
> > ls -Glp: no group, indicator style slash
---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > ls -d: displays only directories
> > ls -c: displays files by file timestamp
> > ls -r: displays files in reverse order
> > ls -u: displays files by file access time
> > ls -1: displays each entry on a line.

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > REPLACE THIS TEXT WITH YOUR RESPONSE

xargs is a tool that takes in a standard input and executes a command.  For example you can use it to find all .txt files in the current directory through: xargs find -name '*.txt'
 

