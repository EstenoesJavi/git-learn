# git-learn
This repository was created to learn about git and refresh memory when be need.

## Commands
- git status
- git log
- git log --oneline
- git add
- git commit -m 'message'
- git commit -am: in case of you created a new file use (git add . && git commit -am 'message')
- git reset --hard codeCommit: use in case you want to go back to a previous commit 
- git commit -m 'message' -amend: use in case you want to change current message commit
- git checkout: change branch
- git branch nameBranch: create branch
- git checkout -b branchName: create a new branch and stand on it
- git pull: download changes of remote repository into current branch
- git push: upload current changes in branch into remote branch
- git merge nameBranch: upload changes in any branch into current branch

### Upload existing repository in local

- git init
- git remote add origin urlRemoteRepository
- git git pull origin master or
- git add .
- git commit -m 'message'
- git push origin master

![git](https://img.devrant.com/devrant/rant/r_1840117_3JUPn.jpg)
