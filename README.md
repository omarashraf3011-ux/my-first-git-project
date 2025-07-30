README.md
# My First Git Project – Debugging & Restoring Changes

Hello Konecta Team 👋,  

This is my first task using **Git & GitHub**, where I practiced identifying bugs, stashing uncommitted work, and restoring previous versions of code in a professional workflow.

You can view the full repository here:  
**[GitHub Repository](https://github.com/omarashraf3011-ux/my-first-git-project)**

---

## **Task Steps & Screenshots**

The screenshots of each step are available in the **`/screenshots`** folder inside this repository.  
Each screenshot is labeled with the step number and includes a small description of what I did.  

**Steps:**
1. **Created project & initial file:** Created `my-first-git-project` folder and `calculator.py`.  
2. **Initial commit:** Added the basic calculator functions and committed them.  
3. **Added multiply function:** Updated the file with multiplication functionality and committed changes.  
4. **Added divide function:** Implemented division with a zero-check and committed changes.  
5. **Detected the bug:** Used `git diff` to inspect changes and identified where the bug was introduced.  
6. **Stashed work:** Used `git stash` to temporarily save uncommitted work for later.  
7. **Reverted the bug:** Used `git revert` to fix the bug and tested the Python file.  
8. **Restored stashed changes:** Used `git stash pop` to bring back the unfinished work.  
9. **Final push:** Pushed all commits and changes to the remote GitHub repository.  

---

## **Written Explanations**

**1. How did `git log` and `git diff` help you identify the erroneous commit?**  
- `git log` let me quickly review all commits and spot the one where I introduced the bug.  
- `git diff` helped me see exactly what changed in that commit (the wrong subtraction logic), so I could confirm where the bug was introduced.  

**2. Why was `git stash` necessary in this scenario?**  
- Because I had some uncommitted changes that I didn’t want to lose. Stashing allowed me to save them temporarily, fix the bug first, and then bring them back after.  

**3. Why did you choose `git revert` instead of `git reset --hard`?**  
- I chose `git revert` because it’s safer for shared branches — it creates a new commit that undoes the buggy changes without rewriting history.  
- `git reset --hard` would remove the commit completely and require a force push, which is risky for collaboration.  

**4. What’s the difference between `git stash pop` and `git stash apply`?**  
- `git stash pop` applies the stashed changes **and removes them** from the stash list.  
- `git stash apply` applies the stashed changes **but keeps them** in the stash for later use.  

---

## **Final Python File**

You can view the final version of `calculator.py` in the repository [here](https://github.com/omarashraf3011-ux/my-first-git-project/blob/main/calculator.py).

---

**Thank you for reviewing my task!** 🚀  
