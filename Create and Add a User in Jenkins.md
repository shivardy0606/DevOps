# How to Create/Add a User in Jenkins
Below are the steps to create new user in Jenkins:

### Step 1) Login to Jenkins Dashboard

Login to your Jenkins dashboard by visiting http://ipv4:port/

If you haven't installed Jenkins in your local server, go to the appropriate URL and access your dashboard by using your login credentials.

![image](https://user-images.githubusercontent.com/82079865/125249838-449dad00-e313-11eb-9af3-7e7e1b4b3e82.png)


### Step 2) Choose the option

You will now see options to create and add user in Jenkins and manage current users.

### Step 3) Create a new User

Under Manage Jenkins, Click Create User
Enter Jenkins add user details like password, name, email etc.
Click Create User
![image](https://user-images.githubusercontent.com/82079865/125249715-259f1b00-e313-11eb-910f-af3788245e7a.png)


### Step 4) User is created

You will see on the dashboard that a new Jenkins create user as per the details entered.

![image](https://user-images.githubusercontent.com/82079865/125250195-97776480-e313-11eb-8f7f-de8acf37c5a5.png)


## How to Install Role Strategy Plugin in Jenkins
There are two methods for installing plugins in Jenkins:

Installing it through your Jenkins dashboard
Downloading the plugin from Jenkins website and installing it manually.
### Step 1)

1. Go to #### Manage Jenkins

2. Click on the Manage Plugins option

![image](https://user-images.githubusercontent.com/82079865/125250312-b544c980-e313-11eb-89a7-0edb648362c7.png)


### Step 2)

In available section, screen Search for "role".
Select #### Role-based Authorization Strategy plugin
Click on #### "Install without restart" (make sure you have an active internet connection)

![image](https://user-images.githubusercontent.com/82079865/125250478-ecb37600-e313-11eb-941b-e0d82ae86d3e.png)

### Step 3)

Once the plugin is installed, a "success" status will be displayed.

![image](https://user-images.githubusercontent.com/82079865/125250543-fe951900-e313-11eb-95b0-90b2123b14bc.png)


Click on Go back to the top page.

### Step 4) Go to Manage Jenkins -> Configure Global Security -> Under Authorization, select Role Based Strategy. Click on Save.

![image](https://user-images.githubusercontent.com/82079865/125250623-18cef700-e314-11eb-8d44-a8970f3bf33f.png)

## How to Manage Users and Roles in Jenkins
Following are the steps on how to manage and assign roles in Jenkins:

### Step 1)

1. Go to Manage Jenkins

2. Select Manage and Assign Roles

![image](https://user-images.githubusercontent.com/82079865/125250692-2f754e00-e314-11eb-918c-c63fbcc6f161.png)

Note: that the Manage and Assign Roles option will only be visible if you've installed the role strategy plugin.

### Step 2) Click on Manage Roles to add new roles based on your organization.

![image](https://user-images.githubusercontent.com/82079865/125250769-40be5a80-e314-11eb-8379-0d2dbf114b3a.png)

### Step 3) To create a new role called "developer",

Type "developer" under "role".
Click on "Add" to create a new role.
Now, select the Jenkins user permissions you want to assign to the "Developer" role.
Click Save

![image](https://user-images.githubusercontent.com/82079865/125250856-56338480-e314-11eb-8782-721f00d17a48.png)

## How to Assign Roles in Jenkins
### Step 1) Now that you have created roles, let us assign them to specific users.

Go to Manage Jenkins
Select Manage and Assign Roles

![image](https://user-images.githubusercontent.com/82079865/125250931-68152780-e314-11eb-910b-973b2d3f597e.png)

### Step 2) We shall add the new role "developer" to user "guru99"

Selector developer role checkbox
Click Save

![image](https://user-images.githubusercontent.com/82079865/125250988-78c59d80-e314-11eb-8168-e6f4e799f896.png)

You can assign any role to any user, as per your need.

## How to Create Project Roles in Jenkins
You can create project specific roles under Project Roles.

### Step 1) In Jenkin's Manage and Assign Roles

Enter a role as "tester"
Add a pattern to this by adding tester.*, so that any username starting with "tester" will be assigned the project role you specify.
Click Add
Select privileges
Click Save

![image](https://user-images.githubusercontent.com/82079865/125253785-6436d480-e317-11eb-8011-2a34c4c7bde3.png)

