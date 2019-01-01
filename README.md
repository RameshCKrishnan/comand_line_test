## Command Line test
I am about to test git command

## What
Some random commands
Committing chunkst of a file
Committing only the changes by picking them
Cherry-pick
Revert commit - remote
Reset commit - local
Checkout - reset working copy of the file

## How
git add -p <file>  for stagin the portion of a file
gives the option to either stage chunk by chunk or all the changes
option e: give the greater flexibility by allowing to pick the changes that needs to be committed

git cherry-pick <commit>: 
cherry picks the selected commit and applies the changes to the current working copy and adds the commit

git cherry-pick -n <commit>: 
cherry picks the selected commit and applies the changes to the current working copy but doesn't add the commit



