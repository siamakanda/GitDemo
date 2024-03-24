# Here I'm going to put all of my Git Commands while learning.

### 1. Check Git Version and Configure it to Work Properly
 To Check Git Version: git --version <br/>
 To Configure Git: git config user.name "usernameofgithub" <br/>
 To Configure Git: git config user.email "emailofgithub" <br/>

### 2. Git Basic Commands
To Clone Repo: git clone repo-url <br/>
To Check Status: git status <br/>
To Change Directory: cd example-folder <br/>

To View List of Files: ls <br/>
To View List of All Files including hidden: ls -a <br/>

### 3. Modifications
 To Add Files: git add filename <br/>
 To Add Multiple Files: git add . <br/>
 To Commit Files: git commit -m "Commit Message" <br/>

#### Sync Techninc
 To Push Changes to GitHub: git push origin main <br/>
 To Pull Changes From Github: git pull origin main <br/>

### 4. Git Init
  To Start Git for a New Folder: git init <br/>
  To Add a Remote Repo to VS Code Before Pushing: git remote add origin <-url-> <br/>
  To Check Current Remote Repo: git remote -v <br/>

### 5. Git Branches
To Check Current Branch: git branch <br/>
To Rename a Branch: git branch -M <-name-> <br/>
To Navigate to Other Branches: git checkout <-Branch_Name-> <br/>
To Create New Branch: git checkout -b <-New_Branch_Name-> <br/>
To Delete Branch: git branch -d <-Branch_Name-> <br/>

### 6. Merge Branches
a. To Compare Branches: git diff <-Branch_Name-> <br/>
b. To Merge 2 Branches: git merge <-Branch_Name-> <br/>

Or Simply Create a Pull Request.