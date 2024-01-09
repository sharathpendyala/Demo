# Demo

-----------------------------Git Commands From Beginning ---------------------------------------------------

1. Initialize a new empty repository in the local folder.
2. Add remote origin link to push/pull your changes
3. Verify the remote
4. Change the name of the origin to main
5. push your changes after committing them.

# git init                           --> Initializing empty repository
# git remote add origin "Link"       --> Linking a remote origin
# git remote -v                      --> To check the remote
# git branch                         --> To check the branch
# git branch -M main                 --> To rename the branch to "main"
# git push -u origin main            --> Push changes to remote github repository

------------------------------------------------------------------------------------------------------------

 
----------------------------- Git Commands For Cloning -------------------------------------------------------

                    CLONE --> CHANGES --> ADD --> COMMIT --> PUSH

1. To push into github first create a repository in your github account.
2. Now from the local files/folder push them into the repository.
3. U need to follow the below commands to push them into the repo.

# git add .               --> To push all the changes into github
# git commit -m "message" --> To commit all the changes
# git push origin main    --> To finally push all the committed changes into github from the local folder.
 
--------------------------------------------------------------------------------------------------------------


------------------------------ Git Branching and Pull Request(PR) --------------------------------------------
1. Create a new branch and checkout to the new branch.
2. Verify your current branch.
3. Push your changes into the current branch.
4. Merge your branch into the main branch.

# git checkout -b "new_branch_name"
# git branch
# git push origin "new_branch_name"
# git checkout main
# git merge "new_branch_name"

---------------------------------------------------------------------------------------------------------------