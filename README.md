# Git Practice

This repository is a guide to practicing basic Git commands. It provides a list of commonly used commands along with descriptions to help you manage your version control effectively.

## **Git Commands**

### **1. Initializing and Configuring Git**
- `git init`  
  Initializes a new Git repository in the current directory.

- `git config --global user.name "Your Name"`  
  Sets your Git username globally.

- `git config --global user.email "your.email@example.com"`  
  Sets your Git email globally.

---

### **2. Checking the Status and History**
- `git status`  
  Displays the current status of the working directory and staging area.

- `git log`  
  Shows a detailed commit history.

- `git log --oneline`  
  Displays a condensed version of the commit history (one line per commit).

- `git diff`  
  Shows the changes in your working directory compared to the index or last commit.

---

### **3. Staging and Committing**
- `git add <file_name>`  
  Stages a specific file to prepare for a commit.

- `git add .`  
  Stages all changes in the current directory.

- `git commit -m "Commit message"`  
  Creates a new commit with the staged changes and a message.

- `git commit --amend`  
  Edits the last commit message or adds additional changes to the last commit.

---

### **4. Branching and Merging**
- `git branch`  
  Lists all branches in the repository.

- `git branch <branch_name>`  
  Creates a new branch.

- `git checkout <branch_name>`  
  Switches to a specific branch.

- `git switch <branch_name>`  
  An alternative to `checkout` for switching branches.

- `git merge <branch_name>`  
  Merges the specified branch into the current branch.

---

### **5. Rebasing**
- `git rebase <branch_name>`  
  Moves the commits of the current branch on top of the specified branch.

- `git rebase -i <after-this-commit>`  
  Allows you to interactively edit, reorder, or squash commits.

---

### **6. Undoing Changes**
- `git restore <file_name>`  
  Restores a file to the last committed state.

- `git reset <file_name>`  
  Unstages a file, keeping changes in the working directory.

- `git reset --hard`  
  Resets the working directory and staging area to match the last commit.

- `git revert <commit_hash>`  
  Creates a new commit that undoes changes introduced by a specific commit.

---

### **7. Fetching and Pulling**
- `git fetch`  
  Retrieves updates from a remote repository without merging.

- `git pull`  
  Fetches and integrates changes from a remote repository into the current branch.

- `git pull --rebase`  
  Fetches updates and rebases your commits on top of them.

---

### **8. Pushing Changes**
- `git push`  
  Sends your commits to a remote repository.

- `git push origin <branch_name>`  
  Pushes a specific branch to the remote repository.

---

### **9. Stashing**
- `git stash`  
  Temporarily saves changes in the working directory for later use.

- `git stash apply`  
  Applies stashed changes without deleting the stash.

- `git stash pop`  
  Applies and removes the stashed changes.

---

### **10. Remote Repository Management**
- `git remote -v`  
  Displays the remote repositories linked to your local repository.

- `git remote add <name> <url>`  
  Adds a new remote repository.

- `git clone <url>`  
  Clones a repository from a remote source.

---

## **Additional Tips**
- Use `git status` frequently to understand what changes are staged, unstaged, or untracked.
- Use `git log --graph` to visualize the commit tree and branches.
- Use `git diff HEAD` to see changes against the latest commit.

---

This guide provides a foundation for Git usage. Practice these commands regularly to become proficient!
