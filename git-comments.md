# GIT COMMENTS

1. ## Clone repository:
   ### cmd: ` git clone <repo_link>` 

   #### above the cmd helps to clone the repository

2. ## Branch creation:

   ### cmd: ` git checkout -b <NEW_BRANCH_NAME>`

   #### Creating the new branch with existing branch code 

3. ## Pull:
    1. **Same Branch**
        ### cmd: ` git pull <BRANCH_NAME>`

        #### To update current branch with new changes.
    
    2. **Other Branch**
        ### cmd: `git pull origin <OTHER_REMOTE_BRANCH>`

        #### Get changes from other branches.

4. ## ADD:

    ### cmd: ` git add .` (or) `git add <PARTICULAR FILE(S)>`

    #### Stage the changes (Ready to update changes from local to remote branch)

5. ## Commit:
    ### cmd:   `git commit -m <message>`

    #### After the all chages are staged, should give commit messages about current changes or anything (about current chages is recommended).

6. ## Push:

    1. T**method:1 (First Push)**

        ## cmd: `git push --set-upstream origin <BRANCH_NAME>`

        #### If your push from your new local branch to remote branch in first time, use above the cmt, otherwise use 2 method.  

    2 **Method:2**

       ### cmd: `git push <BRANCH_NAME>`

       #### After the commiting message push comment move the changes to remote branch

7. ## Merge:

    ### cmd: `git merge <LOCAL_BRANCH>`

    #### Update one local branch changes to another local branch in same machine
