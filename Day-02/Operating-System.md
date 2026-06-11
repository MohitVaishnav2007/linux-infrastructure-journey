# Operating Systems

In my Day 2, I have learnt about the Operating Systems, 
What they are ?
Why they are ? 
Why our machines actually need this kind of program named as Operating System ?
You'll get answer of all such questions in this file.

---

## Key Concepts

Operating Systems, as named suggests, is a System which is very essential to operate our systems. When in late nineteenth century, the Invention of Computers Begin and Engineers starts using it, so they face a very big issue, and the issue is that when we allot one task for our computer, it will use all the memory and other resources in just completing that one task. There are also lot of issue comes infront of engineers related to resource allocation, handling the systems, etc. Engineers will understand that we need a separate layer between hardware and application. Then the invention of Operating Systems (OS) takes place. 

*** Operating Systems (OS) is a full packed system, controls everything between the hardware to application interaction. It contains utilities, applications, services, kernel, etc. ***

---

## Parts of Operating Systems

A Operating System contains 9 major parts or sectors, which OS to take control over system or machine. These are as follow :

- Kernel 
- Libraries 
- System Utilities 
- Shell 
- Init System 
- Device Drivers 
- Package Manager 
- Filesystem 
- Desktop Environment (Optional) 

---

## Understanding Parts of Operating Systems

### Kernel

It is the most important part of the Operating system. It can be called as Sole of whole Operating System. It is the most important part which play crucial roles between hardware and application layer. If there is no kernel in operating system, then it will be very difficult to communicate with hardware.
#### Responsibilities
- CPU Scheduling
- Memory Management
- Security (Permissions, etc.) 
- Process Management
- Networking
- Storage Access
- other Resource Management




### Libraries 

Hope that we all know that the command flow is as follows :
Applications  ->  Library  ->  Kernel

Kernel is not able to understand source code or human readable format of code. So it needs to translate so that kernel can understand it. 

Libraries provide ready-made function, which helps to implement code like this:

 ```C
 printf(Hello)
 ``` 

#### Example 
- glibc
- musl




###  Shell

It is the part of OS (Operating system) with which we are familiar the most, specially the CLI Users. All of interact with this. 
Shell interprets command.
If we don't have shell, then we have very difficult time interacting with system. 




### System Utilities

These are the tools which operating system provide us to handle it more easily. 

``` Common Tools
ls - use to list the files and directories contained within a file system folder
cp - use to duplicate files and directorie
cat - use to display, combine, and create text file
greb - use to search for specific text, words, phrases, or patterns within files or terminal outputs
etc.
```




### Init Systems 

When computer boots, it follows a cycle ;
> Power Button  ->  Kernel  ->  Init System  ->  Services Start 

It launches all the services which helps to operate upon machine, for example:
- Networking
- Login Services
- Background Services




### Device Drivers

Drivers are the masterpiece of OS which helps it to communicate with hardware. Without Drivers, their is no communication with hardware or motherboard.

**Example :**
- Wi-Fi Driver
- GPU Driver
- Keyboard Driver
- USB Driver

*** Note : Many drivers live inside kernel, but some exist outside of it.***




### Package Manager

Package Manager is use to manage package or software all around the OS. 
Managing includes installing, deleting, updating, etc.

For Different Operating Systems, there are different types of package managers are available :
- Arch Linux - Pacman
- Ubuntu - Apt
- Fedora - Dnf




### Filesystem

This is the only thing, which helps you to systematically align and stores all the data around your machine. it helps to stores data systematically. 
Without Filesystems, there is no files, no folders or even no storage organization. 

**Example :**
- ext4 
- xfs
- btrfs
- zfs




### Desktop Environment (optional)

Now, this is place where the mostly GUI users interacts. actually the graphical apprearance of utilities tools, services all around the operating system is only possible with the help of Desktop Environments. This provides windows, icons, etc.
But, here's a catch, an operating system contains desktop environment, is fully optional. For example, systems like server, have no Desktop environments. 

**Example :**
- GNOME
- KDE
- XFCE

---

