# 📘 Git Command Cheat Sheet

### A complete guide of the **most essential Git commands** with examples and explanations.

---


## 📚 Table of Contents

1. [Initialize Git Repo](#-1-initialize-git-repo)
2. [Check Git Version](#-2-check-git-version)
3. [Configure Git Username](#-3-configure-git-username-only-once)
4. [Configure Git Email](#-4-configure-git-email-only-once)
5. [Check Git Config](#-5-check-git-config)
6. [Track Files](#-6-track-files)
7. [Commit Changes](#-7-commit-changes)
8. [Check Commit History](#-8-check-commit-history)
9. [Check Status](#-9-check-status)
10. [Remove from Staging](#-10-remove-from-staging)
11. [Check Changes (Diff)](#-11-check-changes-diff)
12. [Create New Branch](#-12-create-new-branch)
13. [Switch Branch](#-13-switch-branch)
14. [Create & Switch Branch](#-14-create--switch-branch)
15. [Delete Branch](#-15-delete-branch)
16. [Connect Remote Repo](#-16-connect-remote-repo)
17. [Push to Remote Repo](#-17-push-to-remote-repo)
18. [Pull from Remote](#-18-pull-from-remote)
19. [Clone a Repository](#-19-clone-a-repository)
20. [Rename Branch](#-20-rename-branch)
21. [Remove Cached Files](#-21-remove-cached-files)
22. [Git Stash (Temp Save)](#-22-git-stash-temp-save)
23. [Apply Stash](#-23-apply-stash)
24. [Delete Stash](#-24-delete-stash)
25. [Delete All Stashes](#-25-delete-all-stashes)
26. [View Remote URLs](#-26-view-remote-urls)
27. [See Last Commit](#-27-see-last-commit)
28. [Clean Untracked Files](#-28-clean-untracked-files)
29. [See Who Edited File](#-29-see-who-edited-file)
30. [Archive Repo as ZIP](#-30-archive-repo-as-zip)
31. [Create Pull Request](#-31-create-pull-request)

---

## 🔰 1. Initialize Git Repo

```bash
git init
```

**Example:**

```bash
git init my-project
```

🧐 Creates a new Git repository.

---

## 📂 2. Check Git Version

```bash
git --version
```

**Example:**

```bash
git --version
```

🧐 Displays your current Git version.

---

## 🛠 3. Configure Git Username (only once)

```bash
git config --global user.name "Your Name"
```

**Example:**

```bash
git config --global user.name "MrPkMehta"
```

🧐 Sets your name in all commits.

---

## ✉️ 4. Configure Git Email (only once)

```bash
git config --global user.email "you@example.com"
```

**Example:**

```bash
git config --global user.email "mrpkmehta@example.com"
```

🧐 Sets your email in all commits.

---

## 📄 5. Check Git Config

```bash
git config --list
```

**Example:**

```bash
git config --list
```

🧐 Shows all the Git configuration.

---

## 📦 6. Track Files

```bash
git add <file>
```

**Example:**

```bash
git add index.html
```

🧐 Adds file(s) to staging area.

---

## ✅ 7. Commit Changes

```bash
git commit -m "Your message"
```

**Example:**

```bash
git commit -m "Add homepage UI"
```

🧐 Commits staged files with message.

---

## 🔁 8. Check Commit History

```bash
git log
```

**Example:**

```bash
git log
```

🧐 Lists recent commits.

---

## 📶 9. Check Status

```bash
git status
```

**Example:**

```bash
git status
```

🧐 Shows modified/untracked files.

---

## 🧽 10. Remove from Staging

```bash
git reset <file>
```

**Example:**

```bash
git reset index.html
```

🧐 Unstages file from staging area.

---

## 🔍 11. Check Changes (Diff)

```bash
git diff
```

**Example:**

```bash
git diff
```

🧐 Shows file differences.

---

## 🌿 12. Create New Branch

```bash
git branch <branch-name>
```

**Example:**

```bash
git branch dev
```

🧠 Creates a new branch.

---

## 🔄 13. Switch Branch

```bash
git checkout <branch-name>
```

**Example:**

```bash
git checkout dev
```

🧠 Switches to the given branch.

---

## 🔁 14. Create & Switch Branch

```bash
git checkout -b <branch-name>
```

**Example:**

```bash
git checkout -b feature/login
```

🧠 Creates and switches to a new branch.

---

## 🔥 15. Delete Branch

```bash
git branch -d <branch-name>
```

**Example:**

```bash
git branch -d dev
```

🧠 Deletes a branch.

---

## 🔗 16. Connect Remote Repo

```bash
git remote add origin <repo-url>
```

**Example:**

```bash
git remote add origin https://github.com/user/repo.git
```

🧠 Links local repo with remote.

---

## ☁️ 17. Push to Remote Repo

```bash
git push -u origin <branch>
```

**Example:**

```bash
git push -u origin main
```

🧠 Uploads branch to remote.

---

## 📥 18. Pull from Remote

```bash
git pull
```

**Example:**

```bash
git pull
```

🧠 Fetches and merges changes.

---

## 📌 19. Clone a Repository

```bash
git clone <repo-url>
```

**Example:**

```bash
git clone https://github.com/user/repo.git
```

🧠 Copies a remote repo locally.

---

## 🚚 20. Rename Branch

```bash
git branch -m <new-name>
```

**Example:**

```bash
git branch -m main
```

🧠 Renames the current branch.

---

## 🧼 21. Remove Cached Files

```bash
git rm --cached <file>
```

**Example:**

```bash
git rm --cached config.js
```

🧠 Stops tracking file in Git.

---

## 🧾 22. Git Stash (Temp Save)

```bash
git stash
```

**Example:**

```bash
git stash
```

🧠 Saves changes temporarily.

---

## ♻️ 23. Apply Stash

```bash
git stash apply
```

**Example:**

```bash
git stash apply
```

🧠 Restores last stashed change.

---

## 🗑 24. Delete Stash

```bash
git stash drop
```

**Example:**

```bash
git stash drop
```

🧠 Deletes the most recent stash.

---

## 💥 25. Delete All Stashes

```bash
git stash clear
```

**Example:**

```bash
git stash clear
```

🧠 Clears all stashes.

---

## 💭 26. View Remote URLs

```bash
git remote -v
```

**Example:**

```bash
git remote -v
```

🧠 Shows remote repository URLs.

---

## 🕵️‍♂️ 27. See Last Commit

```bash
git show
```

**Example:**

```bash
git show
```

🧠 Displays details of the last commit.

---

## 🧹 28. Clean Untracked Files

```bash
git clean -fd
```

**Example:**

```bash
git clean -fd
```

🧠 Deletes untracked files & folders.

---

## 🧑‍💻 29. See Who Edited File

```bash
git blame <file>
```

**Example:**

```bash
git blame index.js
```

🧠 Shows who wrote each line.

---

## 📦 30. Archive Repo as ZIP

```bash
git archive --format=zip HEAD > project.zip
```

**Example:**

```bash
git archive --format=zip HEAD > backup.zip
```

🧠 Saves repo as a ZIP file.

---

## 🚀 31. Create Pull Request

```bash
git push origin <branch-name>
```

#### Then go to GitHub and click Compare & pull request.
### **Example:**

```bash
git push origin feature/login
```

🧠 Initiates a pull request from a branch.

---

### 🌟 Loved these Git commands?

If you found this helpful, don’t forget to:

* ⭐ **Star** this repo to show your support
* 🍴 **Fork** it to keep your personal copy
* 🧠 **Practice** and become a Git Pro
* 📢 **Share** it with your friends & colleagues

#### 💬 One star from you = One more developer empowered!

---

✨ Made with ❤️ by [MrPkMehta]([https://github.com/MrPkMehta](https://github.com/MrPkMehta))

