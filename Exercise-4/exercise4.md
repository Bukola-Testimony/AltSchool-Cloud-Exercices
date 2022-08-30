  # AltSchool-Cloud-Exercices-Week-2

> <img src= "https://github.com/Bukola-Testimony/AltSchool-Cloud-Exercices/blob/main/cloud3.JPG" alt="cloud Engineering image"> 

- [Back to first page-Introduction](https://github.com/Bukola-Testimony/AltSchool-Cloud-Exercices)
- [Overview](#overview) 
- [Task](#Task) 
- [My process](#my-process)
- [Creating users and groups](#Creating-users-and-groups)
- [Author](#author)

<br>

## Overview
LEARNING CLOUD ENGINEERING WITH ALTSCHOOL.
<p>
It has been 3 weeks of learning cloud engineering with AltSchool.Things are getting better now as I am getting more familiar with cloud concepts.   
</p>
<p>
This week we learnt system processes and file systems in linux, how to create users and groups, How to give sudo priviledges to users, how to add permissions and how to generate ssh keys. 
The highlight for me was when I discovered that by default, admin group has sudo priviledges and any user added to the admin group automatically gain sudo rights. A user or group with sudo rights has root priviledges. 
</p>

<br>
<br>


### TASK (EXERCISE 4)💻

- Create 3 groups; admin, support and engineering.
- create a user in each of the groups.
- Add the admin group to sudoers.
- Generate an ssh key for the user in the admin group.


<br>
<br>


## My process
- I created 2 groups: Support and Engineering. Admin group has already been created by default.
- Also by default, admin group belongs to the sudoers group which means that the user added to the admin group has sudo priviledges.
- I added users to each group
- I generated ssh keys for the user in the admin Group

<br>
<br>



## Creating users and groups  
Note: see screenshot of output below.
<br/>

### created users
> <img src="./Exercise-4/images/users.JPG" alt="users">



### created groups
> <img src="./Exercise-4/images/Capture.JPG" alt="groups">


### added users to groups
> <img src="./Exercise-4/images/Group-users.JPG" alt="users to groups">


### contents of /etc/groups (tail)
> <img src="./Exercise-4/images/etc-group.JPG" alt="content of etc groups">


### contents of /etc/password (tail)
> <img src="./Exercise-4/images/etc-passwd.JPG" alt="content of etc passwd">

<br>
<br>

## Generated ssh keys for user (Bukola) in the admin group:
<br>
<img src="./Exercise-4/images/user-sshkey.png" alt="create user ssh keys">


### User Public keys

<img src="./Exercise-4/images/User-pubkeys.JPG" alt="user public keys">

<br>
<br>



## Author

- Website - [Bukola Testimony](https://bukola-testimony.github.io/My-Portfolio-website/)
- Twitter - [@BukolaTestimony](https://twitter.com/BukolaTestimony)
