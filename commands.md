# Important git commands 

### Begineer level commands

- `git init` -> it initilizes a new git repository. What is a git repository ?
 it is a folder managed by git where we can track all the changes we are making in the project.
- `ls -a` -> it lists all the files and folders in the current folder.
- `git status` -> it shows the status of the project.
- `rm -rf file_name` -> it removes the file_name file from the folder of the project.

A new version is also know as new commit. If we had to create a new version we have to create a 
new commit. 
Initially all the files and change are untracked. 

- `git add <filename>` -> starts tracking your new changes we are making in the project it adds all the files and folders in the  current folder to the staging area. By this we are telling git that we want to track these files and we want them in our new or next version. 
- `git add .` -> it adds all the files and folders in the current folder to the staging area.  
- `git commit -m "<message>"` -> this creates a new version on your previous changes.   
- `git log` -> it shows all the versions of the project.
- `cat <file_name>` -> it shows the content of the file. 
- `git checkout <version>` -> it checks out the specified version.
- `git branch <branch_name>` -> it creates a new branch.
- `git branch -d <branch_name>` -> it deletes a branch.
- `git checkout -b <branch_name>` -> it creates a new branch and checks it out.
- `git checkout <branch_name>` -> it checks out the specified branch.
- `git merge <branch_name>` -> it merges the specified branch.
- `git add remote origin <url>` -> it adds a remote repository.
remote helps to connect to a repository that might not abvailable in the local machine.             
- `git push origin <branch_name>` -> it pushes the changes to the remote repository.
- `git push -u origin <branch_name>` -> it pushes the changes to the remote repository. 
- `git cat-file <flag> <hash>` -> here falg can be of two types 
1. -t -> it shows the type of the hash
2. -p -> it shows the content of the hash
we have to give only 5-6 initial characters of the hash.
- `git log --oneline` -> it shows what commit the head is pointing too. 
head point to the latest commit. 
- `git add -p` -> it adds hunks to the staging area.
- `git pull <remote_name> <branch_name>` -> it pulls the changes from the remote repository.
- `git remote -v` -> it shows all the remote repositories.
- `git remote add <remote_name> <url>` -> it adds a remote repository.
- `git remote rm <remote_name>` -> it removes a remote repository.
- `git remote rename <old_name> <new_name>` -> it renames a remote repository.
- `git remote set-url <remote_name> <url>` -> it sets the url of the remote repository.
- `git remote set-url --add <remote_name> <url>` -> it adds the url of the remote repository.
- `git remote set-url --delete <remote_name> <url>` -> it deletes the url of the remote repository.
- `git remote set-url --push <remote_name> <url>` -> it pushes the url of the remote repository.
- `git remote set-url --push <remote_name> <url>` -> it pulls the url of the remote repository.
- `git remote set-url --push <remote_name> <url>` -> it fetches the url of the remote repository.
 