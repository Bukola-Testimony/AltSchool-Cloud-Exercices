# AltSchool-Cloud-Exercices-Week-1
> <img src= "https://github.com/Bukola-Testimony/AltSchool-Cloud-Exercices/blob/main/cloud3.JPG" alt="cloud Engineering image">

This is the beginning of my journey in Altschool cloud Engineering track second semester. I am excited and pumped up to begin this exciting journey into the cloud. 

- [Introduction](https://github.com/Bukola-Testimony/AltSchool-Cloud-Exercices#readme)
- [Overview](#overview)
- [What I learned](#what-i-learned)
- [My process](#my-process)
- [Exercise 2](#exercise-2)
- [Exercise 3](#exercise-3)
- [Author](#author)



## Overview
LEARNING CLOUD ENGINEERING WITH ALTSCHOOL.

It has been exactly two weeks of learning cloud engineering with AltSchool and it has been the most exciting and tiring week for me.
This Project is a documentation of my progress in my chosen track.


### What I learned

This week I have learnt the different paths in cloud Engineering.
The history of and evolution of operating systems.
Evolution of Linux distros which is the most commonly used around the world.
I learned The difference between Physical hardware and virtual machines(VM) for which there is a need to set up a virtualization software.  
I also Learned several linux commands and still researching more.

It has been a loaded week of sleepless nights and a lot to learn, but the progress is well worth it. 


## My process
- Installed and set up VirtualBox
- Installed and set up Vagrant
- Installed and set up Ubuntu Focal 20.04LTS
We were given a task to set up Setup Ubuntu 20.04 LTS on our local machine using Vagrant and customize Vagrantfile as necessary with private_network set to dhcp. For this task, 
I downloaded, Installed and setup a vertualization software (Virtual Box) on my windows O/S.
I downloaded, Installed and setup Vagrant(A Development environment) on my windows O/S using git bash command.I also created a vagrant folder for vagrant initialization and set up on virtualBox. Finally installed and set up ubuntu focal 20.04LTS on vagrant. 


## EXERCISE 2💻
I particularly had a challenge configuring private networks on vagrant as it kept getting some errors each time I want to power up the machine. With the help of some my colleagues and a lot of google searching, I was able to finally set up the machine and configured it to private network. 

#### Here is the screenshot:

## Private network set to "dhcp" and configuration: ifconfig. 
Note: see screenshot of output below.
<br/>


> ![AltSchool Cloud Exercices](../week1/Vagrant/Vagrant-ifconfig.JPG)



## EXERCISE 3💻
###  Linux commands and their output:

```console

# To Display how long the system has been running.
 ~$ uptime  

# To Display current month calendar.
~$ cal

# To Display who is online.
 ~$ w 
 
# To Display detailed information about RAM.
 ~$ free

```


> ![AltSchool Cloud Exercices](../week1/linux/uptime-calendar-w.JPG)
<br>

```console

# To display current date and time
~$ timedatectl  

# To set currentdate and time to Afica/Lagos
~$ sudo timedatectl set-timezone Africa/Lagos 

```

> ![AltSchool Cloud Exercices](../week1/linux/Date-time.JPG)
<br>



```console

# To display the user and group ids of your current user.
~$ id 

# To display the last users who have logged onto the system.
~$ last    
```


> ![AltSchool Cloud Exercices](../week1/linux/id-last-who.JPG)
<br>



```console

# Display your currently running processes
~$ ps

# Display and manage the top processes
~$ top  
```
<br>

> ![AltSchool Cloud Exercices](../week1/linux/ps-top.JPG)


```console

# Display total disk usage of the current directory
~$ du -sh

# Display disk usage for all files and directories in human readable format
~$ du -ah
 
```


> ![AltSchool Cloud Exercices](../week1/linux/du-ah-sh.JPG)

<br>

## Author

- Website - [Bukola Testimony](https://bukola-testimony.github.io/My-Portfolio-website/)
- Twitter - [@BukolaTestimony](https://twitter.com/BukolaTestimony)
