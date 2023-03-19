# Git (Cheat Code) [<img align="left" height="55" width="55" alt="GIF" src="https://github.com/lonewolfnadhu/lonewolfnadhu/blob/main/assets/github.svg"/>](https://github.com/lonewolfnadhu/git-cheat-code)
Created by [Nadir Shah](https://github.com/lonewolfnadhu)

## 1) Git (Cheat Sheet)
[<img height="300" width="500" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/atlassian-git-cheatsheet-1.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/atlassian-git-cheatsheet-1.png)
[<img height="300" width="500" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/atlassian-git-cheatsheet-2.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/atlassian-git-cheatsheet-2.png)

## 2) Git (Workflow)
[<img height="300" width="500" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-1.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-1.png)
[<img height="300" width="500" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-2.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-2.png)
[<img height="300" width="500" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-3.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-3.png)
[<img height="300" width="500" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-4.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-4.png)

## 3) Set global 'User Name' and 'Email Id'
```
Step #1: git config --global user.name "Nadir Shah"
// Set User Name globally

Step #2: git config --global user.email "lonewolfnadhu@gmail.com"
// Set Email Id globally

Step #3: git config --list
// Shows global Git configuration
```

## 4) GitHub 'SSH Authentication' 
```
Step #1: cd ~
// Go to the main user directory (folder)

Step #2: pwd
// Make sure we are in main directory (folder)

Step #3: cd .ssh
// Check whether there any '.ssh' file

Step #4: mkdir .ssh
// Create '.ssh' file

Step #5: ssh-keygen -t rsa -C "lonewolfnadhu@gmail.com"
// Generate new ssh keygen (FYI: Make sure we are in main directory)

Step #6: ls -al
// Show all files in '.ssh' folder (FYI: Make sure we have 'id_rsa' and 'id_rsa.pub' files in '.ssh' folder)

Step #7: // Open 'id_rsa.pub' file and copy everthing and paste in github website where it shows to setup ssh key

Step #8: ssh -T git@github.com
// Connect to github over ssh protocol
```

## 5) Most used Git commands
```
Tip #01: git --version   <<<OR>>>   git version
// Show git version

Tip #02: git help   <<<AND>>>   git help config
// Show general help and configuration help

Tip #03: PRESSS 'q'   <<<OR>>>   'Q'
// Exit to terminal

Tip #04: git config --global user.name "Nadir Shah"
// Configure git username as 'Nadir Shah' globally

Tip #05: git config --global user.email "lonewolfnadhu@gmail.com"
// Configure git email as 'lonewolfnadhu@gmail.com' globally

Tip #06: git config --global --list
// List out all global configuration settings

Tip #07: touch README.md
// Create a new file name 'README.md'

Tip #08: cat README.md
// Open 'README.md' file in terminal

Tip #09: vim README.md
// Open 'README.md' file in terminal
// PRESS 'i' to edit 'README.md' file
// PRESS 'esc' to go back to terminal file / exit from terminal
// ENTER ':wq' to save 'README.md' file

Tip #10: pwd
// Show current directory (folder) (present working directory (folder))

Tip #11: cd workspace
// Move to 'workspace' folder

Tip #12: ls
// Show files and folders in current directory (folder) without parameters, will list non-hidden folders and files

Tip #13: ls -a
// Show current files in that directory (folder) including hidden files

Tip #14: git init git-demo
// Create or initialise empty git repository

Tip #15: git status
// Modification or changes in current repository
// Show which files have been modified in the working directory (folder) and git's staging area

Tip #16: git add README.md
// Adds the new or newly modified 'README.md' file to git's staging area

Tip #17: git add .
// Adds all new or newly modified files to git's staging area

Tip #18: git commit -m "Initial Commit"
// Commits all files currently in git's staging area
// The '-m' parameter allows for a commit message directly from the command line

Tip #19: git commit -am "Adding some more items"
// Directly commit newly modified tracked files

Tip #20: clear
// Clear all commands from the terminal screen

Tip #21: git reset HEAD README.md
// "Unstage" the specified file from git's staging area

Tip #22: git checkout -- README.md
// Back out any changes made to the specified file and replace it with the version last committed in git

Tip #23: git log
// Git commit history

Tip #24:  git log --oneline --graph --decorate --color
// Much better compact view of git commit history

Tip #25: mkdir Demo
// Creating a new directory (folder) name 'Demo'

Tip #26: git rm Demo.md
// Deleting 'Demo.md' file

Tip #27: mv Demo.txt subfolder/
// Move 'Demo.txt' to 'subfolder/' directory (folder)

Tip #28: git remote -v
// List out all git repositories

Tip #29: which git
// Shows git location

Tip #30: open Text1.txt
// It will open Text1.txt file

Tip #31: open -a Atom Text1.txt
// It will open Text1.txt file in Atom Software

Tip #32: git branch dev
// A new branch will be created from main branch named 'dev'

Tip #32: git checkout dev
// Switch to 'dev' branch from current branch

Tip #32: git branch
// To check all branches in the current repository
```

## 6) Git (Certificate)
[<img height="450" width="650" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-certificate.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/resources/git-certificate.pdf)

<!-- Connect | START -->
[<img align="left" height="55" width="55" alt="GIF" src="https://github.com/lonewolfnadhu/lonewolfnadhu/blob/main/assets/connect-me.gif"/>](https://github.com/lonewolfnadhu/git-cheat-code)

## Connect with me


[<img height="200" width="200" src="https://github.com/lonewolfnadhu/lonewolfnadhu/blob/main/assets/nadir-shah.jpg">](https://github.com/lonewolfnadhu/git-cheat-code)

[<img width="40px" src="https://github.com/lonewolfnadhu/lonewolfnadhu/blob/main/assets/instagram.svg"/>](https://www.instagram.com/lonewolfnadhu/)
[<img width="40px" src="https://github.com/lonewolfnadhu/lonewolfnadhu/blob/main/assets/linkedin.svg"/>](https://www.linkedin.com/in/lonewolfnadhu/)
[<img width="40px" src="https://github.com/lonewolfnadhu/lonewolfnadhu/blob/main/assets/github.svg"/>](https://github.com/lonewolfnadhu)

Made with ❤️

Copyright © 2016-2023 [Nadir Shah](https://linktr.ee/lonewolfnadhu)
<!-- Connect | END -->





