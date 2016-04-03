# Reflection

**What Git concepts were you struggling with prior to the GPS session?**
	- I was confused with merge conflicts before I did the GPS session.
**What concepts were clarified during the GPS?**
	- The merge conflict was cleared up a lot. I am still not 100% on it, but that probably is because I didn't actually get to do this GPS with a guide or a partner, which was my fault.
	- I also got to get more comfortable with the pull requests and just navigating through the github site.
**What questions did you ask your pair and the guide?**
	I didn't get to ask the guide or my pair any questions that I really had, which would have been extremely helpful. I will make sure not to miss another GPS.
**What still confuses you about Git?**
	- I am still not 100% on the merge conflicts like I said earlier, but I am sure once I deal with them more I will get more comfortable.
	- I would like to be more comfortable navigating through the website and cloning/fetching repos. Again I am sure that this will come with experience.
	
# My answers to the Release's and discussion.

 <p>__Through some poor preperation on my part I was 45 minutes late to my GPS 1.1. I was told to do the work by myself and write down my thoughts on any of the release's discussions that involved your pair. Below is what I came up with.__</p>

1. You want to make feature branches because you do your editing/coding on branches. You don't want to make any changes to the code on the master branch that you don't know will work perfectly. Branches are pretty much the place where you make edits to code or add code that might not work correctly at first.

2. Git tracks changes through a series of snapshots. If you have made and committed changes git will store them. If you haven't committed your work in git, it wont save the changes.

3. The commit messages that you use should be detailed on what you have changed. The best practices are to commmit after you have made any changes to any files. The best practices are to add and commit files  early and often. 

4. I explained what a branch is pretty thoroughly in the first answer, but it is a place where it is safe to make changes/add code to a project. To create a branch you would:
	- First find out what branch you are currently on (only applicable if you're not in a new repo) by using the command git branch.
	- Second run the command git checkout BRANCH-NAME to navigate to another branch. If you are on a new repo and need to create a NEW branch you would run the command git checkout -b NEW-BRANCH-NAME to create and move to it.
	-Third to move between different branches you use the command git checkout BRANCH-NAME.

5. The command git fetch downloads from another repository. Git <remote> is usually going to be git origin <branch> in our case. Git merge <remote>/<branch> merges the branch or repo that we are trying to get.

6. The merge conflict happened because the file on the branch small_conflict and the master branch weren’t the same.

Release 6 Discussion:
	- Good git workflow is making sure you do certain things, such as adding branches, adding and committing files, make pull requests and merge your branches if they don’t have any issues. If they do have issues find the issues and fix them.