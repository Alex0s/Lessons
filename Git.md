#Git

##Introduction
* What is Git?
* What is Github?
* Why should you care?
* Novel Writing Analogy
* Installing Git(not really)

#Git Basics
* Git init
* Git status
* Git add
* Git commit -m ""

#Git Checkout
* Git Log
* Git Checkout
* git revert --no-commit 0766c053..HEAD
    
   HEAD
    O -> O -> O -> O
                   Master

#Git add/remove/ignore(https://www.youtube.com/watch?v=wTHPBO28nYQ)
//add all file from an extension, here html:
*git add *.html 
//add all files and folders
* git add -A
//remove a file from being committed
*git reset HEAD <file>
//ignore a file
Create a file called .gitignore and fill it with the name of the files

#Git Branches

// Listing all branches
* git branch

// create 7 switch branch:
* git checkout -b <name>

// merge 2 branchs
* git merge <nameOfBranch>
* 
//removing a branch
* git branch -d <branch_name>






#Cloning and Github Intro
* What is Github?
* Cloning an existing repo

#Pushing to Github
* Creating a repo on github
* Adding a remote
* Pushing to github