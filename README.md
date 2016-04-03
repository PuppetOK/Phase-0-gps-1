# Phase-0-gps-1

1. You want to make feature branches because you do your editing/coding on branches. You don't want to make any changes to the code on the master branch that you don't know will work perfectly. Branches are pretty much the place where you make edits to code or add code that might not work correctly at first.

2. Git tracks changes through a series of snapshots. If you have made and committed changes git will store them. If you haven't committed your work in git, it wont save the changes.

3. The commit messages that you use should be detailed on what you have changed. The best practices are to commmit after you have made any changes to any files. The best practices are to add and commit files  early and often. 

4. I explained what a branch is pretty thoroughly in the first answer, but it is a place where it is safe to make changes/add code to a project. To create a branch you would:
	- First find out what branch you are currently on (only applicable if you're not in a new repo) by using the command git branch.
	- Second run the command git checkout -b NEW-BRANCH-NAME
To navagate between branches you would just run the git checkout BRNACH-NAME. If you aren't certain what branch you're on you would first run the git branch command to find out.

The commands that have been used so far:
git clone
	cloned the newly created REPO
git touch
	made the awesome_page.md
git push origin master
	pushed the master branch to github and updated it with the awesome_page.md file
git checkout -b 
	made the add-command-log branch to work on
subl README.md
	Opened the README.md file.