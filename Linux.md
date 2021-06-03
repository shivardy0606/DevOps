# Linux Basic Commands

#Take the update
```sh
yum update -y
```
#Create User
```sh
adduser shiva
```
#Create password to user
```sh
passwd shiva
```
#Group add
```sh 
groupadd devops
```
#Add user to group
```sh
usermod -a -G devops shiva
```
#Get group & password data  
```sh
vi /etc/passwd
# vi /etc/group
```
#Provide root access to user
```sh
visudo [shiva   ALL=(ALL)       NOPASSWD: ALL]
```
#Login to user
```sh
su - shiva
```
