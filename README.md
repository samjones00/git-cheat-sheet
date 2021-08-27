# git-cheat-sheet

## Cleaning a branch

#### Discard all local changes
`git clean -df`\
`git checkout -- .`

#### Revert to a previous commit (losing all uncommitted changes)
`reset --hard 01b34fa`

#### Removes Staged Tracked and UnStaged Tracked files
`git reset --hard`


## Managing commits

#### Undo last commit:
`git reset HEAD~`

#### Revert to commit
`git checkout commithash fullpath`

## Branch management

#### Create new branch off another:
`git checkout -b myFeature originalBranch`

## List differences

#### List differences between branches by merges:
`git log --no-merges branchA ^branchB`

#### List differences between branches by commits:
`git log newbranch..oldbranch`

#### List differences between branches
`git diff --name-only SHA1 SHA2`

#### List commits formatted:
`git log --grep=Merged --pretty="%ad - %s - %an" --date=short`

## Github specific

#### Create a github branch by url:
`https://github.com/samjones00/git-cheat-sheet/pull/new/branch-name`