# Linux

## Introduction and History


#### What is Linux?
* Linux is a Unix-like, open source and community-developed operating system for computers, servers, mainframes, mobile devices and embedded devices.  It is supported on       almost   every major computer platforms making it one of the most widely supported operating systems.
* Just like Windows XP, Windows 7, Windows 8, and Mac OS X,GNU Linux is an operating system.<br> 
* An operating system is software that manages all of the hardware resources associated with your<br>
  desktop or laptop.<br> 
* To put it simply - the operating system manages the communication between your software and your hardware.<br>
* Without the operating system (often referred to as the “OS”), the software cannot function.
---
## History
* In late 1960's a team of developers of Bell Labs started a project to make a common software for all the computers and named it as 'Unix'.Unix was released in 1970's it was   simple and elegant, used 'C' language instead of assembly language and its code was recyclable. Also its source code was open source.
* Initially, Unix was only found in large organizations like government, university, or larger financial corporations with mainframes and minicomputers (PC is a                 microcomputer) who could afford the costly OS.
* In 1983 a programmer Richard Stallman creates the GNU project. It was an attempt at creating an UNIX type operating System but composed of entirely free Software.
* In 1987 another programmer Andrew S. Tanenbaum creates UNIX like OS called MINIX for academic use.
* In 1991, Linus Torvalds a student at the university of Helsinki, Finland, thought to have a freely available academic version of Unix started writing its own code. Later     this project became the Linux kernel. He wrote this program specially for his own PC as he wanted to use Unix 386 Intel computer but couldn't afford it.   
* Linux uses most of its tools from GNU software and are under GNU copyright. In 1992, he released the kernel under GNU General Public License.

---
## Why Linux over Other OS

### 1. Linux is Secure and Private <br>
  Linux is more secure in comparison to other competing operating systems. Linux requires authorization from the root, or superuser, in the form of a password. Unless the       password is known and used, nothing will run – not even a virus! This provides an added benefit of eliminating the need for anti-virus software.

### 2.Linux is Free to Use and Update<br>
  Linux is not licensed and is free to download and use. Typical costs for Windows OS range from $55 to $450 dollars depending on the application. There are paid versions of   Linux, but these are typically much more affordable.<br>

### 3.Linux is Easy to Install
Linux is easily installed from the web without any prerequisites as it can run on any hardware.

### 4. Linux is Reliable
Other operating systems, such as Windows, often require a reboot after installing or uninstalling software and updates – not so with Linux! Linux doesn’t freeze or lock up systems (unless there is a hardware fault).<br>


---
##  Various Linux Distribution
### What is a “distribution?"
Linux has a number of different versions to suit nearly any type of user. From new users to hard-core users, you’ll find a “flavor” of Linux to match your needs. These versions are called distributions (or, in the short form, “distros.”) Nearly every distribution of Linux can be downloaded for free, burned onto disk (or USB thumb drive), and installed (on as many machines as you like).
**The most popular Linux distributions are:
* Ubuntu Linux
* Linux Mint
* Arch Linux
* Deepin
* Fedora
* Debian
* openSUSE.

---
## POPULAR LINUX COMMANDS

| Command   | Syntax   | Explanation   |
|---|---|---|
| ls  | ls directoryname'<br>ls -l<br>ls -la   |(ls) is used to list all files and directories inside of a particular directory.<br>(ls -l)it gives details of the file.<br>(ls -la )it list all files including hidden files.  |  
| cd (change directory)   | cd directoryname' <br> cd /<br>cd -<br>cd ~| it allows you to change your current directory.<br>change to previous directory<br>moves directory step back<br>takes you to home directory   |
| pwd   | pwd   | is used to print the current working directory path   |  
| man   | man (command)   | is used to display the manual page for a particular command   |
| mkdir   | mkdir directoryname  | is used to create a directory.   |
| rmdir  | rmdir directoryanme | is used to delete a directory.   |
| touch   | touch filename   | It creates an empty file.  |
| rm   | rm filename<br>rm -r<br>rm -rf  | used to delete a file<br>only removes files<>used to delete folders/directory   |
| rm - rf*   | rm -rf*   | used to delete all files and folders/directory  |
| cat     | cat filename  | It prints the content of a file to the terminal window. |
| mv   |mv 'D''S'    | The mv command is used to move a particular file or directory from one location to another   |
| cp  | cp'f1''f2'<br>cp-rf'd1''d2'   | The cp command is used to copy a particular file from one location to another.<br>used to copy a particular directory from one location to another  |
|echo   | echo ''   | The echo command is used to print a string to the terminal window.   |
| ps   | ps   | The ps command is used to view the ongoing processes on your system.  |
| who	   | who  | Tells who is logged on the system.  |
| whoami  | whoami  |	Tells the name of the user. |
|top    | top  | The top command gives information regarding your machine's performance, the resources usage and the currently running processes.     |
| history   | history   | show all past    |
| exit   | exit    |it exits from the terminal    |
|ifconfig(apple os)<br>ipconfig(windows os)    | ifconfig<br>ipconfig    | gives network address/informations    |
| ping   | ping   | to check internet speed   |
| less    | less filename    | prints output pagewise basically gives more data or information    |
| more   | more filename   | gives less data or information     |
| clear     | clear     |  clear the terminal/everything   |
|ssh    | ssh'Host ip address'  | helps login to another server   |
| which   | which [filename]   |it is used to locate the executable file associated with the given command by searching it in the path environment variable  |
| tail   | tail -n <number> <file name>   | It will display the specified number of lines from the last. <br>where n is the number of lines you want to display from the last |
|wget  | wget URL   | acts as command line browser   |

----

 ## LINUX FILE SYSTEM AND DIRECTORY STRUCTURE
  
![image](https://user-images.githubusercontent.com/84236206/119609583-761af180-be15-11eb-89fb-c2caa635cfec.png)

  
| Directory Type  | Type of file stored|
|---|---|
| /boot  | System kernel is stored    |
| /bin   | Binary files are stored here<br> or <br> it contains thecommands that are useful to both system admin as well as other users  |
| /sbin   | it contains the system binaries <br> used by system admin and not by other non priviledged users    |
| /home       | contains home directories of the user <br> e.g: home folder -->/home/username<br>it contains all users data or files     |
| /var        | variable files <br> it is writable directory and contains files like log files,spool files and cache files    |
|  /usr    | userf binaries <br>all user related resources and supporting software are stored here      |
| /root      |It is the home directory of the root user.|
| /tmp       | temporary files are stored here   |
| /etc      | System configuration are stored here   |
| /lib      | System level binaries are stored in lib    |
| /mnt      |The '/mnt' directory should be empty and sysadmins can only mount temporary filesystems |
| /dev      | provides memory files <br> This location is of special files or the device files.<br>all external hardware like mouse,keyboard are connected via dev    |
| /opt       | Optional packages <br>this contains sub directories for all optional packages that are not part of the installation    |

---
  
  
