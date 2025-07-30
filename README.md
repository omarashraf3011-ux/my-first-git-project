# Hello Konecta Team 👋

This is my first task in **Git & GitHub** as part of the hands-on activity for debugging and restoring code.  
In this project, I created and managed a simple Python calculator, intentionally introduced a bug, and then used Git to debug and restore a clean version of the code while preserving ongoing work.  

You can view the repository and final Python file here:  
👉 [My First Git Project](https://github.com/omarashraf3011-ux/my-first-git-project)

---

## Tools & Commands Used
Throughout this task, I practiced key Git commands such as:
- `git log` – to explore commit history and identify the buggy commit.  
- `git diff` – to compare changes between commits and confirm the bug.  
- `git stash` – to temporarily save my uncommitted work.  
- `git revert` – to safely undo the buggy commit without rewriting history.  
- `git add` & `git commit` – to stage and save my changes.  
- `git push` – to upload the changes to the remote repository on GitHub.  

---

## Screenshots
All screenshots documenting each step are available in the [`screenshots`](./screenshots) folder inside the repository.  
Each screenshot is numbered according to its step for easy tracking.  

### Steps Overview:
1. **Created `my-first-git-project`** folder and initialized Git with a simple `calculator.py` file.  
2. **Staged and committed** the initial calculator functions and verified using `git log`.  
3. **Added a multiply function** and committed the changes.  
4. **Added a divide function with zero check** and confirmed updates in commit history.  
5. **Introduced a bug** in the subtract function and used `git diff` to identify the changes.  
6. **Stashed uncommitted work** using `git stash` for safe temporary storage.  
7. **Reverted the buggy commit** using `git revert` and verified functionality by running the Python file.  
8. **Popped the stashed changes** back into the working directory using `git stash pop`.  
9. **Pushed all final changes** to the remote repository.  

---

## Written Explanations

**1. How did `git log` and `git diff` help identify the erroneous commit?**  
- `git log` allowed me to quickly review the commit history and locate the commit where the bug was introduced.  
- `git diff` helped compare the buggy commit with its previous version, making it easy to spot the exact line that caused the error.  

**2. Why was `git stash` necessary in this scenario?**  
- It allowed me to temporarily save my ongoing uncommitted work so I could safely revert to a clean state without losing progress.  

**3. Why did I choose `git revert` over `git reset --hard`?**  
- `git revert` creates a new commit that undoes the changes, keeping the history intact, which is safer for shared repositories.  
- In contrast, `git reset --hard` rewrites history, which can cause problems for collaborators and generally requires a force push.  

**4. Difference between `git stash pop` and `git stash apply`:**  
- `git stash pop` applies the stashed changes **and removes them from the stash list** (one-time use).  
- `git stash apply` applies the changes **but keeps them saved in the stash list** for reuse.  

---

## Final Python File  
The final `calculator.py` file is available in the main directory of the repository.  

---

Thanks for reviewing my work!  
**Omar Ashraf**  