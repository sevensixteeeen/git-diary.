# git-diary

## What is git?
> git is a distributed version control system, that tracks changes in code or files. It allows us to save sanpshots (commits), manage branches and collaborate without chaos.
---
## What is github?
> github is a cloud platform that hosts git respositories and enables collaboration, It's allows developers to store, share and manage their code online.
---
## Basic git commands
```bash 
git init      "initialize respository"
git add       "stage changes"
git commit -m "messages/save snapshot"
git status    "check changes"
git branch    "create branch" 
git checkout  "switch branch"
git merge     "combining multiple branch"
git push      "upload to github"
```
---
## git worklflow
> Working directory --> Staging --> Local repo --> Github
```steps
Working Directory
    ↓
git init
    ↓
Create file
    ↓
git status
    ↓
git add
    ↓
git commit
    ↓
git push
```
## Key concepts of git
- **Repository:** A folder where Git tracks your project and its history.
- **Clone:** Make a copy of a remote repository on your computer.
- **Stage:** Tell Git which changes you want to save next.
- **Commit:** Save a snapshot of your staged changes.
- **Branch:** Work on different versions or features at the same time.
- **Merge:** Combine changes from different branches.
- **Pull:** Get the latest changes from a remote repository.
- **Push:** Send your changes to a remote repository.
---
### Working with git

- Initialize Git on a folder, making it a **Repository**
- Git now creates a hidden folder to keep track of changes in that folder
- When a file is changed, added or deleted, it is considered **modified**
- You select the modified files you want to **Stage**
- The **Staged** files are **Committed**, which prompts Git to store a **permanent** snapshot of the files
- Git allows you to see the full history of every commit.
- You can revert back to any previous commit.
- Git does not store a separate copy of every file in every commit, but keeps track of changes made in each commit!

## Configure Git
``` user:
git config --global user.name "your name"
git config --global user.name "716@example.com"
```
- use **--global** to set the value for every repository on your system.
- use **--local** (the default) to set it only for current repository.

