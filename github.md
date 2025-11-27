<h1>-----------------Github Commands-----------------------</h1>
---

# 🔵 **1. GitHub CLI (gh) Installation**

```
gh --version
gh auth login        # Login to GitHub
gh auth logout       # Logout
```

---

# 🟢 **2. GitHub Authentication**

```
gh auth login
gh auth status
gh auth refresh
```

---

# 🟣 **3. GitHub Repositories**

```
gh repo create                # Create a new GitHub repo
gh repo clone <owner/repo>    # Clone using GitHub CLI
gh repo view                  # View repo details
gh repo fork <repo>           # Fork a repository
gh repo rename <new-name>     # Rename repository
gh repo delete                # Delete repository
```

---

# 🔶 **4. Issues (GitHub Issues)**

```
gh issue list
gh issue view <number>
gh issue create
gh issue close <number>
gh issue reopen <number>
```

---

# 🔷 **5. Pull Requests (PR)**

```
gh pr list
gh pr view <number>
gh pr create
gh pr merge <number>
gh pr checkout <number>
gh pr close <number>
```

---

# 🟡 **6. GitHub Gists**

```
gh gist create <file>
gh gist list
gh gist view <id>
gh gist delete <id>
```

---

# 🟠 **7. GitHub Actions**

```
gh workflow list
gh workflow view <workflow>
gh run list
gh run view <run-id>
```

---

# ⚫ **8. GitHub SSH Commands**

```
ssh-keygen -t ed25519 -C "your@email"
cat ~/.ssh/id_ed25519.pub      # Copy key
ssh -T git@github.com          # Test SSH
```

---

# 🔘 **9. Git Commands Used With GitHub**

These are the commands you use daily to push/pull from GitHub.

### Remote settings

```
git remote -v
git remote add origin <url>
git remote set-url origin <url>
git remote remove origin
```

### Push / Pull

```
git push -u origin main
git push
git pull
git fetch
```

### Branch + GitHub

```
git branch <name>
git switch <name>
git push -u origin <branch>
git pull origin <branch>
```

### PR workflow (manual Git)

```
git merge <branch>
git rebase <branch>
```

---

# 🟤 **10. GitHub Release Commands**

```
gh release list
gh release create <tag> <files>
gh release delete <tag>
```

---

