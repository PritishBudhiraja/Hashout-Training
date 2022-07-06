# Central Repository

The repository that holds every other code of each contributor.

# Origin Repository (The Forked Repo)

The repository that we have made via Fork(making a copy) the central repository.
Copy the SSH Keys of this repo and make a local repository for the same.
**git clone SSH Keys**

# Git Initialisation

To make that particular folder a git repository in local we use **git init** command.

# Git Status

It displays the state of the working directory and the staging area.
**git status**

# Git Staging Area

To make the file pushed from Untracked/Modified Stage to Staged Area where it can go for commiting process we use **git add** command
**git add <file_name>** to add a particular file in staging area.
**git add .** to add all files in the staging area.

# Git Commit

To make the file changes commit to be pushed to the origin repo.
**git commit -m "Commit Message"**

# Git Push

To push the commited changes to the origin repo.
**git push origin**

# Git Pull Command

It's a combination of git fetch & git merge so basically it will first fetch from the repository mentioned and the merges the code with the origin repository

**git pull central branchName**
means
**git fetch central**
**git merge central/branchName**

# Git Stash

To stash the local changes.
**git stash**

# Git Stash Pop

write working from top of stash stack
**git stash pop**

# Git Stash Drop

discard the changes from top of stash stack
**git stash drop**

# Git Checkout to Different Branch

To change the branch and add the branch in local repository
**git fetch central**
**git checkout branchName --track central/branchName**
**git push -u origin** to create a branch in the origin repo

# Git Add A Branch

To add a branch in a repo.
**git remote add branchName URL**

# Git Cherry Pick

git cherry-pick is a command that enables arbitrary Git commits to be picked by reference and appended to the current working HEAD. Cherry picking is the act of picking a commit from a branch and applying it to another.

**git cherry-pick commid-id -m1**

Reference Materials:
https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud#create-the-repository
https://www.freecodecamp.org/news/git-and-github-crash-course/
https://www.freecodecamp.org/news/git-for-professionals/
