
![linux](https://i.ibb.co/hHpZhq9/Webp-net-resizeimage-4.png)

# What is  Command line?

The Linux command line is a text interface to your computer.
Also known as shell, terminal, console, command prompts and many others, is a computer program intended to interpret commands.
Allows users to execute commands by manually typing at the terminal, or has the ability to automatically execute commands which were programmed in “Shell Scripts”.

# The Shell Bash?

Within a terminal you have what is known as a shell. This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you. There are various shells available but the most common one is called bash which stands for Bourne again shell. 

## Basic Navigation !

### So where are we?
```
user@bash: pwd
/home/omar

```
### What's in Our Current Location?

```
user@bash: ls
bin Documents public_html

```

### Let's Move Around a Bit
```
user@bash: cd ~/Documents

```

>pwd
Print Working Directory - ie. Where are we currently.
ls
List the contents of a directory.
cd
Change Directories - ie. move to another directory.


## More About Files!

### Linux is Case Sensitive
This is very important and a common source of problems for people new to Linux. Other systems such as Windows are case insensitive when it comes to referring to files. Linux is not like this. As such it is possible to have two or more files and directories with the same name but letters of different case.


```
user@bash: ls Documents
FILE1.txt File1.txt file1.TXT
...
user@bash: file Documents/file1.txt
Documents/file1.txt: ERROR: cannot open 'file1.txt' (No such file or directory)

```

### Hidden Files and Directories 
Linux actually has a very simple and elegant mechanism for specifying that a file or directory is hidden. If the file or directory's name begins with a . (full stop) then it is considered to be hidden
```
user@bash: ls Documents
FILE1.txt File1.txt file1.TXT
...
user@bash: ls -a Documents
. .. FILE1.txt File1.txt file1.TXT .hidden .file.txt
...

```

>file
obtain information about what type of file a file or directory is.
ls -a
List the contents of a directory, including hidden files.
