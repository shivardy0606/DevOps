### Git installation on AWS EC2 instance:

#Create an EC2 instance with Amazon Linux 2 with internet access
#Connect to your instance using putty

#Perform a quick update on your instance:
```sh
sudo yum update -y
```
#Install git in your EC2 instance
```sh
sudo yum install git -y
```
#Check git version
```sh
git version
```
#create a directory named employee
```sh
mkdir mygit
```
#get inside mygit directory
```sh
cd mygit/
```
#initialize git local repository
```sh
git init
```
#observe .git file is created in your local git repository which contains data and metadata of your local git repository
```sh
ls -a
ls -a .git/
```
#check git status
```sh
git status
```
#getting help from the command line
```sh
git help
```

#list all git commands and sub-commands
```sh
git help -a
```

#getting help for a particular git command
git help <command> # for example, git help init will provide details of git init command
