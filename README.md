
# Git Commands for daily usage: 

 1. *create a new repository on the command line:*  
`git init`  
`git add .`  
`git commit -m "first commit"`  
`git branch -M main`     
`git remote add origin https://github.com/abdullahmiraz/test-delete.git`  
`git push -u origin main`  

 2.  *for daily usage:*   
 `git add .`  
`git commit -m "message here"`  
`git push`  

 3. *push an existing repository from the command line:*  
 `git remote add origin https://github.com/abdullahmiraz/test-delete.git`  
    `git branch -M main`  
    `git push -u origin main`  
    
 4.  `git init`: Initializes a new Git repository in the current directory.
 5.  `git clone <repository>`: Clones a remote repository to your local machine.
 6.  `git add <file>`: Adds a file or changes to the staging area.
 7.  `git commit -m <message>`: Commits the staged changes with a descriptive message.
 8.  `git status`: Shows the current status of the repository.
 9.  `git push`: Pushes the committed changes to a remote repository.
 10.  `git pull`: Fetches and merges changes from a remote repository to the local repository.
 11.  `git branch`: Lists all branches in the repository. 
 12.  `git checkout <branch>`: Switches to the specified branch.
 13.  `git merge <branch>`: Merges the specified branch into the current branch.
 14.  `git remote add <name> <url>`: Adds a new remote repository with the given name and URL.
 15.  `git remote -v`: Lists all remote repositories and their URLs.
 16.  `git log`: Displays the commit history.
 17.  `git diff`: Shows the differences between the working directory and the repository.
 18.  `git reset <file>`: Unstages a file, removing it from the staging area.
 19.  `git stash`: Temporarily saves changes that are not ready to be committed.
 20.  `git branch -d <branch>`: Deletes a branch.
 21. `git clean -fX` : removes all untracked files and directories from the working directory, including those specified in `.gitignore` files
 22. `git clean -n -fX` : perform a dry run and see which files would be removed
 23. `git submodules` : [git submodule repo](https://github.com/abdullahmiraz/git-submodules) create a repo within a repo and update them selectively/individually.  


## Problems Fix:
| Serial | Solve              | Problem                                          |
| ------ | ---------------- | --------------------------------------------- |
| 1      |  *reset the origin url* | HEAD related problem comes, remote the origin url   |
| 2      |  `git rm --cached . -rf` |fatal: in unpopulated submodule |
| 3      | git pull origin <branch-name> --allow-unrelated-histories  | fatal: refusing to merge unrelated histories
 

