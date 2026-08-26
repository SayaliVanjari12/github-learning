git status: whats going on rn?
current branches, modified files, staged files, untracked files, commits, everything.
git branch: an independent line of development
(* =  currently checkedout branch)
git switch: used to switch between branches
(eg: git switch -c feature/git-command-notes, -c = crate a new branch and switch to it)
git add: stage the changes
(add changes from current direct to the staging area)
git commit: commit the changes
(commit!=push, staging area to local repo)
git log: logs the commit history
git push: add/push changes from local repo to github/remote repo (the final changes happen here)
git pull: get the latest changes from github and integrate them into my local branch
git fetch: download info about whats chnged on github, but dont integrate those changes into my current branch yet
git diff: shows what has changed(in detail)