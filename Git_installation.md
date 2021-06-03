## Git installation on AWS EC2 instance:


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
git --version
```
#Set Username Configuration
```sh
git config --global user.name "shivardy0606"
```
#Set Email Configuration
```sh
git config --global user.eamil "shivareddy0692.b@gmail.com"
```
#Verify Username and Email Configurations
```sh
git config --list
```
#get project01 from github
```sh
git clone https://github.com/shivardy0606/Project01.git
```
#get inside project01 directory
```sh
cd Project01
```
#create a file inside project01 directory
```sh
echo "# Project01" >> README.md
```
#initialize git local repository
```sh
git init
```
#add file
```sh
git add README.md
```
#commit file
```sh
git commit -m "first commit"
```
#check git status
```sh
git status
```
#create git branch 
```sh
git branch -M master or git checkout -b master
```
#add origin [fatal: remote origin already exists.]
```sh
git remote add origin https://github.com/shivardy0606/Project01.git 
```
#remove origin
```sh
git remote rm origin
```
#again add origin
```sh 
git remote add origin https://github.com/shivardy0606/Project01.git
```
#push code to origin master
```sh
git push -u origin master
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
