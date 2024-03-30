# git_branching_learning
Git Branching Learning 

Step 1 = Create Branch
         Git branch "branch name"

Step 2 : Checkout branch
        Git checkout "branch name"

Step 3:  Create new file
        touch test2.txt

Step 4 : Get git status and commit and push
        git status
        git commit -m "added test file"
         git push -u origin MyNewBranch

Step 5 : Check in git remote repository
        
Step 6: Merge new branch in master branch
        git merge "branch name"
        

## Remove the Untracked File:
You can remove the untracked file .DS_Store from your working directory. You can do this using the following command:
git rm .DS_Store


## Move the Untracked File:
If you want to keep the file but move it out of the way temporarily, you can move it to a different location outside of the repository. You can do this using the following command:


mv .DS_Store /path/to/desired/location/
