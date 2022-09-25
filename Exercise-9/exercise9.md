  # AltSchool-Cloud-Exercise-9-Week-6


> ![AltSchool Cloud Exercices](../cloud3.JPG) 

<br>

- [Back to first page](../README.md)
- [📔 Exercise 1](../README.md)
- [📔 Exercise 2](../Exercise-2/exercise2.md)
- [📔 Exercise 3](../Exercise-3/exercise3.md)
- [📔 Exercise 4](../Exercise-4/exercise4.md)
- [📔 Exercise 5](../Exercise-5/exercise5.md)
- [📔 Exercise 6](../Exercise-6/exercise6.md)
- [📔 Exercise 7](../Exercise-7/exercise7.md)
- [📔 Exercise 8](../Exercise-8/exercise8.md)
- [Overview](#overview) 
- [Task](#Task-EXERCISE-8) 
- [My process](#my-process)
- [Author](#author)


<br>

## Overview
### LEARNING CLOUD ENGINEERING WITH ALTSCHOOL.
<p>
It's about 8 weeks of learning cloud engineering with AltSchool.There has been so many new concepts to learn. This is the last week in september.
</p> 
<p>This week we learnt Bash scripting. With Bash scripting comes conditional statements, iterations and Functions. File permissions needs to include (x) to run an executable bash script. These files should have an extention of sh. e.g (test.sh) The files are started with a shebang line: !#/bin/bash. Bash scripting also allows for automation of scripts that runs within the linux environment.
</p>

<p>We also learnt about Crontab. This allows you to schedule commands or any application to run on the system. Cron job format : * * * * * which are minutes, hours, day, month, weekday respectively.
</p>
<br>
<br>


## Task EXERCISE 8💻
-  Create an ansible playbook to set up a server with apache
- The server should be set to the Africa/Lagos timezone.
- Host an index.php with the following content as the main file on the server.

<br>
<br>


## My process
- I created 2 VMs.
- I created ssh-keygen on the master-VM and copied it into the slave-VM. 
- I connected with slave-VM from master-VM through ssh and IP address. 
- In the master VM, I installed ansible.
- I created a directory for the ansible.
- I edited the /etc/ansible/hosts file adding the IP address of the slave-VM.
- I cd into ansible directory
- In the ansible directory, I created a host-inventory file.(Optional)
- I exported the ansible inventory module into the ansible path using the export command and echo the command to make sure it exported correctly.
- Then I edited the host-inventory file with the slave-VM IP address.(optional)
- I created a playbook to install apache, set the time zone to Africa/lagos and install php then ran a check on the playbook.
- I executed the playbook file. 
- I check the result in the slave-VM to see if the installations were deployed, and I checked the apache service to confirm it is working fine. 
- I created and edited an index.php file.
- Using ansible playbook, I copied the index.php file from the localhost to the remote server.
- I edited the apache config file in the remote server.
- I then checked the rendered page on my browser.
<br>
<br>

## Created multiple VMs edited the vagrantfile as follows:
<br>

## To Create ssh-keygen on the master-VM and copy it into the slave-VM. 
#### Run the following command :

```bash
$ ssh-keygen -t rsa
$ ssh-copy-id -i <remote-host IP address>
$ ssh <remote-host IP address>

```

## To install ansible
#### Run the following command:

```bash
$ sudo apt update
$ sudo apt install -y software-properties-common   
$ sudo apt install -y ansible

```
<img src="./images/Google-acct1.JPG">

<br>
<br>

## To create a folder in the home directory for the ansible
#### Run the following command:

```bash
$ mkdir -p ansible

```
<img src="./images/Google-acct1.JPG">

<br>
<br>


## To edit the /etc/ansible/hosts file adding the IP address of the remote-server.

#### Run the following command:

```console
# nano /etc/ssmtp/ssmtp.conf
```


<img src="./images/smtp-config1.png">
<img src="./images/smtp-config2.png">
<br>
<br>  





## To edit the revaliases file.

#### Run the following command from the root directory:

```console
#  nano /etc/ssmtp/revaliases

```
<img src="./images/revaliases-config.png">
<br>
<br> 


## To create a script for memory logs.
#### Run the following command:

```console
# touch email.sh
To run the script: ./email.sh
```
<img src="./images/EmailscrptConfig.JPG">
<br> 


## To read the content of the memory logs sent to a file (mailFile)

#### Run the following command:

```console
# cat mailFile

```
<img src="./images/cat-mailfile.png">
<br> 



## Create a crontab file and set the cronjobs to run the script(email.sh) to send emails at a specified time.

#### Run the following command from the root directory:

```console
# crontab-e 
(to create the crontab)
# crontab-l 
(to list the cronjobs on the system)
```
<img src="./images/cronjob1.JPG">
<img src="./images/cronjob2.JPG">
<br>


## Screenshots of emails sent.

### Screenshot of a random test mail.
<img src="./images/Email2.png">

### Screenshot of a mail sent at 12 midnight prompt.
<img src="./images/Gmail - VAGRANT MEMORY LOG.JPG">
<br>  


## Email log file was automatically deleted at 12:02 midnight.
<img src="./images/mailFile-deleted.JPG">
<br>
<br>

## Author

- Website - [Bukola Testimony](https://bukola-testimony.github.io/My-Portfolio-website/)
- Twitter - [@BukolaTestimony](https://twitter.com/BukolaTestimony)


