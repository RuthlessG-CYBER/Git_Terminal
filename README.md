# Git Cheat Sheet

## Configuration
Set up your Git identity

- `git config --global user.name "Your Name"` - Sets your name for commits
- `git config --global user.email "you@example.com"` - Sets your email for commits
- `git config --list` - Lists all Git settings

## Repository Setup
Start or clone a repository

- `git init` - Creates a new Git repository
- `git clone <repo_url>` - Copies a remote repository

## Staging and Committing
Manage file changes

- `git add <file>` - Stages a file for commit
- `git add .` - Stages all changed files
- `git commit -m "Message"` - Commits staged changes

## Branching
Work with branches

- `git branch` - Lists all branches
- `git checkout -b <name>` - Creates and switches to a new branch
- `git checkout <name>` - Switches to a branch
- `git branch -d <name>` - Deletes a branch (use `-D` to force)
- `git merge <branch>` - Merges a branch into the current one

## Remote Repositories
Sync with GitHub or other remotes

- `git remote add origin <url>` - Links to a remote repository
- `git push -u origin main` - Pushes to remote main branch
- `git push` - Pushes commits to remote
- `git pull` - Fetches and merges remote changes

## Status and History
Check repository state

- `git status` - Shows working directory status
- `git log` - Shows commit history
- `git log --oneline --graph` - Shows compact commit graph

## Undoing Changes
Revert or reset changes

- `git reset HEAD <file>` - Unstages a file
- `git restore <file>` - Discards file changes
- `git revert <commit>` - Undoes a commit
- `git reset --hard <commit>` - Resets to a commit (careful)

## Stashing
Temporarily save changes

- `git stash` - Saves uncommitted changes
- `git stash apply` - Reapplies stashed changes
- `git stash list` - Lists all stashes
- `git stash pop` - Applies and removes latest stash
