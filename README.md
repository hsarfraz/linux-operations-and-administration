# linux-operations-and-administration

Textbook: Linux Operations and Administration by Alfred Basta

## Ch 1: Intro to Linux Operations

* Linux architecture and its components: kernal, desktop environment, and file structure (pg.2)
* Open source software has its source code published with the software. Users can modify and redistribute open-source software (pg.2)
* Ubuntu is a distribution/version of Linux. Other distributions include red hat, openSUE, etc
* Linux is a modular system, meaning all components are separate from one another
* The **kernal** is the core of the operating system and manages the hardware such as disk drivers and memory
* **RAM** is short for random access memory and it is a temporary storage space where the computer reads and writes data. The memory is erased when the computer shuts down (pg.7-8)
* A **shell** is a command-line interface between users and the kernal. The most common shell is BASH (pg.10)

| Components of Linux Architecture (pg 7) -[image link](https://github.com/hsarfraz/linux-operations-and-administration/blob/main/images/linux_architecture.jpg) | Purpose |
| ------------- | ------------- |
| Applications (Firefox, OpenOffice.org)  | na |
| Graphical Desktop Environment (KDE, GNOME) | gives you windows, icons, menus + part of linux OS |
| Daemons (ftpd, httpd, inetd) & Shells (Bourne, C, Korn, BASH)  | part of linux OS |
| Linux Kernel  | Part of Linux operating system (Ubuntu or openSUSE) |
| Hardware | The virtualization software (VirtualBox or VMWare Player) + The Linux OS runs on this |

## Ch 2: Installing OpenSUSE & Virtualization Software Packages 

* Here are 4 virtualization software packages: cooperative linux/CoLinux, Windows Virtual PC, Oracle Virtual Box, VMware Player (pg. 18)
* Here is a youtube video which talks about the differece between the two most popular virtualisation software packages, VirtualBox vs VMWare Player. [link to video](https://www.youtube.com/watch?v=BZE6WhOa7GM)
* Steps for installing a virtualization software packages 
  1. Install the virtualization software package (cooperative linux/CoLinux, Windows Virtual PC, Oracle Virtual Box or VMware Player)
  2. Install a linux operating system (Ubuntu or openSUSE)
* How I installed the Ubuntu 24.04.3 operating system on my virtualbox virtual machine
  * I searched "ubuntu desktop install" on Google and clicked on [this link](https://ubuntu.com/download/desktop) from the official Ubuntu website and picked the `.iso` file for intel machines. I then went on the settings page of my virtual machine and went on the storage tab. Under the controller section/IDE I selected the iso file for the Ubuntu system

 ## Ch 3: Managing Files and Directories

 * Here is a [screenshot](https://github.com/hsarfraz/linux-operations-and-administration/blob/main/images/windows%20directory%20structure.jpg) of the windows file directory structure (pg. 42) and here is a [screenshot](https://github.com/hsarfraz/linux-operations-and-administration/blob/main/images/Linux%20Directory%20Structure.jpg) of the Linux file directory structure (pg. 43). Notice how the windows file directory has two separate braches while the linux file directory has one main branch

The table below highlights different components of the Linux directory structure

| Directory | Description |
| ------------- | ------------- |
| /bin  | Contains binary commands that can be used by system administrators, users, and scripts; this directory shouldn't contain subdirectories and can be accessed in single user mode |
| /boot  | Contains the Linux kernal and static files needed to boot the computer |
| /dev  | Contains device files, such as the CD/DVD-ROM drive |
| /etc  | Contains static configuration files, which are also unsharable files, meaning they are local to the machine  |
| /home  | An optional directory that might not be included in all Linux distributions; in openSUSE, it's the user's home directory |
| /lib  | Contains shared libraries that are loaded when a program starts |
| /media  | Contains the mount point for removable media |
| /mnt  | Empty by default, but administrators can use it to mount other resources, such as CD/DVD-ROM drives |
| /opt  | Contains static shareable add-on software packages |
| /root  | Contains the recommended home directory for the root user; not all Linux distributions use it, but it's used in openSUSE |
| /sbin  | Contains system binaries used by the system administrator |
| /srv  | Contains data files for services |
| /tmp  | Contains temporary files that system administrators should delete whenever the system is booted |
| /usr  | Contains shareable, read-only applications and files |
| /var  | Contains variable data files, such as log files |
