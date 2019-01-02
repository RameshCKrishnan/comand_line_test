## Command Line test
I am about to test git commands

## What
Some random commands

Committing chunks  of a file

Committing only the changes by picking them

Cherry-pick

Revert commit - remote - but not shared with anyone else or not pushed to anyother branch

Reset commit - local

Checkout - reset working copy of the file


## How
git add -p <file>  for staging the portion of a file
gives the option to either stage hunk(s) or all the changes
option e: gives greater flexibility to selectively pick the changes that needs to be committed

git cherry-pick <commit>: 
cherry picks the selected commit  and adds the commit to the working copy 

git cherry-pick <commit1> <commit2>
to cherry pick more than one commit in the order from left to right

git cherry-pick -n <commit>: 
cherry picks the selected commit and applies the changes to the current working copy but doesn't add the commit

git reset <head~1> or <commit_hash> to reset your local branch to previous commit
git push -d origin <remote_branch> to delete the remote branch
git push -u origin <remote_branch> to recreate the remote branch without the commit that was removed by reset

git remote => to see the remote name: typically "origin"
