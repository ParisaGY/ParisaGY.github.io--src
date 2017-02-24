Title: Introduction to git branching
Date: 2016-12-22 1:00
Category: Git/Github

Introduction to git branching

Git Branching is used when you want to add a new feature or fix a bug, you spawn a new branch to encapsulate your changes. 
This makes ensure that unstable code is never committed to the main code base, and it gives you the chance to clean up your feature’s history before merging it into the main branch.

The followings are comments used to make a new branch.

a) git branch nameofbranch
b) git check out nameofbranch
Note: we can use git checkout -b nameofbranch which works as steps a and b.
c) git merge nameofbranch: moves the work from branch into the master, merge the branch into the master when master is selected (have asterisk).
d) git rebase master: adds the branch to the master when branch is selected.
e) git merge nameofbranch: merges the branch to the master
f)git branch -d nameofbranch
