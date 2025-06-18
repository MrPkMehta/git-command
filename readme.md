# 🚀 30 Essential Git Commands for Every Developer

A handy, beginner-friendly guide to Git — each command explained with one-line usage and example. Master version control like a pro! 🔧

---

## 🔧 Basic Setup

### 1. `git init`
📝 Initializes a new Git repo  
📌 `git init my-project`

### 2. `git config`
⚙️ Sets username and email  
📌 `git config --global user.name "John"`  
📌 `git config --global user.email "john@example.com"`

### 3. `git clone`
📥 Clone existing repo  
📌 `git clone https://github.com/user/repo.git`

---

## 📁 Stage & Commit

### 4. `git status`
🔍 See current file states  
📌 `git status`

### 5. `git add`
📥 Stage files for commit  
📌 `git add file.txt` or `git add .`

### 6. `git commit`
🗃️ Save changes with message  
📌 `git commit -m "Added feature"`

---

## 🌿 Branching

### 7. `git branch`
🌴 View/create branches  
📌 `git branch`  
📌 `git branch new-feature`

### 8. `git checkout`
🔁 Switch branches  
📌 `git checkout main`

### 9. `git merge`
🔗 Merge branches  
📌 `git merge feature-branch`

### 10. `git branch -d`
🗑️ Delete a branch  
📌 `git branch -d old-feature`

---

## 🚀 Remote Repositories

### 11. `git remote add`
🌐 Connect to remote  
📌 `git remote add origin https://...`

### 12. `git push`
📤 Push changes to remote  
📌 `git push origin main`

### 13. `git pull`
📥 Pull latest from remote  
📌 `git pull origin main`

### 14. `git fetch`
⏬ Download changes only  
📌 `git fetch origin`

### 15. `git remote -v`
🔍 Show remote URLs  
📌 `git remote -v`

---

## 🔄 Undoing Changes

### 16. `git reset`
⏪ Move HEAD, optionally reset  
📌 `git reset --soft HEAD~1`  
📌 `git reset --hard <commit>`

### 17. `git revert`
🧼 Undo specific commit  
📌 `git revert <commit-id>`

### 18. `git stash`
📦 Save uncommitted changes  
📌 `git stash`

### 19. `git stash apply`
📂 Re-apply stashed changes  
📌 `git stash apply`

---

## 📜 Logs & History

### 20. `git log`
📚 Show commit logs  
📌 `git log --oneline`

### 21. `git reflog`
📅 Log of branch movement  
📌 `git reflog`

### 22. `git show`
🔍 Show commit details  
📌 `git show <commit>`

### 23. `git diff`
🔎 Show unstaged/staged changes  
📌 `git diff` or `git diff --staged`

---

## 🔍 Inspection Tools

### 24. `git blame`
👤 See who changed each line  
📌 `git blame app.js`

### 25. `git tag`
🏷️ Mark specific commits  
📌 `git tag v1.0`

### 26. `git cherry-pick`
🍒 Apply specific commit  
📌 `git cherry-pick <commit>`

---

## 🧹 File Handling

### 27. `git rm`
🗑️ Delete and stage file  
📌 `git rm file.txt`

### 28. `git mv`
✏️ Rename/move files  
📌 `git mv old.txt new.txt`

### 29. `git clean`
🧼 Remove untracked files  
📌 `git clean -fd`

---

## 📦 Extra

### 30. `git archive`
📁 Export project as zip/tar  
📌 `git archive --format=zip HEAD > project.zip`

---

## 💡 Bonus: Visual Log

```bash
git log --oneline --graph --all

---

## 🎯 Why Git?

- 🔒 Version control like a pro  
- 🤝 Collaborate without chaos  
- 💡 Learn how real-world devs work

---

⭐️ **Star this repository if you learned something!**  

