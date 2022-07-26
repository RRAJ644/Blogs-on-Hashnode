## Let's begin with Linux - Part 1

Let's start with ** What is a Linux ** and ** Where did it come from ?**

To learn more about this term ** "LINUX" ** let's understand the bit of history associated with it.

In 1969, there were two developers ** Ken Thompson ** and ** Dennis Ritchie ** while working for Bell Laboratories these two people had developed the first **Unix operating system**. After sometime they rewrote the whole operating system into ** C language ** and it was majorly for making it more portable and soon it became a widely used operating system. 

After a decade a guy named **Richard Stallman** started working on GNU project, **the kernel of GNU called Hurd**, which never came to completion.  At that time lots of operating systems were coming like BSDs, MINIX etc. they all were unix like-systems but there is a common lack in all these unix like-systems that there is no unified kernel in them.

Now there is a new term **Kernel** so what it is let's look into it to get the basic understanding of kernel?

**kernel** is the core of an operating system **(most important piece in the operating system)** and it has complete control over everything in the system and 
it facilitates the interaction between the hardware and software. kernel does the whole lot of other stuff too.

In 1991, now a guy named **Linus Torvalds** started working and developed something which is today known as **Linux kernel**.

So  the term linux refers to the **Linux kernel** there are various operating systems which uses linux kernel so therefore they are commonly known as Linux operating systems.

A Linux system is divided into 3 parts

   1. Hardware: It includes the hardware that your system runs on as well as memory, disks, etc.

   2. Linux kernel: It facilitates the interaction between the hardware and software.
 
   3. User Space: User here means who is interacting with the system. 
 
**So why to use Linux?**
 1.  It is open source
 2. Supports all the programming languages
 3. Terminal is superior to CMD (Command Prompt)
 4.  It opens the scope for **bash scripting**.

** Now let's deep dive into how to use linux based operating system what is shell, commands and so on? **

** So What is shell? **
It is a command line interface which will take all my commands as an input from the keyboard and sends them to the operating system to execute.

In GUI also that is Graphical User Interface there are programs such as Command prompt. these are just programs that launches a shell for the user to operate on the system.

There are different types of shell such as bash, ksh, zsh etc.

We will get into the ** bash ** which stands for ** Bourne Again Shell **. every linux distribution is having bash shell by default.

![usr_name.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657817262583/MJeixFyTI.png align="left")

username@hostname:current_directory

``` ~ ```: This symbol denotes the home directory.

```$ ```: This symbol denotes the normal user using bash.

``` # ```: This symbol denotes the root user using bash.

** Now let's start with commands let begin with simple one echo command **

```echo```:  This command is used for displaying the text on the display.
![echo.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657818530957/CE2HrXwVF.png align="left")

** Path: **/** [current directory] ** home**[there is home directory]**/User**[inside home there is user]**

```pwd```:  This stands for Present Working Directory. It tells where we are on the computer by giving the path of present working directory.
![pwd.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657818462953/dlC2h4rbj.png align="left")

```cd```: This stands for Change Directory. This command is used for navigation in the file system. We navigate using the paths. There are 2 different ways of specifying the path.

**But What is path?**
**It’s a unique location to a folder or file.**

  1. **Absolute path:** This path is specified from the root directory. root directory is denoted as ** / **.Whenever we want to navigate in the file system we need to specify the destination path from the root directory.

  2. **Relative path:** This is the path related to present working directory. whenever we want to navigate in the file system we need to specify the destination path with respect to present working directory.

** Let's look at some examples **

Let say I am currently in the documents folder and wanted to go in Desktop. I can navigate to desktop in two ways that is using 

   1.  Absolute path
       ![abs.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657825772402/SBH_hS662.png align="left")

   2. Relative paths.
       ![rel.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1657826686506/K7C6_0u9D.png align="left")


** There are shortcuts we can use with the absolute and relative paths **
 
```cd .``` : (Current directory) 
```cd ..```: (Parent directory)
```cd ~```: (Home directory)
```cd -```: (Previous directory)
