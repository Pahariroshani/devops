# devops class
Learning git from github
git init: to initialize an empty repository

git clone <repo url>: to clone the remote repository into local repository

After cloning "cd reponame/directory"

git branch: to check which branch we are working on 

git branch -a: to display all the branches

git checkout -b <branch name>:to create a NEW branch
Example: git checkout -b my-local-branch

git add: to add the file (make the files in to tracking from untracked mode)

git commit -m "commit message": to create the commit (version)

git push origin <branch name>: to push the local changes to remote repository for the respective branch

git pull: to pull the branch in to the current branch 

git diff: to see the difference in local machine (this has to be performed before git add)

git status : to check the current status of the file in repo (like, untracked or added or any commits to be made)

git log : to view the commit information

git push --upstream origin <branch name> : instead of command git push origin <branch name>, you can use this command to set up the upstream.                                           for a particular branch, so that when you have to push the changes you don't have to type branch 
                                           branch name. it automatically recognizes the branch you are pushing from where you set up upstream                                           But, once you checkout to another branch, you may need to set upstream for another branch.

