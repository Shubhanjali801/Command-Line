

# 🟢 **1. Git Setup**

```
git init                    # Initialize a new Git repository
git clone <url>             # Clone a remote repository
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list           # Show all git config settings
```

---

# 🔵 **2. Basic Snapshotting**

```
git status                  # Show changes
git add <file>              # Add a file
git add .                   # Add all files
git reset <file>            # Unstage a file
git reset                   # Unstage everything
git rm <file>               # Remove a file
git mv <old> <new>          # Rename a file
```

---

# 🟣 **3. Commit Commands**

```
git commit -m "message"             # Commit
git commit -am "message"            # Add + Commit tracked files
git commit --amend                  # Modify last commit
```

---

# 🔶 **4. Branch Commands**

```
git branch                          # List branches
git branch <name>                   # Create branch
git checkout <name>                 # Switch branch
git switch <name>                   # New way to switch
git switch -c <name>                # Create + switch
git merge <branch>                  # Merge branch
git branch -d <name>                # Delete branch
git branch -D <name>                # Force delete branch
```

---

# 🔷 **5. Remote Repository**

```
git remote -v                       # Show remotes
git remote add origin <url>         # Add remote
git remote remove origin            # Remove remote
git remote set-url origin <url>     # Change remote URL
```

---

# 🟡 **6. Push & Pull**

```
git push origin main                # Push to main
git push -u origin main             # Set upstream
git push                            # Push
git pull                            # Pull latest from remote
git fetch                           # Fetch updates only
git pull --rebase                   # Rebase pull
```

---

# 🔺 **7. Undoing Things**

```
git checkout -- <file>              # Undo file changes
git reset --hard                    # Reset everything
git reset --hard HEAD~1             # Delete last commit
git restore <file>                  # Restore changes
git revert <commit>                 # Create undo commit
```

---

# 🟤 **8. Viewing History**

```
git log                             # Full commit history
git log --oneline                   # One-line history
git log --graph                     # Branch graph
git show <commit>                   # Show details of a commit
git diff                            # Compare unstaged changes
git diff --staged                   # Compare staged changes
```

---

# ⚫ **9. Stash Commands**

```
git stash                           # Save work temporarily
git stash list                      # List stashes
git stash pop                       # Restore and delete stash
git stash apply                     # Restore without deleting
git stash drop                      # Remove a stash
```

---

# 🔘 **10. Tags**

```
git tag                             # List tags
git tag <tagname>                   # Create tag
git tag -a <tagname> -m "msg"       # Annotated tag
git push origin <tagname>           # Push tag
git push origin --tags              # Push all tags
```

---

# 🟠 **11. GitHub Authentication**

```
git config credential.helper store  # Store credentials
git credential-manager uninstall    # Remove manager
```

---

# 🟣 **12. Advanced Commands**

```
git cherry-pick <commit>            # Copy a commit to another branch
git rebase <branch>                 # Rebase
git reflog                          # Git history of HEAD
git bisect                          # Debug using binary search
git blame <file>                    # Show who changed each line
```

# A. Basic Commands:

git init: How do you initialize a new Git repository in an existing directory?
git clone <repository-url>: How do you create a local copy of a remote repository?

git add <file> / git add .: What is the purpose of git add, and how do you stage specific files or all changes?
git commit -m "message": How do you commit staged changes to the repository with a descriptive message? 

git status: How do you check the current state of your working directory and staging area?
git log: How do you view the commit history of a branch?

git push: How do you upload your local commits to a remote repository?
git pull: How do you fetch changes from a remote repository and merge them into your current local branch?

git fetch: What is the difference between git pull and git fetch? 
git branch: How do you list, create, or delete branches?

git checkout <branch-name> / git switch <branch-name>: How do you switch between branches?
git merge <branch-name>: How do you integrate changes from one branch into another? 

# B. Intermediate Commands & Concepts:

git revert <commit-hash>: How do you undo a specific commit that has already been pushed, without rewriting history?

git reset --hard <commit-hash> / --soft / --mixed: Explain the different modes of git reset and when to use them.
git stash: How do you temporarily save changes in your working directory without committing them?

git remote: How do you manage remote repositories?
git config: How do you configure Git settings, such as user name and email?

Merge Conflicts: What is a merge conflict, and how do you resolve it? 
# C. Advanced Commands & Scenarios:

git rebase: Explain the concept of rebasing and its advantages/disadvantages compared to merging.
git cherry-pick <commit-hash>: How do you apply a specific commit from one branch to another? 

git reflog: What is git reflog and when is it useful?
.gitignore: What is the purpose of the .gitignore file?

Git Workflow: Describe a common Git workflow (e.g., Gitflow, Feature Branching).
Hooks: What are Git hooks and how can they be used? 
