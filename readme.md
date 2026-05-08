#Cmds

```
git init // Creates a new repository
git add <fileName> // Adds single file to stage
git add -A // Adds all changes to the stage, Also adds removal of files as well. 
git commit -m '<msg>' // Performs a commit 
git branch // Creates a branch
git checkout -b '<branchName>' // Creates and checksout a new branch.
git status // Help Tells me where im at. 

git merge <branchName> // Merges a branch
git checkout <branchName> // Changes the branch we are on.

git log // Gives a history of all the commits.
clear // Removes all the interface in the terminal

git remote add <origin> <url> // the name is origin. The URL will be provided to us. 
git remote add origin https://github.com/flamingtoast201/gitDemo.git
git push origin main // Matters which branch goes up first. 
git pull origin <branchName> // Gets and pulls the origin

git reset --hard <wholeCommitId or Tag> // sends you back to a previous version. 
git push --force // Pushes regardless of whats going on. Only when you know your current version is the right version.
```
