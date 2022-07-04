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
