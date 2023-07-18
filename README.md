
# Customised-Virtual-File-System

This Project is used to emulate all functionalities provided by File Systems.


## Platform Required

Windows NT Platform OR Linux Distributions
## Architectural Requirement

Intel 32 bit Processor
## User Interface 

Command User Interface
## Technology Used

C++

C programming
## Description

-> In this project we emulate all data structures which are used
   by Operating system to manage File system oriented tasks.

-> As the name suggest virtual, its because we maintain all
   records in the Primary storage(RAM).

-> In this project we create all data structures which are 
   required for File Subsystems like Incore Inode Table, UAREA,
   User File Descriptor Table, Super Block, Disk Inode List Block,
   Boot Block etc. 
      
-> We provide all implementation of necessary system calls and 
   command of File Subsystem as Open, Close, Read, Write, Lseek, 
   Create, RM, LS, Stat, Fstat etc.

-> While providing the implementation of all above functionality
   we use our own data structures by referring Algorithms of UNIX
   Operating system. 
     
-> By using this project we can get overview of UFS(Unix file 
   System) on any platform.
   ## Commands Implemented using this project

| Command             | Description                                                                |
| ----------------- | ------------------------------------------------------------------ |
| ls | To list all the files |
| clear | To clear the console |
| create | Create a new file |
| open | Open a specific file |
| close | Close specific file |
| closeall | Close all the opened files |
| read | To read the contents form file |
| write | To write contents into the file |
| truncate | To remove all the data from the file |
| rm | To delete the file |
| stat | Display information about the file |
| fstat | Display information using the File Descriptor |
| exit | To teminate the File System |




## Refrence

- Linux System programming by Robert Love

