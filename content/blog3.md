Title: Introduction to Git/Github
Date: 2016-12-22 1:00
Category: Git/Github


Introduction to Git
Git is a series of commands that helps us to keep track of all the different versions of a file.Git allows us to do collaboration, manage conflicts 
and recall a specific version later.

A git projects consists of three parts:
a) working directory where you create, modify and/or delete files;
b) staging area where you list changes you make to the working directory;
c) repository: where git permanently saves all the changes.

The followings are some useful commands we need to use to set up a repository.

1) git init: this command initializes all the tools that "git" needs to begin tracking of changes in a file.

2) git status: shows the status of the changes after you modify a file.

3) git add filename: used to add a file to the staging area.
Note: git add . adds all the changes of all the files to the staging area.

4) git diff filename: used to show the differences between the working directory and the staging area.

5) git commit -m "The comments" : used to permanently stores changes from the staging area inside the repository

6) git log: Shows the commit logs


Introduction to Github
Github is a developer social network.Github uses git and hosting service for the git repository.


Introduction to repository:
A repository holds all versions of a file and tracked changes.
A brand new repository can be created by git init and an existing remote repository can be cloned to the local machine by git clone.
