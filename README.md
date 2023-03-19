# Cheat Code | Configurations | Shortcuts [<img align="left" height="55" width="55" alt="GIF" src="https://github.com/lonewolfnadhu/lonewolfnadhu/blob/main/assets/github.svg"/>](https://github.com/lonewolfnadhu/git-cheat-code)
Created by [Nadir Shah](https://github.com/lonewolfnadhu)

## Repository Includes
```
01) Git (Cheat Sheet)
02) Git (Workflow)
03) Set global 'User Name' and 'Email Id'
04) GitHub 'SSH Authentication'
05) Most used Git commands
06) 'Terminal' configuration
07) 'VS Code' configuration
08) Open an 'iOS Simulator'
09) Open an 'Android Emulator'
10) Git (Certificate)
```

### 01) Git (Cheat Sheet)
[<img height="250" width="400" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/atlassian-git-cheatsheet-1.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/atlassian-git-cheatsheet-1.png)
[<img height="250" width="400" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/atlassian-git-cheatsheet-2.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/atlassian-git-cheatsheet-2.png)

### 02) Git (Workflow)
[<img height="250" width="400" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-1.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-1.png)
[<img height="250" width="400" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-2.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-2.png)
[<img height="250" width="400" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-3.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-3.png)
[<img height="250" width="400" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-4.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-workflow-4.png)

### 03) Set global 'User Name' and 'Email Id'
```
Step #1: git config --global user.name "Nadir Shah"
// Set User Name globally

Step #2: git config --global user.email "lonewolfnadhu@gmail.com"
// Set Email Id globally

Step #3: git config --list
// Shows global Git configuration
```

### 04) GitHub 'SSH Authentication'
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

### 05) Most used Git commands
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

### 06) 'Terminal' configuration
```
[FYI: Configure 'Terminal' as below for better performance and making work faster]

Step #01: Make current user a root user
Type: dsenableroot

Step #02: Install ZSH via homebrew
Type: brew install zsh

Step #03: Make it your default shell
Type: chsh -s /bin/zsh

Step #04: Verify the shell
Type: echo $SHELL (Note: Check whether it prints '/usr/bin/zsh')

Step #05: Install 'Oh My Zsh'
Type: sudo sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

Step #06: Clone 'PowerLeve10K theme'
Type: git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k

Step #07: Clone 'autosuggestion'
Type: sudo git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions

Step #08: Clone 'highlighting'
Type: sudo git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting

Step #09: Open ".zshrc" and replace these sections / files
1. ZSH_THEME="powerlevel10k/powerlevel10k"
2. ENABLE_CORRECTION="true"
3. plugins=(git zsh-autosuggestions zsh-syntax-highlighting)

Step #10: To final configuration
Type: p10k configure

Reference: 
https://medium.com/@shivam1/make-your-terminal-beautiful-and-fast-with-zsh-shell-and-powerlevel10k-6484461c6efb
```

### 07) 'VS Code' configuration
```
[FYI: Install below 'VS Code' packages to make your IDE more stable and for better performance]

Package #01: 'React Native Tools'

Package #02: 'Babel JavaScript'

Package #03: 'ESLint'

Package #04: 'Prettier - Code formatter'

Package #05: 'Auto Close Tag'

Package #06: 'Auto Complete Tag'

Package #07: 'Auto Rename Tag'

Package #08: 'Color Highlight'

Package #09: 'Path Intellisense'

Package #10: 'Rainbow Brackets'

Package #11: 'SVG Viewer'

Package #12: 'TODO Highlight'

Package #13: 'change-case'

Package #14: 'Code Spell Checker'

Package #15: 'npm' and 'npm intellisense'

Package #16: 'Material Icon Theme' [Note: Theme for the 'Icons']

Package #17: 'Night Owl' [Note: Theme for the 'IDE']

Package #18: 'code .' [Note: To open 'VS Code']
```

### 08) Open an 'iOS Simulator'
```
Step #1: Type 'xcrun simctl list devices'
[FYI: List all 'iOS Simulators' / 'Physical Devices']

Step #2: Type 'open -a Simulator'
[FYI: To open ios simulator, Default will be 'iPhone 14']
```

### 09) Open an 'Android Emulator'
```
Step #1: Type 'adb devices'
FYI: List all 'Android Emulators' / 'Physical Devices']

Step #2: Type 'emulator -avd Pixel'
[FYI: To open android emulator named 'Pixel', if it doen't open type 'source ~/.bash_profile' then type 'emulator -avd Pixel' again]
```

### 10) Git (Certificate)
[<img height="450" width="650" src="https://github.com/lonewolfnadhu/git-cheat-code/blob/main/assets/git-certificate.png">](https://github.com/lonewolfnadhu/git-cheat-code/blob/main/resources/git-certificate.pdf)

<!-- Connect | START -->
[<img align="left" height="50" width="50" alt="GIF" src="https://github.com/lonewolfnadhu/lonewolfnadhu/blob/main/assets/connect-me.gif"/>](https://github.com/lonewolfnadhu/git-cheat-code)

## Connect with me


[<img height="200" width="200" src="https://github.com/lonewolfnadhu/lonewolfnadhu/blob/main/assets/nadir-shah.jpg">](https://github.com/lonewolfnadhu/git-cheat-code)

[<img width="35px" src="https://github.com/lonewolfnadhu/lonewolfnadhu/blob/main/assets/instagram.svg"/>](https://www.instagram.com/lonewolfnadhu/)
[<img width="35px" src="https://github.com/lonewolfnadhu/lonewolfnadhu/blob/main/assets/linkedin.svg"/>](https://www.linkedin.com/in/lonewolfnadhu/)
[<img width="35px" src="https://github.com/lonewolfnadhu/lonewolfnadhu/blob/main/assets/github.svg"/>](https://github.com/lonewolfnadhu)

Made with ❤️

Copyright © 2016-2023 [Nadir Shah](https://linktr.ee/lonewolfnadhu)
<!-- Connect | END -->





