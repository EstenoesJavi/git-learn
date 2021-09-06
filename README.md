# git-learn
This repository was created to learn about git and refresh memory when be need.

## Commands

- git status:  Show status of current branch.
- git log: Show commits in current branch.
- git log --oneline: Show commits in current branch in one line.
- git add nameFile: Add file in stage.
- git commit -m 'message': Add message to current changes before pushing it.
- git commit -am 'message': In case of you created a new file use (git add . && git commit -am 'message').
- git reset --hard codeCommit: Use in case you want to go back to a previous commit.
- git commit -m 'message' -amend: Use in case you want to change current message commit.
- git checkout: Change branch.
- git branch nameBranch: Create a branch.
- git checkout -b branchName: Create a new branch and stand on it.
- git pull: Download changes of remote repository into current branch.
- git push: Upload current changes in branch into remote branch.
- git merge nameBranch: Upload changes in any branch into current branch.

### Upload existing repository in local
-----
- git init: Start local repository. 
- git remote Add origin urlRemoteRepository: Add remote repository into current local repository.
- git git pull origin master or
- git add .
- git commit -m 'message'
- git push origin master

![git](https://img.devrant.com/devrant/rant/r_1840117_3JUPn.jpg)
