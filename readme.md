# 🚀 30 Essential Git Commands for Every Developer

---

## 1. Set Git Config Globally

<pre><code id="cmd1">git config --global user.name "Your Name"
git config --global user.email "you@example.com"</code></pre>
<button onclick="copy('cmd1')">📋 Copy</button>  
🧠 Sets your Git identity across all projects.

---

## 2. Initialize a Repository

<pre><code id="cmd2">git init</code></pre>
<button onclick="copy('cmd2')">📋 Copy</button>  
🧠 Creates a new Git repository in the current folder.

---

## 3. Add Remote Repository (Optional)

<pre><code id="cmd3">git remote add origin https://github.com/user/repo.git</code></pre>
<button onclick="copy('cmd3')">📋 Copy</button>  
🧠 Connects your local repo to a remote one.

---

## 4. Check Repo Status

<pre><code id="cmd4">git status</code></pre>
<button onclick="copy('cmd4')">📋 Copy</button>  
🧠 Shows current changes in the working directory.

---

## 5. Stage Files

<pre><code id="cmd5">git add .</code></pre>
<button onclick="copy('cmd5')">📋 Copy</button>  
🧠 Adds all files to the staging area.

---

## 6. Commit Staged Changes

<pre><code id="cmd6">git commit -m "Your message"</code></pre>
<button onclick="copy('cmd6')">📋 Copy</button>  
🧠 Saves a snapshot of your code to Git history.

---

## 7. Create and Switch Branch

<pre><code id="cmd7">git checkout -b new-feature</code></pre>
<button onclick="copy('cmd7')">📋 Copy</button>  
🧠 Creates and moves to a new branch in one step.

---

## 8. Make Edits → Add → Commit Again

<pre><code id="cmd8">git add . && git commit -m "Changes done"</code></pre>
<button onclick="copy('cmd8')">📋 Copy</button>  
🧠 Stages and commits further changes.

---

## 9. Switch Between Branches

<pre><code id="cmd9">git checkout main</code></pre>
<button onclick="copy('cmd9')">📋 Copy</button>  
🧠 Moves back to `main` or any other branch.

---

## 10. Merge Branch

<pre><code id="cmd10">git merge new-feature</code></pre>
<button onclick="copy('cmd10')">📋 Copy</button>  
🧠 Merges changes from another branch into current one.

---

## 11. Push to Remote

<pre><code id="cmd11">git push origin main</code></pre>
<button onclick="copy('cmd11')">📋 Copy</button>  
🧠 Uploads local commits to GitHub (or any remote).

---

## 12. Pull Latest Changes

<pre><code id="cmd12">git pull origin main</code></pre>
<button onclick="copy('cmd12')">📋 Copy</button>  
🧠 Downloads and merges latest code from remote.

---

## 13. View Commit History

<pre><code id="cmd13">git log</code></pre>
<button onclick="copy('cmd13')">📋 Copy</button>  
🧠 Lists all previous commits with messages.

---

## 14. Show File Differences

<pre><code id="cmd14">git diff</code></pre>
<button onclick="copy('cmd14')">📋 Copy</button>  
🧠 Shows changes between files and versions.

---

## 15. Stash Uncommitted Changes

<pre><code id="cmd15">git stash</code></pre>
<button onclick="copy('cmd15')">📋 Copy</button>  
🧠 Temporarily saves changes for a clean workspace.

---

## 16. Apply Last Stash

<pre><code id="cmd16">git stash apply</code></pre>
<button onclick="copy('cmd16')">📋 Copy</button>  
🧠 Re-applies the most recent stashed changes.

---

## 17. Delete Branch After Merge

<pre><code id="cmd17">git branch -d new-feature</code></pre>
<button onclick="copy('cmd17')">📋 Copy</button>  
🧠 Removes a branch safely after merging.

---

## 18. See All Branches

<pre><code id="cmd18">git branch</code></pre>
<button onclick="copy('cmd18')">📋 Copy</button>  
🧠 Lists all local branches.

---

## 19. Show Remote URLs

<pre><code id="cmd19">git remote -v</code></pre>
<button onclick="copy('cmd19')">📋 Copy</button>  
🧠 Displays linked remote repositories.

---

## 20. Revert a Commit (Safe Undo)

<pre><code id="cmd20">git revert &lt;commit-id&gt;</code></pre>
<button onclick="copy('cmd20')">📋 Copy</button>  
🧠 Reverses a commit by creating a new one.

---

## 21. Hard Reset to Commit

<pre><code id="cmd21">git reset --hard &lt;commit-id&gt;</code></pre>
<button onclick="copy('cmd21')">📋 Copy</button>  
🧠 Resets everything (code + history) to a specific commit.

---

## 22. Tag a Version

<pre><code id="cmd22">git tag v1.0</code></pre>
<button onclick="copy('cmd22')">📋 Copy</button>  
🧠 Labels a specific commit (e.g., release version).

---

## 23. Show Tag Info

<pre><code id="cmd23">git show v1.0</code></pre>
<button onclick="copy('cmd23')">📋 Copy</button>  
🧠 Shows commit message and content of a tag.

---

## 24. Cherry Pick Specific Commit

<pre><code id="cmd24">git cherry-pick &lt;commit-id&gt;</code></pre>
<button onclick="copy('cmd24')">📋 Copy</button>  
🧠 Brings a single commit from one branch to another.

---

## 25. Remove File from Repo

<pre><code id="cmd25">git rm unwanted.txt</code></pre>
<button onclick="copy('cmd25')">📋 Copy</button>  
🧠 Deletes a file and tracks that deletion.

---

## 26. Rename File in Git

<pre><code id="cmd26">git mv old.txt new.txt</code></pre>
<button onclick="copy('cmd26')">📋 Copy</button>  
🧠 Renames or moves file and stages that change.

---

## 27. Fetch from Remote

<pre><code id="cmd27">git fetch origin</code></pre>
<button onclick="copy('cmd27')">📋 Copy</button>  
🧠 Updates local repo with remote data (no merge).

---

## 28. Clean Untracked Files

<pre><code id="cmd28">git clean -fd</code></pre>
<button onclick="copy('cmd28')">📋 Copy</button>  
🧠 Deletes all untracked files and folders.

---

## 29. View File Author Line-by-Line

<pre><code id="cmd29">git blame file.txt</code></pre>
<button onclick="copy('cmd29')">📋 Copy</button>  
🧠 Shows who wrote each line in a file.

---

## 30. Archive Repo as ZIP

<pre><code id="cmd30">git archive --format=zip HEAD > project.zip</code></pre>
<button onclick="copy('cmd30')">📋 Copy</button>  
🧠 Saves current repo as a zip file.

---

<script>
function copy(id) {
  const text = document.getElementById(id).innerText;
  navigator.clipboard.writeText(text).then(() => {
    alert("✅ Copied: " + text);
  });
}
</script>


---

## 🎯 Why Git?

- 🔒 Version control like a pro  
- 🤝 Collaborate without chaos  
- 💡 Learn how real-world devs work

---

⭐️ **Star this repository if you learned something!**  

