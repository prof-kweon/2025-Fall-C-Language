# 2025-Fall-C-Language
This is a github for C programming language of Fall 2025 semester

### Professor: Kweon, Tae Deok  
   Email: tdkweon@wsu.ac.kr  
   Office Phone   : (042) 629-6647  
   Office Location: Endicott building W19 232  
   Office Hours   : Mon. ~ Thr. (13:00 ~ 17:00)  

---

# **Uploading Files to GitHub Without GitHub Desktop or Git Commands**
## *(From local PC - Drag & Drop Method)*

If you want to upload files to your GitHub repository without using **GitHub Desktop** or **Git commands**, you can use the simple **Drag & Drop method** directly from your web browser.

---

## **Method: Drag & Drop File Upload on GitHub**
### **Step 1: Open Your GitHub Repository**
1. Go to [GitHub](https://github.com/) and **log in** to your account.
2. Navigate to the repository where you want to upload files.
<img width="794" height="308" alt="image" src="https://github.com/prof-kweon/2025-Fall-C-Language/blob/mainimg/2025-09-11%20115921.png" />

### **Step 2: Open the Upload Interface**
1. Inside the repository, click on the **"Add file"** button at the top.
2. Select **"Upload files"** from the dropdown menu.

### **Step 3: Drag & Drop Files**
1. Drag the file(s) from your computer and drop them into the upload area.
2. You can also click **"Choose your files"** to browse and select files manually.

### **Step 4: Commit and Save**
1. Enter a commit message (e.g., "Added new files").
2. Click **"Commit changes"** to upload the files to GitHub.

---

## **Switching Between Users on a Shared PC**
- If multiple users share the same PC, each person should **log out of GitHub** and **log in with their own account** before uploading files.
- Ensure that you are in the correct repository before uploading.

This method is the simplest way for beginners to upload files to GitHub without using additional software.

---
# **Uploading Files to GitHub Using Codespaces**
## *(Codespaces Method)*

If you want to upload files to GitHub without using **GitHub Desktop** or **Git commands**, you can use **GitHub Codespaces**, a web-based development environment.

---
## **Method: Uploading Files in GitHub Codespaces**
### **Step 1: Open Your Repository in Codespaces**
1. Go to [GitHub](https://github.com/) and **log in**.
2. Navigate to the repository where you want to upload files.
3. Click the **"Code"** button and select **"Create codespace on main"**.
4. Wait for the Codespaces environment to load.

### **Step 2: Open the File Explorer**
1. Once inside Codespaces, look for the **File Explorer** on the left sidebar.
2. If the sidebar is hidden, click on the **Explorer** icon (📂).

### **Step 3: Upload Files**
1. Right-click inside the File Explorer.
2. Select **"Upload..."** from the context menu.
3. Choose the files from your computer and upload them.

### **Step 4: Commit and Push Changes**
1. Click the **Source Control (Git icon) 🔃** in the left sidebar.
2. Type a commit message (e.g., "Added new files").
3. Click **"Commit & Push"** to upload the files to GitHub.

---

## **Switching Between Users on a Shared PC**
- Each user should **log out of GitHub** and **log in with their own account** before using Codespaces.
- Make sure you are in the correct repository before uploading files.

This method is great for users who prefer a **web-based** solution without installing software.

---

# Git Usage Guide 

## English Version

### 1. Installing Git
- Download and install Git from [git-scm.com](https://git-scm.com/).
- Check the installation:
  ```sh
  git --version
  ```

### 2. Configuring Git
- Set your user name and email:
  ```sh
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  ```
- Check your configuration:
  ```sh
  git config --list
  ```

### 3. Initializing a Repository
- Create a new repository:
  ```sh
  git init
  ```
- Clone an existing repository:
  ```sh
  git clone <repository_url>
  ```

### 4. Basic Commands
- Check the repository status:
  ```sh
  git status
  ```
- Add files to staging:
  ```sh
  git add <file>
  ```
- Commit changes:
  ```sh
  git commit -m "Your commit message"
  ```
- View commit history:
  ```sh
  git log
  ```
- Push changes to a remote repository:
  ```sh
  git push origin main
  ```
- Pull changes from a remote repository:
  ```sh
  git pull origin main
  ```

### 5. Branching and Merging
- Create a new branch:
  ```sh
  git branch <branch_name>
  ```
- Switch to a branch:
  ```sh
  git checkout <branch_name>
  ```
- Merge branches:
  ```sh
  git merge <branch_name>
  ```
- Delete a branch:
  ```sh
  git branch -d <branch_name>
  ```

### 6. Undoing Changes
- Undo the last commit:
  ```sh
  git reset --soft HEAD~1
  ```
- Discard uncommitted changes:
  ```sh
  git checkout -- <file>
  ```
- Revert a commit:
  ```sh
  git revert <commit_hash>
  ```

---
