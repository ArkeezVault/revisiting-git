# Git Cheat Sheet

This repo is my my cheat sheet for git command while refreshing on git and learning more advanced git commands

## Basic Commands

To copy a project to your local machine

```
git clone <repo url>
```

To show the edited files that have not been committed yet

```
git status
```

To track file changes and newly created files

```
git add <file> # track specific file
git add . # track all the files in this directory
```

To commit changes to a repo

```
git commit -m "some message"
git commit -m "commit title" -m "commit description"
```

To push changes to live repo

```
git push origin main
```

`origin` - location or repo
`main` - the branch we push to

To create a git repo locally

```
git init
```

To connect our local repo with the one on github

```
git remote add origin <remote repo url>
```

To check remote repo connected to local one

```
git remote -v
```

To set upstream to use `git push` on initial push use

```
git push -u origin main
```

To pull changes from remote

```
git pull -u origin main # if upstream not set
git pull
```

As shortcut to commit modified files

```
git commit -am "some message"
```

To pull changes from main to feature branch

```
git merge main
```

To undo an add or commit

```
git reset # for add
git reset HEAD~1 # undo last commit
```

## Git Branching

Branches are used to safely add new features without risking breaking your code

To view Branches

```
git branch
```

To create a new branch

```
git checkout -b <name>
```

To switch Branches

```
git checkout <name>
```

To merge branch to main locally

```
git merge
```

To view changes in code

```
git diff
```

Push branch to github, then create pull request to merge branch

```
git push -u origin <branch-name>
```

To remove branch after merge

```
git branch -d <branch-name>
```
