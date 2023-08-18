# Operating-System-Terminal-Life
Various OS &amp; Terminal processes


## Operating Systems

An Operating system serves as a bridge asb between a computer's user and its hardware. An operating system's function is to offer a setting in which a user can conveniently and effectively run programmes. There are two types of OS ie

  - Linux
  - Unix
  
Linux refers to the kernel of the GNU/Linux operating system. More generally, it refers to the family of derived distributions. Linux is a Unix clone,behaves like Unix but doesn't contain its code. Linux is an open source, free to use operating system widely used for computer hardware and software, game development, tablet PCS, mainframes etc. Unix is an operating system commonly used in internet servers, workstations and PCs by Solaris, Intel, HP etc. Currently, more than 300 Linux distributions are actively maintained. There are commercially backed distributions, such as Fedora (Red Hat), openSUSE (SUSE) and Ubuntu (Canonical Ltd.), and entirely community-driven distributions, such as Debian, Slackware, Gentoo and Arch Linux.

Unix refers to the original operating system developed by AT&T. More generally, it refers to family of derived operating systems. Original code developed by Linus and the GNU Foundation. Unix contain a completely different coding developed by AT&T Labs. In other words we can say that Linux is just the kernel. Unix is a complete package of Operating system.


## Terminal Life
The word terminal refers to a interfacce used to interact with the Operating system. Some of them are mentioned below:

 - Terminal Multiplexers
 - Process Monitoring
 - System performance
 - Network Tools
 - Bash Scripting
 - Text Manipulation Tools
 - Others

Once again I'd like to mentioned the source of this roadmap: https://roadmap.sh/devops
I'll be discussing all of these above mentioned interactions by demonstrating them in Centos.


### 1. Terminal Multiplexers
  - screen & tmux:
  Screen is a full-screen window manager that multiplexes a physical terminal between several processes whereas tmux is a terminal multiplexer: it enables               a number of terminals to be created, accessed, and controlled from a single screen. 
          
   -     man screen
         
   -     man tmux

    
### 2. Process Monitoring
  - ps, top, htop, atop etc:
    These commands are for monitoring various processes happening in the system both hardware & software, some of which are explained below: 
  
    on typing (man ps), we get:
    ![image](https://user-images.githubusercontent.com/97732099/200850709-cf0ed412-3095-4a38-95dd-35797a5fa802.png)
   
    on typing (man top), we get:
    ![image](https://user-images.githubusercontent.com/97732099/200851043-a98c70cc-992d-44a3-8b5a-38db88898a93.png)

    similarly go and check out for htop, atop etc.    
    
    
### 3. Text Manipulation Tools
  - grep, sort, cat, echo etc:
    These commands are used for searching, sorting, reading files/data in the system, some of which are explained below: 
  
    on typing (man grep), we get:
    ![image](https://user-images.githubusercontent.com/97732099/200853244-bdeb640b-43d5-437e-99a7-a4027d46b221.png)
    
    on typing (man sort), we get:
    ![image](https://user-images.githubusercontent.com/97732099/200853353-eea41183-aead-43af-b3bd-14abd8cafe44.png)

    on typing (man cat), we get:
    ![image](https://user-images.githubusercontent.com/97732099/200853488-48d7a867-270a-4af7-9e44-37975d45a3d5.png)

    similarly go and check out for commands such as echo, fgrep, egrep etc.

    
### 4. Network Tools
  - tracerout, iptables, netstat, ping etc:
    These commands are used to understand network connectivity between host and the server. 
  
    on typing (man ping), we get:
    ![image](https://user-images.githubusercontent.com/97732099/200854491-ec3d6800-09d8-42d0-978a-950b2bcc59b4.png)

    
    
