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

1) pwd
2) mkdir directory
3) rmdir directory
4) touch filename
5) rm filename
6) mv oldfilename newfilename
7) ls -a 
8) cp file1 file2
9) history
10) man command 





 

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

1) lists contents of working directory
2) lists files + hidden files in wd
3) long listing of file info
4) list size of file
5) list size of hidden files as well
6) list files by modification time
7) long listing of files with path, without owner

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

1) ls -R list contents of directory and subdirectories
2) ls -r list files in reverse order
3) ls -i display inodes of each file
4) ls -d display directories only
5) ls -c disply files by timestamp

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

xargs converts input into arguments for a command.
Default command is echo.

**xargs find -name "*.txt"**


 

