# 🚀 Git Command Cheat Sheet

A complete guide of the **most essential Git commands** with examples, explanations.

---

### ✅ Setup Git (Only Once)

```bash
# Syntax
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

```bash
# Example
git config --global user.name "Priyamanshu"
git config --global user.email "mehta@gmail.com"
```

📌 Sets your name and email for all git commits.

---

### 📁 Initialize a New Repo

```bash
# Syntax
git init
```

```bash
# Example
git init
```

📌 Creates a new Git repo in the current folder.

---

### 🔍 Check Current Git Status

```bash
# Syntax
git status
```

```bash
git status
```

📌 Shows modified/untracked files.

---

### ➕ Add Files to Staging Area

```bash
# Syntax
git add <file|.>
```

```bash
git add index.html
```

📌 Adds specified file(s) to staging.

---

### ✅ Commit Changes

```bash
# Syntax
git commit -m "message"
```

```bash
git commit -m "Initial commit"
```

📌 Saves staged changes with a message.

---

### 🔄 Connect to Remote Repo

```bash
# Syntax
git remote add origin <url>
```

```bash
git remote add origin https://github.com/user/repo.git
```

📌 Links local repo to remote GitHub repo.

---

### 🚀 Push to Remote Repo

```bash
# Syntax
git push -u origin <branch>
```

```bash
git push -u origin main
```

📌 Pushes commits to remote (first time).

---

### 🔽 Pull From Remote Repo

```bash
# Syntax
git pull origin <branch>
```

```bash
git pull origin main
```

📌 Fetches and merges latest remote changes.

---

### 🌱 Create New Branch

```bash
# Syntax
git branch <branch_name>
```

```bash
git branch feature/login
```

📌 Creates a new branch.

---

### 🔀 Switch to Branch

```bash
# Syntax
git checkout <branch_name>
```

```bash
git checkout feature/login
```

📌 Moves to the specified branch.

---

### 🔄 Create + Switch Branch (Shortcut)

```bash
# Syntax
git checkout -b <branch_name>
```

```bash
git checkout -b feature/signup
```

📌 Creates and switches to new branch.

---

### 📜 See All Branches

```bash
# Syntax
git branch
```

```bash
git branch
```

📌 Lists all branches.

---

### 🧹 Delete Branch

```bash
# Syntax
git branch -d <branch_name>
```

```bash
git branch -d feature/signup
```

📌 Deletes local branch.

---

### 🔄 Merge Branch

```bash
# Syntax
git merge <branch_name>
```

```bash
git merge feature/login
```

📌 Merges given branch into current.

---

### 🎉 Clone Repo

```bash
# Syntax
git clone <url>
```

```bash
git clone https://github.com/user/project.git
```

📌 Downloads a repo to your system.

---

### 🔁 View Commit History

```bash
# Syntax
git log
```

```bash
git log
```

📌 Shows full commit history.

---

### 🧾 View Commit History (One-line)

```bash
# Syntax
git log --oneline
```

```bash
git log --oneline
```

📌 Summarized commit list.

---

### 🛠 Undo Changes in File

```bash
# Syntax
git checkout -- <file>
```

```bash
git checkout -- index.html
```

📌 Discards changes in file.

---

### 🚫 Remove File from Git (but keep locally)

```bash
# Syntax
git rm --cached <file>
```

```bash
git rm --cached secret.env
```

📌 Stops tracking file but keeps it.

---

### 🧼 Clean Untracked Files

```bash
# Syntax
git clean -fd
```

```bash
git clean -fd
```

📌 Deletes all untracked files.

---

### 🎯 Stash Changes

```bash
# Syntax
git stash
```

```bash
git stash
```

📌 Temporarily saves uncommitted changes.

---

### 🧾 Show Stash List

```bash
# Syntax
git stash list
```

```bash
git stash list
```

📌 Lists stashed changes.

---

### 🔙 Apply Stash

```bash
# Syntax
git stash apply
```

```bash
git stash apply
```

📌 Applies latest stash.

---

### 🧼 Drop Stash

```bash
# Syntax
git stash drop
```

```bash
git stash drop
```

📌 Removes the latest stash.

---

### 🔎 View Diffs

```bash
# Syntax
git diff
```

```bash
git diff
```

📌 Shows unstaged code changes.

---

### 🧠 Who Changed What (Blame)

```bash
# Syntax
git blame <file>
```

```bash
git blame index.html
```

📌 Shows who edited each line.

---

### 💌 Create Pull Request

➡️ Go to GitHub → Click "Compare & Pull Request"

📌 Used to request code review and merging.

---

### 📦 Archive Repo as ZIP

```bash
# Syntax
git archive --format=zip HEAD > file.zip
```

```bash
git archive --format=zip HEAD > project.zip
```

📌 Saves repo as a zip file.

---

### 📋 Enable Copy Button (JavaScript)

Use this script at the end of README (for Markdown + HTML rendering sites like GitHub Pages):

```html
<script>
function copy(id) {
  const text = document.getElementById(id).innerText;
  navigator.clipboard.writeText(text).then(() => {
    alert("✅ Copied: " + text);
  });
}
</script>
```

---

✨ Made with ❤️ by [MrPkMehta](https://github.com/MrPkMehta)
