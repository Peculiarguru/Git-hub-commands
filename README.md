# First-repository
Hello repo

# Git Hub Commands
## Configure the author name and email address to be used with zour commits.



- git config --global user.name "mmilaamen"
- git config --global user.email "mmiladaniel@gmail.com"

## Create a new repository
- git init

## Checkout a repository

- git clone /ssh path

## Add files
- git add .
- git add "filename"

## Commit changes to head (not to remote repo)
- git commit -m "file has changed"

## Commit any file that you have added with git add  
- git commit -a

## Send changes to the master branch of your remote repository
- git push origin master

## If you had not connected your local repo to a remote server
- git remote add origin "url"

## list all the repo 
- git remote -v

## Create a new branch
- git checkout -b "branchname"

## switch from one branch to another
- git checkout "branch name"

## list all the branches in your repo and also tell your current branch
- git branch

## delete the branch
- git branch -d "branch name"

## push the branch to your remote repository
- git push origin "branch name"

##  push all the branches to remote repository
- git push --all origin

## fetch and merge changes on the server to the remote
- git pull 

## To merge a branch 
- git merge "branch name"

## Analysis the changes
- git status

## History of the changes
- git log

## SSH key setup
- ssh-keygen -t ed25519 -c "emailaddress"
- ls -al -/.ssh
- cd .ssh
- cat ~/ssh/id_ed25519







