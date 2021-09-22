# Git Cheat Sheet

### Workspace :arrow_right: Staging

```
git add <filename> - adds file to staging.
git add . - adds all files to staging.
git restore --staged <filename> - removes file from staging.
git restore --staged . or git reset HEAD - unstages all currently staged files.
```

### Staging :arrow_right: Local

```
git commit -m “<commit message>” - commits our changes.
git commit -am “<commit message>” - adds and commits our changes.
git commit --amend -m “<commit message>” - overides last commit with current.
```

### Workspace :arrow_left: Local

```
git checkout -- <filename> - brings last local version of file to your workspace.
git checkout -- . - brings all last changes on local to your workspace.
```

### Local :arrow_right: Remote

```
git push origin <branch name> - pushes commit to remote branch
```

### Local :arrow_left: Remote

```
git fetch <branch name> - downloads a remote branch to local branch
git fetch --all - brings all branches on the remote repo to local
```

### Workspace :arrow_left: Remote

```
git pull origin <branch name> - fetches a remote branch and merges it with your local, bringing changes to the workspace.
git reset --hard <branch name/commit SHA> - changes current local branch’s head to specific branch/commit
```

### Branches

```
git checkout/switch <branch name> - brings branch to workspace
git checkout -b - creates new branch and brings to workspace
git merge <branch name> - merges branch into current checked out branch
git rebase <branch name> - updates current branch with forward work of branch stated
```

### Informational

```
git log (-n <number>) - returns branch activity info (optional n for number of logs)
git status - shows branch and working three status
git diff - show difference between staged and workspace.
git diff <branch name/commit SHA>..<branch name/commit SHA> - compares branches/commits.
git show <commit SHA> -show commit info.
```
