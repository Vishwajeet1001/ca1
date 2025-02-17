# Git Commit States

## 1. Untracked
A newly created file that Git does not yet track. Running `git status` will show it under "Untracked files."

## 2. Staged
A file that has been added to the staging area using `git add <filename>`. Git is now tracking changes, but they are not yet saved in the repository.

## 3. Committed
A file whose changes have been permanently recorded in the repository with `git commit -m "Commit message"`. The commit creates a snapshot of the file at that point.

Use `git status` to check the state of files and `git log` to view the commit history.

