# Git Commands:

| Command | uses for |
| ------- | ------- |
| git init | create new repository |
| git status | show status of files in working directory |
| git add | add files to a staging area in order to commit or save |
| git commit -m"commited message " | moves added files to repo also record time and message |
| git diff | to compare changes in the working directory against a previously commited version |
| git diff --staged | to ensure that you have directly staged all of your changes |
| git log | view the history of the repo and commit log |
| git show | view the changes made in the commit |
| git remote | to share changes from or to repo |
| git push | share your commits and push them to a remote repo |
| git pull | sync changes from a remote repo into your local machine |
| git fetch | downloads the changes from repo to seperate branch |
| git merge | merge the fetched changes into master |
| git checkout | access the branch |
| git checkout . | also will replace all files in the current directory | 
| git reset | move files back from staging area to the working directory |
| git reset | move files back from staging area to the working directory |
| git reset hard | combine of git reset + git checkout |
| git revert | undo the commits |
| git pull | = (get fetch + get merge) and also used to fix the conflict |
| git checkout -- ours staging .txt | pick local version |
| git checkout -- thiers staging .txt | pick remote version |
| git commit --no-edit | default commit message |
| git rebase | unwind changes and replying changes in branch(all in same branch)...it fix confict but maybe lose commits |
| git branch | create new branch |
| git branch -va | list all branches with last commit message |
| git branch -d | delete the branch |
