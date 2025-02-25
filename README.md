Here’s a **detailed `README.md`** file with **Git commands, explanations, images, and animations**. You can copy and save this in your repository.  

I'll assume you will **upload images/GIFs manually** in your GitHub repo under the `assets/` folder. If you need help generating images or GIFs, let me know! 🚀  

---

### **README.md - Comprehensive Git Guide**  

```md
# 🚀 Git Complete Guide  

Welcome to the **Git Complete Guide**! This document covers all essential Git commands with detailed explanations and visuals to help you master Git.  

---

## 📌 What is Git?  
Git is a **distributed version control system** that helps track changes in files, collaborate with teams, and manage software development efficiently.  

---

# 🔥 Basic Git Setup  

## 🔹 Configure Git (Set Username & Email)  
Before using Git, set your identity:  
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
✅ *This ensures that all commits are associated with your identity.*  

---

## 🔹 Initialize a Git Repository  
```bash
git init
```
✅ *Creates a new Git repository in the current directory.*  
📌 **After running this command, Git starts tracking changes in your project.**  

---

## 🔹 Clone an Existing Repository  
```bash
git clone <repository-url>
```
✅ *Copies a remote repository to your local machine.*  
📌 **Example:**  
```bash
git clone https://github.com/niranjan-46/microservices-python-app.git
```

![Git Clone](assets/git-clone.gif)  

---

# 📂 Working with Git  

## 🔹 Check the Status of the Repository  
```bash
git status
```
✅ *Displays modified, untracked, or staged files.*  

![Git Status](assets/git-status.gif)  

---

## 🔹 Track & Stage Changes  
```bash
git add <file>          # Add a specific file  
git add .               # Add all files  
```
✅ *Stages files for commit.*  

📌 **Example:**  
```bash
git add index.html  
git add .  # Adds all files  
```

![Git Add](assets/git-add.gif)  

---

## 🔹 Commit Changes  
```bash
git commit -m "Your commit message"
```
✅ *Records changes in Git history with a message.*  

📌 **Example:**  
```bash
git commit -m "Added login functionality"
```

---

## 🔹 Push Changes to Remote Repository  
```bash
git push origin <branch-name>
```
✅ *Sends your commits to GitHub.*  

📌 **Example:**  
```bash
git push origin main
```

![Git Push](assets/git-push.gif)  

---

## 🔹 Pull Latest Changes from Remote Repository  
```bash
git pull origin <branch-name>
```
✅ *Fetches and merges remote updates.*  

📌 **Example:**  
```bash
git pull origin main
```

![Git Pull](assets/git-pull.gif)  

---

# 🔀 Working with Branches  

## 🔹 Create a New Branch  
```bash
git branch <branch-name>
```
✅ *Creates a new branch for feature development.*  

📌 **Example:**  
```bash
git branch feature-login
```

---

## 🔹 Switch to a Different Branch  
```bash
git checkout <branch-name>
```
✅ *Moves between branches.*  

📌 **Example:**  
```bash
git checkout feature-login
```

---

## 🔹 Merge a Branch into Main  
```bash
git checkout main  
git merge <branch-name>
```
✅ *Combines changes from another branch into `main`.*  

📌 **Example:**  
```bash
git checkout main  
git merge feature-login
```

![Git Merge](assets/git-merge.gif)  

---

## 🔹 Delete a Branch  
### **Locally**  
```bash
git branch -d <branch-name>     # Delete a branch  
git branch -D <branch-name>     # Force delete if not merged  
```
### **Remotely**  
```bash
git push origin --delete <branch-name>
```
✅ *Removes the branch locally or remotely.*  

📌 **Example:**  
```bash
git push origin --delete feature-login
```

---

# 🔄 Undo & Reset Changes  

## 🔹 Undo Last Commit (Keep Changes)  
```bash
git reset --soft HEAD~1
```
✅ *Moves last commit to the staging area.*  

---

## 🔹 Undo Last Commit (Discard Changes)  
```bash
git reset --hard HEAD~1
```
✅ *Deletes the last commit permanently.*  

---

## 🔹 Revert a Commit (Keep History)  
```bash
git revert <commit-hash>
```
✅ *Reverts changes while keeping history.*  

📌 **Example:**  
```bash
git revert a1b2c3d
```

![Git Revert](assets/git-revert.gif)  

---

# 🔍 Check Commit History  
```bash
git log --oneline --graph --decorate --all
```
✅ *Displays a graphical commit history.*  

---

# 🎭 Git Stash (Save Temporary Changes)  
```bash
git stash        # Save changes  
git stash pop    # Restore saved changes  
git stash list   # View saved stashes  
```
✅ *Useful when switching branches without committing.*  

📌 **Example:**  
```bash
git stash  
git checkout another-branch  
git stash pop
```

![Git Stash](assets/git-stash.gif)  

---

# ⚠️ Force Push (Use with Caution)  
```bash
git push --force origin <branch-name>
```
⚠️ *Overwrites the remote branch. Be careful!*  

📌 **Use only if necessary to override remote changes.*  

---

# 🔗 Remote Repository Management  

## 🔹 Check Remote Repositories  
```bash
git remote -v
```
✅ *Lists all remote repositories.*  

---

## 🔹 Add a Remote Repository  
```bash
git remote add origin <repository-url>
```
✅ *Links a local repo to a remote GitHub repository.*  

---

# ⚠️ Fix Merge Conflicts  
```bash
# Open conflicted files, edit manually, then run:
git add <file>
git commit -m "Resolved merge conflict"
```
✅ *Manually resolve merge conflicts and commit changes.*  

![Git Merge Conflict](assets/git-merge-conflict.gif)  

---

# 🎉 Congratulations!  
You now have a solid foundation in Git! Happy coding! 🚀  

![Git Workflow](assets/git-workflow.gif)  

---

## 📖 Additional Resources  
- [Official Git Documentation](https://git-scm.com/doc)  
- [GitHub Learning Lab](https://lab.github.com/)  
- [Pro Git Book (Free)](https://git-scm.com/book/en/v2)  

---

## 💬 Need Help?  
Feel free to raise an issue or contribute to this guide! 🎯  
```

---

### **Next Steps**:
1. Add **GIFs and images** in the `assets/` folder of your repository.
2. Update **image links** to match your GitHub repo structure.
3. **Commit & push** the `README.md` file.

Would you like me to generate Git command GIFs for you? 🚀
