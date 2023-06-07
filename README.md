## Git Commands

At first need to install git if don't have then after perform to set name and email as below

```bash
git config --global user.name “Your Name”
git config --global user.email “you@example.com”
git config --global color.ui auto
ssh-keygen
```
## basic commands

```bash
git clone <URL>
git status
git add .
git commit -m "comments"
git push
git revert <code>
git pull
```

## basic commands for branch
```bash
git branch
```
provide list of branch
```bash
git branch <branch-name>
``` 
creating branch
```bash
git checkout develop
``` 
Can start working on develop branch
```bash
git checkout -b <branch-name>
``` 
Another way to create and checkout into the branch
```bash
- git merge <branch-name>
``` 
can merge branch 
```bash
- git branch --delete <branch-name>
- git branch -d <branch-name>
``` 
can remove branch from the local repository
```bash
git push --delete origin <branch-name>
```
can remove branch from the remote repository
```bash
git branch -r
```
can check remote branch
```bash
git fetch --prune
git fetch -p
```
delete remote Refs that were removed from the remote repository
```bash
git fetch
git fetch -all
```
can fetch remote repo changes or Fetch changes from the remote, but not update tracking branches
```bash
git rebase <branch-name>
```
can rebase the parent branch
```bash
git revert <commit-id>
```
can revert based on commit id
