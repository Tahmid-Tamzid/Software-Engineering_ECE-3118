# 1710010_Tahmid Tamzid

# Git Master Branch
```
The master branch is a default branch in Git. It is instantiated when first commit made on the project.Master branch is the branch in which all the changes eventually get merged back. It can be called as an official working version of any project.
```
# Operations on Branches
```
The git branch command allows to create, list, rename and delete branches.
```
# Create Branch

 A new branch can be created with the help of the git branch command.
 ```
 $ git branch  <branch name> 
 ```
# List Branch
You  All of the available branches in a repository can be listed by using the command.
```
$ git branch --list  
```
# Delete Branch
A specific branch can be deleted using the command.
```
$ git branch -d<branch name> 
```
# Switch Branch
One can switch between two branches with the git checkout command.
```
$ git checkout <branch name>
```
# Merge Branch
Git allows to merge the other branch with the currently active branch. Two branches can be merged with the help of git merge command.
```
$ git merge <branch name> 
```
# Git Merge
```
In Git, the merging is a procedure to connect the forked history. It joins two or more development history together.
```
# The "git merge" command
The git merge command is used to merge the branches.
```
$ git merge <query>  
```
 To merge the specified commit to currently active branch.
 ```
 $ git merge <commit> 
 ```
 To merge a specified commit into master, the log command is used to find the particular commit id.
 ```
 $git log 
 ```
 To merge the commits into the master branch, switch over to the master branch.
 ```
 $ git checkout master  
 ```
 Switch to branch 'master' to perform merging operation on a commit, the git merge command along with master branch name is used.
 ```
 $ git merge master
 ```
 Git allows merging the whole branch in another branch. To merge the whole branch in the active branch below command is used.
 ```
 $ git merge <branchname> 
 ```
 # Git Merge Conflict
 When two branches are trying to merge, and both are edited at the same time and in the same file, Git won't be able to identify which version is to take for changes. Such a situation is called merge conflict.
 # Resolve Conflict:
 To resolve the conflict, it is necessary to know whether the conflict occurs and why it occurs. Git merge tool command is used to resolve the conflict. 
 ```
 $ git mergetool 
 ```
 # Git Pull
 The term pull is used to receive data from GitHub. It fetches and merges changes from the remote server to working directory. The git pull command is used to pull a repository.
 ```
 $ git pull <option> [<repository URL><refspec>...]  
 ```
 # Git Pull Remote Branch
 Git allows fetching a particular branch. Fetching a remote branch is a similar process as in git pull command. The only difference is we have to copy the URL of the particular branch we want to pull. To do so, we will select a specific branch.
 ```
 $ git pull <remote branch URL> 
 ```
 # Git Push
 The push term refers to upload local repository content to a remote repository. Pushing is an act of transfer commits from local repository to a remote repository. Pushing is capable of overwriting changes.
 ```
 $ git push <option> [<Remote URL><branch name><refspec>...]  
 ```
 # Git Push Origin Master
 Git push origin master is a special command-line utility that specifies the remote branch and directory. When there is multiple branches and directory, then this command assists in determining main branch and repository.
 ```
 $ git push origin master  
 ```