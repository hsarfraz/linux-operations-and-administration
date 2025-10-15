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

 * Here is a [screenshot]() of the windows file directory structure (pg. 42) and here is a [screenshot]() of the Linux file directory structure (pg. 43)
