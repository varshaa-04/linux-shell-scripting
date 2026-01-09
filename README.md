# linux-shell-scripting

**OPERATING SYSTEM: An Operating System (OS) acts as an interface between the user/applications and the computer hardware.**

**LINUX OPERATING SYSTEM**

Linux is the boss of the computer.
It tells the hardware what to do, when to do it, and for which program.

When you run a command or app, Linux:

1.Starts the process

2.Gives it CPU time

3.Gives it memory (RAM)

4.Allows or denies access to files

5.Talks to hardware

6.Stops the process when done

**ARCHITECTURE OF LINUX OS**


<img width="550" height="500" alt="ChatGPT Image Jan 9, 2026, 08_18_06 PM" src="https://github.com/user-attachments/assets/a5991dec-8d22-4e03-b289-8a4c73664c7d" />




Applications        |--------> Applications user install on top of OS

Shell / GUI         |--------> Graphical user interface

System Libraries    |--------> Shared libraries are reusable pieces of code that multiple programs can use at the same time instead of each program carrying its own copy.

Linux Kernel        |--------> Heart of linux OS, which actually establishes the communication between the hardware and the software. 

Hardware            |--------> CPU,RAM,HARD DISK

**LINUX COMMANDS** 

**Basic commands**

1.ls--> which list all the previous files and folders.

2.pwd--> present working directory

3.cd-->change directory

4.cd .. --> moving back to the previous directory

5.cd../.. --> moving back to the 2 directory back.

6.ls -ltr --> it gives all the files and folders details with the time stamp and owner of the group and type of the file & permissions 

**file and directory commands**

1.touch filename --> to craete a file 

2.vi filename--> to write content into the file.

3.cat filename --> to view the content of the file

4.rm --> to remove file

5.mkdir --> to create a directory

6.rm -r dir-name --> to remove a directory

**c**

1.free -g --> to view details about the memory usage 

2.nproc --> shows the details of how many cpus are used

3.df -h--> check disk size

4.top --> to check both the memory and cpu utilizations
