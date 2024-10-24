# Git Commands Cheat Sheet

## 1. Basic Commands
- **Print Current Directory Path**  
  `pwd`

- **List Files in a Directory**  
  `ls`

- **Create a Directory**  
  `mkdir <directory_name>`

- **Change Directory**  
  `cd <directory_name>`

## 2. Git Initialization
- **Initialize a New Git Repository**  
  `git init`

## 3. Working with Files
- **Create Files**  
  `touch <file1> <file2>`

- **Delete Files**  
  `rm -rvf <file_name>`

## 4. Git Configuration
- **Set Global Git Username**  
  `git config --global user.name "<your_username>"`

- **Set Global Git Email**  
  `git config --global user.email "<your_email>"`

## 5. Staging and Status
- **Check Git Repository Status**  
  `git status`

- **Add File(s) to the Staging Area**  
  `git add <file_name>`

- **Remove File from Staging Area**  
  `git rm --cached <file_name>`

## 6. Committing Changes
- **Commit Staged Files with a Message**  
  `git commit -m "<commit_message>"`

## 7. Branching
- **Create a New Branch**  
  `git checkout -b <branch_name>`

- **Switch to an Existing Branch**  
  `git switch <branch_name>`

## 8. File Restoration
- **Restore a File to its Previous Version**  
  `git restore <file_name>`

## 9. Git Log
- **View Commit History**  
  `git log`

- **View Simplified Commit History**  
  `git log --oneline`

## 10. Merging and Switching Branches
- **Switch to Master Branch**  
  `git checkout master`

- **Switch to a Specific Branch**  
  `git checkout <branch_name>`

## 11. Miscellaneous Commands
- **View Command History**  
  `history`

- **Open a File in Vim**  
  `vim <file_name>`

- **Edit a File Using Echo**  
  `echo "<content>" > <file_name>`

## 12. File Contents
- **Display File Content**  
  `cat <file_name>`
