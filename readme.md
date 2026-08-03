

#Cmds

```
How to Start Day
Open Github
Swap to Safety
git commit safety
git pull origin safety

Then
checkout your dev branch
git checkout tinkDev
git merge safety
This will merge safety into your dev branch.

To finish the day
From yours push
then
git checkout safety
git commit safety
git pull origin safety
git merge tinkDev
git push origin safety



rm .git/index.lock // removes locks placed into the annoying git. 
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

ASpicer@Desktop-SpicerAlexander MINGW64 /c/Unity/School/Project and Portfolio2/StudentProject (spicerDev)
$ git checkout safety
Switched to branch 'safety'
Your branch is up to date with 'origin/safety'.

ASpicer@Desktop-SpicerAlexander MINGW64 /c/Unity/School/Project and Portfolio2/StudentProject (safety)
$ git pull origin safety
From https://github.com/SlayerzDY/Team-Name-Random
 * branch            safety     -> FETCH_HEAD
Already up to date.

ASpicer@Desktop-SpicerAlexander MINGW64 /c/Unity/School/Project and Portfolio2/StudentProject (safety)
$ git push origin safety
Everything up-to-date

ASpicer@Desktop-SpicerAlexander MINGW64 /c/Unity/School/Project and Portfolio2/StudentProject (safety)
$ git checkout spicerDev
Switched to branch 'spicerDev'
Your branch is up to date with 'origin/spicerDev'.

ASpicer@Desktop-SpicerAlexander MINGW64 /c/Unity/School/Project and Portfolio2/StudentProject (spicerDev)

```
