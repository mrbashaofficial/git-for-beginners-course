# Git for Beginners: Version Control Made Simple 🚀

Welcome to the **Git for Beginners** course repository! This is your one-stop guide to mastering Git, a powerful version control system that developers and teams use to track changes, collaborate, and build amazing projects efficiently.

This repository contains the complete course content, lesson overviews, and links to individual lesson materials to help you follow along with the video tutorials and exercises.

---

## 📚 Course Overview

This course is designed to take you from being a **complete Git novice** to a **confident Git user**. By the end of the course, you'll be comfortable with Git's core concepts, commands, and collaboration workflows.

### 🎥 **YouTube Playlist**
You can watch the full video series on YouTube here: [Git for Beginners: Video Playlist](#).

---

## 🗂 **Course Content**

### **1. Introduction to Git and Version Control**
   - What is version control, and why is it important?
   - Overview of Git: how it works and why it’s popular.
   - Difference between Git and GitHub.
   - Installing Git on different operating systems.
   - Configuring Git for the first time:
     ```bash
     git config --global user.name "Your Name"
     git config --global user.email "youremail@example.com"
     ```

   [Learn more →](lesson-materials/lesson-01/README.md)

---

### **2. Core Git Concepts**
   - Understanding the **working directory**, **staging area**, and **commit history**.
   - What are repositories? Local vs. remote repositories.
   - Visualizing how Git tracks changes over time.

   [Learn more →](lesson-materials/lesson-02/README.md)

---

### **3. Starting a Project with Git**
   - Initializing a new Git repository:
     ```bash
     git init
     ```
   - Cloning an existing repository:
     ```bash
     git clone <repository-url>
     ```

   [Learn more →](lesson-materials/lesson-03/README.md)

---

### **4. Basic Git Commands**
   - Tracking changes with `git add`:
     ```bash
     git add <file-name>
     ```
   - Saving changes with `git commit`:
     ```bash
     git commit -m "Your message here"
     ```
   - Checking the status of your repository:
     ```bash
     git status
     ```
   - Viewing the commit history:
     ```bash
     git log
     ```

   [Learn more →](lesson-materials/lesson-04/README.md)

---

### **5. Branching and Merging**
   - What are branches? Why use them?
   - Creating a new branch and switching to it:
     ```bash
     git branch <branch-name>
     git switch <branch-name>
     ```
   - Merging branches:
     ```bash
     git merge <branch-name>
     ```
   - Resolving merge conflicts.

   [Learn more →](lesson-materials/lesson-05/README.md)

---

### **6. Working with Remote Repositories**
   - Adding a remote repository:
     ```bash
     git remote add origin <repository-url>
     ```
   - Pushing changes to a remote repository:
     ```bash
     git push origin <branch-name>
     ```
   - Pulling updates from a remote repository:
     ```bash
     git pull origin <branch-name>
     ```
   - Fetching updates without merging:
     ```bash
     git fetch
     ```

   [Learn more →](lesson-materials/lesson-06/README.md)

---

### **7. Undoing Changes**
   - Undoing changes in the working directory:
     ```bash
     git checkout -- <file-name>
     ```
   - Unstaging files:
     ```bash
     git reset <file-name>
     ```
   - Undoing commits:
     ```bash
     git revert <commit-hash>
     ```
   - Resetting to a previous state:
     ```bash
     git reset --soft <commit-hash>
     git reset --hard <commit-hash>
     ```

   [Learn more →](lesson-materials/lesson-07/README.md)

---

### **8. Collaborating with Others**
   - Forking and cloning repositories.
   - Making a pull request.
   - Reviewing and merging pull requests.

   [Learn more →](lesson-materials/lesson-08/README.md)

---

### **9. Common Scenarios and Best Practices**
   - Rebase vs. merge:
     ```bash
     git rebase <branch-name>
     ```
   - Handling a detached HEAD state.
   - Squashing commits into one:
     ```bash
     git rebase -i HEAD~<number-of-commits>
     ```

   [Learn more →](lesson-materials/lesson-09/README.md)

---

### **10. Advanced Topics**
   - Saving your work with `git stash`:
     ```bash
     git stash
     git stash apply
     ```
   - Cherry-picking commits:
     ```bash
     git cherry-pick <commit-hash>
     ```
   - Tagging releases:
     ```bash
     git tag -a v1.0 -m "Version 1.0"
     ```

   [Learn more →](lesson-materials/lesson-10/README.md)

---

## 🛠 **Repository Structure**

git-for-beginners-course/ ├── README.md ├── lesson-materials/ │ ├── lesson-01/ │ │ ├── README.md │ ├── lesson-02/ │ │ ├── README.md │ ├── ... ├── exercises/ │ ├── beginner-exercises.md │ ├── solutions/ ├── scripts/ │ ├── sample-commands.sh └── CONTRIBUTING.md

---

## 🏆 **Who Is This Course For?**

This course is for anyone who:
- Wants to understand version control and Git.
- Aspires to collaborate efficiently in team projects.
- Is looking to contribute to open-source projects.

No prior knowledge of Git is required! 🎉

---

## 🤝 **How to Contribute**

We love contributions! If you find issues or would like to improve the content:
1. Fork this repository.
2. Make changes in a new branch.
3. Submit a pull request.

---

## 🚀 **Start Your Git Journey Today!**

Jump into the lesson materials, watch the tutorials, and start practicing Git today. If you have questions, feel free to open an issue or contact us.

Happy coding! 🖖
