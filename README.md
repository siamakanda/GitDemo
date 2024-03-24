# Here I'm going to put all of my Git Commands while learning.

### 1. Check Git Version and Configure it to Work Properly
 To Check Git Version: git --version <br/>
 To Configure Git: git config user.name "usernameofgithub" <br/>
 To Configure Git: git config user.email "emailofgithub"

### 2. Git Basic Commands
To Clone Repo: git clone repo-url
To Check Status: git status
To Change Directory: cd example-folder

To View List of Files: ls
To View List of All Files including hidden: ls -a

### 3. Modifications
 To Add Files: git add filename
 To Add Multiple Files: git add .
 To Commit Files: git commit -m "Commit Message"

#### Sync Techninc
 To Push Changes to GitHub: git push origin main
 To Pull Changes From Github: git pull origin main

### 4. Git Init
  To Start Git for a New Folder: git init
  To Add a Remote Repo to VS Code Before Pushing: git remote add origin <-url->
  To Check Current Remote Repo: git remote -v

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