# git-rewrite-history
Just contains some useful git commands to rewrite the history in various scenarios

## Scenario 1: Change commit message
```
  git commit --amend
```
## Scenario 2: Change last commit files
```
  git commit --amend --no-edit
```
## Scenario 3: Squashing multiple commits into one
```
  git rebase -i HEAD~3
```
## Scenario 4: Splitting a commit into multiple commits
```
  git rebase -i HEAD~2
  git reset HEAD^
```

## Scenario 5: Reordering the commits
```
  git rebase -i HEAD~2
```
## Scenario 6: Deleting a commit
```
  git rebase
```
