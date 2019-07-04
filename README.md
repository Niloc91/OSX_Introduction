# OSX_Introduction

# Skills to be obtained
- Navigation through OSX
- Basic scripting
- Introduction to terminal
- Introduction to bash profile

## Helpful commands
CMD + Spacebar - searching

Linux commands

* touch - creating a file
* ls - list files
* rm - remove
* mkdir - make directory
* man <command name> - manual

## Exercises

### 1) Navigation
Open terminal and create entry to automatically print the message below

string „hello <username> the time is <datetime>“
<username> and <datetime> should be taken from the OS

example: "hello colinsiew the date is: Do 4 Jul 2019 10:05:16 CEST"

Hint: .bash_profile will need to be edited

### 2) Terminal introduction
create a directory structure using terminal with the structure below

hello/world/example.sh

The example should be completed without navigation ie. don't "cd" into directories, directories can be created recursively

hint: useful commands - mkdir, ls, touch

### 3) Scripting
Modify the example.sh script to print out all even numbers from 1-100 when terminal is opened. This will combine the previous exercises together. The path to the script should be added to your bash_profile.

Script can be run using 
`
$ sh example.sh
`
When a new terminal is opened the even numbers from 1-100 should be printed on screen

### 4) More Linux commands
under the hello/world folder
create files called 
* example2.sh
* example.txt
* example2.txt
* example.jpeg

Try using the command below
`
$ ls
`
This will list everything

Try listing only files with the .sh extension

hint: `man ls` for the manual

Remove all files with the .txt extension

hint: `man rm`

Copy all files with .jpeg and .sh extension with the one command to the top level "hello directory"

hint: `man cp`


