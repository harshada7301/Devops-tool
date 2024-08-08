# $${\color{blue}Git-commands}$$


![work2](https://github.com/user-attachments/assets/31a45633-10b6-466c-a33c-13994e50ae12)

git basic commands


### Create a Repository: Navigate to your project directory and initialize a Git  new repository.
```
git init
```

### cloning an existing repository :‘git clone’ is used to create a copy or clone of remote repositories.
```
git clone <repo url >
```
### git workflow
There are four core elements in the git workflow: Working Directory, Staging Area, Local Repository and Remote Repository.
![git 1](https://github.com/user-attachments/assets/0146ee36-47e3-4dc7-b897-326930c06b9a)

 A file in a working directory can be in one of the following states:

Staged: File with the updated changes is marked to be committed to the local repository but not yet committed.
Modified: File with the updated changes is not yet stored in the local repository.
Committed: Updated changes made into a file are safely stored in the local repository.

### Git basic terminologies

 A git command used to add a file from working directory to the staging area.
```
git add .

git add < file name >
```
 A git command used to add all files that are staged to the local repository.
```
git commit -m "   "
```
**To Show commit histroy**
```
git log

git log --oneline
```
**Show Creditals which is add**
```
git config --list
git config
```
**show tracked and untracked files**
```
git status
```
 used to add all committed files in the local repository to the remote repository.
```
git push origin main 
```

 to get files from remote repository to the local repository but not into the working directory.
```
git fetch
```
 used to get files from local repository into the working directory.
```
git merge
```
used to get files from remote repository directly into the working directory. It is equivalent to git fetch and git merge.
```
git pull
```
used to restore file from staging area to working dirctory 
```
git restore --stage < filename >
```
To add a remote repository in Git
```
git remote add <name> <url>
```


