
# Git Commands for daily usage: 
### create a new repository on the command line
**Steps**: initialize -> add all files > commit message > main branch shifting > adding branch > pushing to main branch 

    git init
    git add .
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/abdullahmiraz/test-delete.git
    git push -u origin main

### push an existing repository from the command line

    git remote add origin https://github.com/abdullahmiraz/test-delete.git
    git branch -M main
    git push -u origin main



## Others: 
removes untracked files from the working tree that match patterns specified in the `.gitignore` file.

    git clean -fX

