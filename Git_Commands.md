### How to check your Git configuration:
 The command below returns a list of information about your git configuration including user name and email:
```sh
git config -l
```
### How to setup your Git username:
 With the command below you can configure your user name:
```sh
git config --global user.name "shivardy0606"
```
### How to setup your Git user email:
 This command lets you setup the user email address you'll use in your commits.
```sh
git config --global user.email "shivardy0692.b@gmail.com"
```
### How to cache your login credentials in Git:
 You can store login credentials in the cache so you don't have to type them in each time. Just use this command:
```sh
git config --global credential.helper cache
```
### How to initialize a Git repo:
 Everything starts from here. The first step is to initialize a new Git repo locally in your project root. You can do so with the command below:
```sh
git init
```
### How to add a file to the staging area in Git:
 The command below will add a file to the staging area. Just replace filename_here with the name of the file you want to add to the staging area.
```sh
git add filename_here
```
### How to add all files in the staging area in Git
 If you want to add all files in your project to the staging area, you can use a wildcard . and every file will be added for you.
```sh
git add .
```
