# Git Commit States

## 1. Untracked
A newly created file that Git does not yet track. Running `git status` will show it under "Untracked files."

## 2. Staged
A file that has been added to the staging area using `git add <filename>`. Git is now tracking changes, but they are not yet saved in the repository.

## 3. Committed
A file whose changes have been permanently recorded in the repository with `git commit -m "Commit message"`. The commit creates a snapshot of the file at that point.

Use `git status` to check the state of files and `git log` to view the commit history.


## Importance of Git History in Version Control and Debugging

1. **Tracking Changes:**  
   - Git history allows developers to track modifications over time.
   - Helps in understanding why certain changes were made.

2. **Debugging and Bug Fixing:**  
   - Developers can find the exact commit where a bug was introduced.
   - The `git bisect` command helps in locating faulty commits.

3. **Collaboration:**  
   - Team members can see previous changes and contributions.
   - Commit history provides context for changes.

4. **Reverting Mistakes:**  
   - If a problematic change is committed, it can be reverted using `git revert` or `git reset`.

5. **Audit and Compliance:**  
   - Helps maintain a record of changes for security and compliance needs.
