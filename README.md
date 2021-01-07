# git-cheat-sheet

#### Create a github branch by url:
`https://github.com/samjones00/git-cheat-sheet/pull/new/branch-name`

#### undo last commit:
`git reset HEAD~`

#### Create new branch off another:
`git checkout -b myFeature originalBranch`

#### List differences between branches by merges:
`git log --no-merges branchA ^branchB`

#### List differences between branches by commits:
`git log newbranch..oldbranch`

#### Removes Staged Tracked and UnStaged Tracked files
`git reset --hard`

#### Revert to commit
`git checkout commithash fullpath`

#### List differences between branches
`git diff --name-only SHA1 SHA2`

#### List commits formatted:
`git log --grep=Merged --pretty="%ad - %s - %an" --date=short`
