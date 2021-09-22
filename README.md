#Git Cheat Sheet

###Workspace :arrow_right: Staging

```
#git add <filename> - adds file to staging
#git add . - adds all files to staging
#git commit -m “<commit message>” - commits our changes
#git commit -am “<commit message>” - adds and commits our changes
#git restore --staged <filename> - removes file from staging
#git restore --staged . - removes all currently staged files
```

###Workspace :arrow_left: Staging

```
git checkout -- <filename> - brings last staged version of file to your workspace
git checkout -- . - brings all last changes staged to your workspace
```

###Staging :arrow_right: Remote

```
git push
```

###Workspace :arrow_left: Remote

```
git fetch
git pull
git reset --hard <branch name/commit SHA> - changes current local branch’s head to specific branch/commit
```

###Branches

```
git checkout/switch <branch name> - brings branch to workspace
git checkout -b - creates new branch and brings to workspace
git merge <branch name> - merges branch into current checked out branch
git rebase <branch name> - updates
```

###Informational

```
git log (-n <number>) - returns branch activity info (optional n for number of logs)
git status - shows branch and working three status
git diff - show difference between staged and workspace.
git diff <branch name/commit SHA>..<branch name/commit SHA> - compares branches/commits.
git show <commit SHA> -show commit info.
``
```
