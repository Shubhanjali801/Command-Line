

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


# D. Check this 
# Git commands cheat-sheet

## Configuration  
git config --global user.name "Your Name"  
    # Set the global Git username. :contentReference[oaicite:1]{index=1}  
git config --global user.email "you@example.com"  
    # Set the global Git email address. :contentReference[oaicite:2]{index=2}  

## Starting / cloning a repository  
git init  
    # Initialize a new Git repository in the current directory. :contentReference[oaicite:3]{index=3}  
git clone <repository-url>  
    # Copy an existing remote repository (with all files/history) into a local directory. :contentReference[oaicite:4]{index=4}  

## Checking repository status / staging changes  
git status  
    # Show the status of the working directory and the staging area — which files are changed, staged, or untracked. :contentReference[oaicite:5]{index=5}  
git add <file>  
    # Add a file (or files) from working directory to the staging area. Prepares them for commit. :contentReference[oaicite:6]{index=6}  
git add .  
    # Add all changed/ new/ deleted files to staging area. :contentReference[oaicite:7]{index=7}  

## Creating commits  
git commit -m "Your commit message"  
    # Commit the staged changes to repository history, with a descriptive message. :contentReference[oaicite:8]{index=8}  
git commit -a  
(or git commit --all)  
    # Automatically stage and commit all modified and deleted files (skips explicit git add). :contentReference[oaicite:9]{index=9}  

## Viewing history / changes  
git log  
    # Show the commit history for the current branch. :contentReference[oaicite:10]{index=10}  
git diff  
    # Show differences between working directory, staging area, and last commit — or compare two commits. :contentReference[oaicite:11]{index=11}  

## Branching and switching  
git branch  
    # List all branches in repository. Current branch is marked with `*`. :contentReference[oaicite:12]{index=12}  
git branch <branch-name>  
    # Create a new branch named <branch-name>. :contentReference[oaicite:13]{index=13}  
git checkout <branch-name>  
    # Switch to the specified branch (or commit); can also be used to restore files. :contentReference[oaicite:14]{index=14}  
git checkout <old_branch> <new_branch> / git branch -m <old> <new>  
    # Rename a branch. (alternative: git branch -m) :contentReference[oaicite:15]{index=15}  

## Merging / integrating changes  
git merge <branch-name>  
    # Merge changes from specified branch into current branch. :contentReference[oaicite:16]{index=16}  
git rebase <branch-or-commit>  
    # Re-apply commits on top of another base commit/branch — helpful to keep history linear. :contentReference[oaicite:17]{index=17}  

## Working with remote repositories  
git push  
    # Upload local commits to a remote repository (e.g. origin). :contentReference[oaicite:18]{index=18}  
git pull  
    # Fetch updates from remote repo and merge into current branch (fetch + merge). :contentReference[oaicite:19]{index=19}  
git fetch  
    # Retrieve updates from remote repository, but do not merge — allows you to review before merging. :contentReference[oaicite:20]{index=20}  

## Undoing / cleaning / restoring  
git revert <commit-hash>  
    # Create a new commit that undoes changes introduced by the specified commit; does not rewrite history. :contentReference[oaicite:21]{index=21}  
git reset --soft <commit>  
    # Reset HEAD to specified commit, keeping changes in working directory (unstaged). :contentReference[oaicite:22]{index=22}  
git reset --hard <commit>  
    # Reset HEAD *and* working directory to specified commit — discards all changes after that commit. :contentReference[oaicite:23]{index=23}  

git clean -fd  
    # Remove untracked files and directories from working directory (clean up workspace). :contentReference[oaicite:24]{index=24}  

## Stashing changes  
git stash  
    # Temporarily save (stash) uncommitted changes — both staged and unstaged — so working directory becomes clean. :contentReference[oaicite:25]{index=25}  
git stash list  
    # List all stashed states. :contentReference[oaicite:26]{index=26}  
git stash apply  
    # Re-apply a stash without removing it from stash history. :contentReference[oaicite:27]{index=27}  
git stash pop  
    # Re-apply the most recent stash and remove it from stash history. :contentReference[oaicite:28]{index=28}  
git stash drop stash@{n}  
    # Delete a specific stash from history. :contentReference[oaicite:29]{index=29}  

## Tagging releases  
git tag -a <tagname> -m "message"  
    # Create an annotated tag pointing to current commit — useful for marking releases or versions. :contentReference[oaicite:30]{index=30}  
git push origin <tagname>  
    # Push the tagged commit to remote repository. :contentReference[oaicite:31]{index=31}  

## Other useful commands  
git rm <file>  
    # Remove a file from working directory and staging area (so deletion is tracked). :contentReference[oaicite:32]{index=32}  
git rm --cached <file>  
    # Remove a file from tracking (staging area) but keep it in working directory. :contentReference[oaicite:33]{index=33}  

git ls-files  
    # List all files tracked by Git in the repository (staging + working directory). :contentReference[oaicite:34]{index=34}  

git fetch --all  
    # Fetch updates from all remotes (all branches) without merging. :contentReference[oaicite:35]{index=35}  

git reflog  
    # Show history of HEAD and branch updates — useful to recover lost commits or check past HEAD positions. :contentReference[oaicite:36]{index=36}  
