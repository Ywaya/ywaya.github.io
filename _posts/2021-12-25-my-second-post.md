---
layout: post
title: Fundamental Linux Commands
subtitle: Beginner's guide to the Linux terminal
categories: Markdown
tags: [Markdown, Linux terminal commands]
---
# Fundamental Linux Commands
- 'To open terminal' *click ctrl + alt + t*
- 'To zoom in" *click ctrl + +*
- 'To zoom out' *click ctrl + -*
- 'To clear the screen' *clear or ctrl + l*
- 'Home directory' */home/your username*
CD stands for change directory, in other words go to another directory for example cd Downloads/
- 'Going back to home directory' *cd/home/your username or cd ~ or cd*
ls stands for list
pwd stands for print working directory
- 'To show all files including the hidden files' *ls -a*
Files that begin with periods are hidden files on Linux
- 'To show all files including the hidden file for long listed format' *ls -al*
'ls -lah' *l stands for long format, a stands for all files including hidden files and h stands for human readable numbers*
- 'To read the main page' *man ls*
- 'To exit' *click ctrl + x*
- 'To save' *click ctrl + y*
- 'To create a new directory' * mkdir name*
mkdir stands for make directory
- 'To move something into a dirctory so tha it is no longer empty' *mv file name/*
- 'To go to the last directory you were in before the current directory' *cd -*
- 'To copy a file' *cp file name/*
- 'To remove files from directories' *rm name/ file*
- 'To remove an empty directory' *rmdir name/*
- 'To remove a directory with everything in it' *rm -rf name/*
- 'To find programs on your system' *which ls or whereis name*
whereis name lists multiple things with the same name used
- 'To search for files and directories on your system' *locate name or sudo find / -name name*
'To install this program' *sudo apt install mlocate*
'To update this program' *sudo updatedb*
- 'To print text' *echo "text"*
- 'To print text' *printf "1\n2\n3"* allows escape sequences
- 'To redirect output to a file' *>*
- 'To find a specific line of text' *grep name .location*
| directs the output from a program to another
- 'To get specific lines of a text' *head .name or tail .name*
- 'To get specific number of lines' *head -n number or tail -n name*
- 'For file permissions' *drwxr -xr -x*
- 'To change finale permissions' *chmod permission file*
- 'To give yourself executive permissions' *./name or chmod +x name*
history gives the commands run recently
- 'To run a specific command as numbered in history' *!number* as listed and *!!* the last command run
- 'To update your system' *apt update*
- 'To kill or close a program' *kill name-terminal* and *killall name-terminal* for multiple instances
- 'To test networking' *ping site*
- 'To kill the ping' *click ctrl + c*
wget is for downloads from the web
date returns the date
- 'To change format for programs' *man name* of the program for example man date
cal stands for calendar
bc stands for basic calculator
- 'To get out of bc' *quit*
.bashrc signifies the files can fit well
nano .bashrec
alias ll = 'ls -alF'
alias la = 'ls -A'
alias l = 'ls -cF'
- 'To update your system on a Debian or Ubuntu based system' *sudo apt update && sudo apt upgrade*
alias nano .bashrc
alias aptup = 'sudo apt update && sudo apt upgrade'
- 'To exit' *click ctrl + x*
- 'To write' *click ctrl + y*
