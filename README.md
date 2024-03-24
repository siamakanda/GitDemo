# GitDemo
This is my Git Learning Process (Ignore)

## Here I'm going to put all of my Git Commands while learning.

### 1. Check Git Version and Configure it to Work Properly
 To Check Git Version: git --version <br/>

 To Configure Git: git config user.name "usernameofgithub" <br/>
 To Configure Git: git config user.email "emailofgithub"

### 2. Git Basic Commands
Clone: git clone repo-url
Project Status: git status
Change Directory: cd example-folder
To View List of Files: ls
To View List off all files including hidden: ls -a

### 3. Modifications
 To add files: git add filename
 To add multiple files: git add .
 To Commit files: git commit -m "Commit Message"

 To Push Changes to GitHub: git push origin main

### 4. Git Init
  To start Git for a new folder: git init
  To add a remote repo to vscode before pushing: git remote add origin <-url->
  To check current remote repo: git remote -v

### 5. Git Branches
To Check Current Branch: git branch
To Rename a Branch: git branch -M <-name->
To Navigate to Other Branches: git checkout <-Branch_Name->
To Create New Branch: git checkout -b <-New_Branch_Name->
To Delete Branch: git branch -d <-Branch_Name->

### 6. Merge Branches
a. To Compare Branches: git diff <-Branch_Name->
b. To Merge 2 Branches: git merge <-Branch_Name->

Or Simply Create a Pull Request.