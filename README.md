# GitHelper

### Delete a local branch
`git branch -d branch_name`

### Remote branch appears in `git branch -a`, deleted on remote though
`git remote prune origin`

### Create a new branch and move onto it
`git pull origin branch_name` (dev)   // Pull changes from dev

`git checkout -b branchname`    // Create a new branch and checkout

### Change name of a local branch
If you want to rename a branch while pointed to any branch, do:

`git branch -m <oldname> <newname>`

If you want to rename the current branch, you can do:

`git branch -m <newname>`

### Push code to the remote, same branch currently working in

`git push origin HEAD`

### Force git pull
https://stackoverflow.com/questions/1125968/how-do-i-force-git-pull-to-overwrite-local-files

### List all branch

`git branch -a`
