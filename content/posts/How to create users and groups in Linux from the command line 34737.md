---
title: "You won't believe how easy it is to create users and groups in Linux with just one command!"
ShowToc: true 
date: "2022-11-15"
author: "Linda Killeen"
---
*****
# You Won't Believe How Easy it is to Create Users and Groups in Linux with Just One Command!

If you are new to Linux, you might think that creating users and groups is a complicated process. But, did you know that you can create them with just one command? Yes, you heard it right! With Linux, creating and managing users and groups is incredibly easy!

Here's how you can do it:

## Creating a User

To create a user, you can use the ```useradd``` command. This command creates a new user on the system. Here's the syntax for this command:

```sh
$ sudo useradd [options] username
```

Here, ```[options]``` are the various options that you can use with the ```useradd``` command, and ```username``` is the name of the user you want to create. 

For example, if you want to create a user with the name 'john', you can use the following command:

```sh
$ sudo useradd john
```

## Creating a Group

Creating a group is even easier than creating a user. You can use the ```groupadd``` command to create a new group. Here's the syntax for this command:

```sh
$ sudo groupadd groupname
```

Here, ```groupname``` is the name of the group you want to create. 

For example, if you want to create a group with the name 'developers', you can use the following command:

```sh
$ sudo groupadd developers
```

## Adding Users to a Group

Once you have created a group, you can add users to the group using the ```usermod``` command. Here's the syntax for this command:

```sh
$ sudo usermod -aG groupname username
```

Here, ```groupname``` is the name of the group, and ```username``` is the name of the user you want to add to the group.

For example, if you want to add the user 'john' to the 'developers' group, you can use the following command:

```sh
$ sudo usermod -aG developers john
```

## Conclusion

As you can see, creating users and groups in Linux is really easy with just a few simple commands. With the help of these commands, you can easily manage your system and its users. 

So, the next time you need to create a new user or group, don't worry, just use the commands we discussed above, and you'll be good to go!

{{< youtube W9c3xTcyB1s >}} 



Whether you're a serious admin or a casual user, chances are pretty good you will eventually need to add a new user and/or a group to a Linux system. 
Let's find out how.

 
## Requirements


The process of creating users and groups from the command is the same, regardless of which Linux distribution you use, so it doesn't matter which distro you use. You will, however, need a user with sudo privileges because this is an administrative task.
With that said, let's get to the creation of users and groups.

 
## Creating a new user


The first thing we're going to do is add a new user. I'll demonstrate by adding the user olivia but you can substitute whatever username you need for the user.

 
### 1. Log in to your desktop or server


To create this new user, log in to your desktop or server. If either has a GUI, you'll then need to open a terminal window from which you'll run the necessary command.

 
### 2. Create the new user


From the terminal window, create the user olivia with the command:
The above command will ask you a few questions:
New password (you'll type and verify a new password for the user)

 
Full NameRoom NumberWork PhoneHome PhoneOther


After answering the questions, you'll be asked to okay the information (type Y or N).
Of the above questions, the only one that is required is the password. The adduser command also automatically creates a home directory for the new user (unlike the useradd command which requires the -m option to create the home directory). 

 
## Creating a new group


Next, we'll create a new group. Groups are a very convenient way to hand over permissions to a directory or file to several users at once (instead of having to do so one user at a time). For that, you create the group, add users, and then change the file or directory ownership to the new group. 
Creating a new group is even easier than creating a user. Let's create a group named "editorial" with the command:
Boom!, group is ready for users.

 
## Adding users to a group


We now have the new user olivia and the new group editorial. Let's add olivia to editorial, so she can enjoy all the benefits that come with membership. To add olivia to editorial we make use of the usermod command with the -a (append) and -G (groups) options like so:
User olivia can issue the groups command to see that she's been added to the editorial group.

 
## Giving a folder group ownership


Let's say you've created the folder /DOCS and you want to change the ownership to editorial, so anyone in that group can work with the contents within. To change the ownership to the editorial group, the command would be:
The -R option stands for recursive and means it will apply the ownership not just to the parent folder but to all child folders and files. The :editorial option means we're only changing group ownership and not the actual owner.
At this point, olivia would be able to view the contents of the folder, but cannot write to that folder. To give the editorial group write permissions, we use the chmod command like so:
Now, any member of the editorial group will have write access to the /DOCS folder (and anything it contains).
And that, my dear Linux user friends, is how we add users and groups (and add users to groups) on the Linux operating system.




