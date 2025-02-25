

### **README.md - Git Guide for Beginners**  

```md
# 🚀 Git Guide by [niranjan-46](https://github.com/niranjan-46)

Welcome to the **Ultimate Git Guide**! This guide will help you understand Git commands with easy-to-follow steps, examples, and visuals.  

📌 **What is Git?**  
Git is a **Version Control System (VCS)** that helps developers track code changes, collaborate efficiently, and maintain different versions of a project.  

---

## 🎯 **Getting Started with Git**  

### ✅ **1. Configure Git (Set Username & Email)**  
Before using Git, set your identity:  
```bash
git config --global user.name "niranjan-46"
git config --global user.email "your.email@example.com"
```
✅ *This ensures all commits are linked to your GitHub account.*  

---

### ✅ **2. Initialize a Git Repository**  
```bash
git init
```
📌 *This creates a new Git repository in your project folder.*  

---

### ✅ **3. Clone an Existing Repository**  
```bash
git clone <repository-url>
```
📌 *Copies a remote repository to your local machine.*  

Example:  
```bash
git clone https://github.com/niranjan-46/microservices-python-app.git
```

---

## 🚀 **Working with Git**  

### 📌 **Check Repository Status**  
```bash
git status
```
✅ *Shows modified, staged, and untracked files.*  

---

### 📌 **Track & Stage Changes**  
```bash
git add <file>    # Add a specific file  
git add .         # Add all files  
```
✅ *Prepares files for commit.*  

Example:  
```bash
git add index.html  
```

---

### 📌 **Commit Changes**  
```bash
git commit -m "Your commit message"
```
✅ *Saves changes in the repository.*  

Example:  
```bash
git commit -m "Added login functionality"
```

---

### 📌 **Push Changes to GitHub**  
```bash
git push origin <branch-name>
```
✅ *Uploads local commits to GitHub.*  

Example:  
```bash
git push origin main
```

---

### 📌 **Pull Latest Changes from GitHub**  
```bash
git pull origin <branch-name>
```
✅ *Fetches and merges remote updates.*  

Example:  
```bash
git pull origin main
```

---

## 🔀 **Working with Branches**  

### 📌 **Create a New Branch**  
```bash
git branch <branch-name>
```
✅ *Creates a separate branch for development.*  

Example:  
```bash
git branch feature-login
```

---

### 📌 **Switch to a Different Branch**  
```bash
git checkout <branch-name>
```
✅ *Switches between branches.*  

Example:  
```bash
git checkout feature-login
```

---

### 📌 **Merge a Branch into Main**  
```bash
git checkout main  
git merge <branch-name>
```
✅ *Combines changes from another branch into `main`.*  

Example:  
```bash
git merge feature-login
```

---

### 📌 **Delete a Branch**  
#### Locally:  
```bash
git branch -d <branch-name>
```
#### Remotely:  
```bash
git push origin --delete <branch-name>
```

Example:  
```bash
git push origin --delete feature-login
```

---

## 🔄 **Undo & Reset Changes**  

### 📌 **Undo Last Commit (Keep Changes in Staging)**  
```bash
git reset --soft HEAD~1
```

### 📌 **Undo Last Commit (Discard Changes Completely)**  
```bash
git reset --hard HEAD~1
```

### 📌 **Revert a Commit (Keep History Intact)**  
```bash
git revert <commit-hash>
```

Example:  
```bash
git revert a1b2c3d
```

---

## 📌 **Check Commit History**  
```bash
git log --oneline --graph --decorate --all
```
✅ *Displays a clean commit history with branches.*  

---

## 🎭 **Git Stash (Save Temporary Changes)**  
```bash
git stash        # Save changes  
git stash pop    # Restore saved changes  
git stash list   # View saved stashes  
```

---

## 🔗 **Working with Remote Repositories**  

### 📌 **Check Remote Repository URL**  
```bash
git remote -v
```

### 📌 **Add a Remote Repository**  
```bash
git remote add origin <repository-url>
```

Example:  
```bash
git remote add origin https://github.com/niranjan-46/microservices-python-app.git
```

---

## ❌ **Fix Merge Conflicts**  
```bash
# Open conflicted files, edit manually, then run:
git add <file>
git commit -m "Resolved merge conflict"
```

---

## ⚠️ **Force Push (Use with Caution!)**  
```bash
git push --force origin <branch-name>
```
⚠️ *Overwrites the remote branch. Be careful!*  

---

## 🎉 **Congratulations! You Are Now a Git Pro! 🚀**  
🔥 Keep practicing, and you'll master Git in no time!  

---

## 📖 **Useful Resources**  
- [Official Git Documentation](https://git-scm.com/doc)  
- [GitHub Learning Lab](https://lab.github.com/)  
- [Pro Git Book (Free)](https://git-scm.com/book/en/v2)  

---

## 💬 **Need Help?**  
Feel free to reach out to [niranjan-46](https://github.com/niranjan-46) or contribute to this guide! 🎯  
```

---

### **What’s Next?**
1. **Add GIFs and images** to the `assets/` folder in your repo.
2. **Update image links** inside `README.md`.
3. **Commit & push** your README file.

Would you like me to generate Git command GIFs for you? 🚀
