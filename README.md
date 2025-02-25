# 🚀 **Git Guide for Beginners** 🌟  

*[niranjan-46](https://github.com/niranjan-46)

Welcome to the **Simple Git Guide**! This guide will help you understand Git commands with easy-to-follow steps, examples, and visuals. Let’s dive in!  

![Git Logo](https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png)  

---

## 📌 **What is Git?**  
Git is a **Version Control System (VCS)** that helps developers:  
- Track changes in their code.  
- Collaborate with others.  
- Maintain different versions of a project.  

Think of it as a **time machine** for your code! 🕰️  

---

## 🎯 **Getting Started with Git**  

### 1️⃣ **Set Up Git**  
Before using Git, tell it who you are:  
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```  
✅ *This links your commits to your GitHub account.*  

---

### 2️⃣ **Create a New Git Repository**  
To start tracking changes in your project:  
```bash
git init
```  
📌 *This creates a hidden `.git` folder in your project to store all Git data.*  

---

### 3️⃣ **Clone a Repository**  
To copy a project from GitHub to your computer:  
```bash
git clone <repository-url>
```  
📌 *This downloads the entire project to your local machine.*  

Example:  
```bash
git clone https://github.com/niranjan-46/microservices-python-app.git
```  

---

## 🚀 **Working with Git**  

### 📌 **Check the Status of Your Repository**  
```bash
git status
```  
✅ *Shows which files are modified, staged, or untracked.*  

---

### 📌 **Stage Changes for Commit**  
To prepare files for saving:  
```bash
git add <file>    # Add a specific file  
git add .         # Add all files  
```  
✅ *Think of this as adding files to a "to-be-saved" list.*  

Example:  
```bash
git add index.html  
```  

---

### 📌 **Save Changes (Commit)**  
To save your changes:  
```bash
git commit -m "Your commit message"
```  
✅ *This creates a snapshot of your changes with a message.*  

Example:  
```bash
git commit -m "Added login functionality"
```  

---

### 📌 **Upload Changes to GitHub**  
To share your changes with others:  
```bash
git push origin <branch-name>
```  
✅ *This uploads your commits to GitHub.*  

Example:  
```bash
git push origin main
```  

---

### 📌 **Download Latest Changes from GitHub**  
To get updates from others:  
```bash
git pull origin <branch-name>
```  
✅ *This fetches and merges changes from GitHub.*  

Example:  
```bash
git pull origin main
```  

---

## 🌿 **Working with Branches**  

### 📌 **Create a New Branch**  
To work on a new feature without affecting the main code:  
```bash
git branch <branch-name>
```  
✅ *This creates a separate branch for your work.*  

Example:  
```bash
git branch feature-login
```  

---

### 📌 **Switch to a Branch**  
To move to a different branch:  
```bash
git checkout <branch-name>
```  
✅ *This lets you work on that branch.*  

Example:  
```bash
git checkout feature-login
```  

---

### 📌 **Merge a Branch**  
To combine changes from one branch into another:  
```bash
git checkout main  
git merge <branch-name>
```  
✅ *This adds the changes from your branch to `main`.*  

Example:  
```bash
git merge feature-login
```  

---

### 📌 **Delete a Branch**  
To remove a branch you no longer need:  
#### Locally:  
```bash
git branch -d <branch-name>
```  
#### On GitHub:  
```bash
git push origin --delete <branch-name>
```  

Example:  
```bash
git push origin --delete feature-login
```  

---

## 🔄 **Undo & Reset Changes**  

### 📌 **Undo Last Commit (Keep Changes)**  
```bash
git reset --soft HEAD~1
```  

### 📌 **Undo Last Commit (Discard Changes)**  
```bash
git reset --hard HEAD~1
```  

### 📌 **Revert a Commit (Keep History)**  
```bash
git revert <commit-hash>
```  

Example:  
```bash
git revert a1b2c3d
```  

---

## 📜 **View Commit History**  
To see a summary of all commits:  
```bash
git log --oneline --graph --decorate --all
```  
✅ *This shows a clean history of your project.*  

---

## 🎒 **Git Stash (Save Temporary Changes)**  
To save changes without committing:  
```bash
git stash        # Save changes  
git stash pop    # Restore saved changes  
git stash list   # View saved stashes  
```  

---

## 🔗 **Advanced Git Commands**  

### 📌 **Rebase a Branch**  
```bash
git rebase <branch-name>
```  

### 📌 **Squash Commits**  
```bash
git rebase -i HEAD~<number-of-commits>
```  

### 📌 **Cherry-Pick a Commit**  
```bash
git cherry-pick <commit-hash>
```  

### 📌 **Tag a Commit**  
```bash
git tag -a v1.0 -m "Version 1.0"
git push origin v1.0
```  

---

## 💬 **Need Help?**  
Feel free to reach out to **[niranjan-46](https://github.com/niranjan-46)** or contribute to this guide! 🎯  

---

### **Visual Summary**  
Here’s a quick visual to help you understand Git workflows:  

![Git Workflow](https://wac-cdn.atlassian.com/dam/jcr:34e935dd-3108-40a8-9c39-55b13a403c58/01.svg)  

Happy coding! 🚀
