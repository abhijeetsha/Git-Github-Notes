# Git-Github-Notes
## What is Git?
### Ans: Git is an open-source Distrubuted version control tools that helps developers track changes in their code and collaborate with others.
### 💡 In Simple Terms:
* Git keeps a history of your project, allowing you to go back to any version and work safely in teams without overwriting each other’s work.

## ⚙️ Key Features of Git:
* Tracks changes in files (especially code)
* Supports branching and merging
* Works offline
* Helps in collaboration with teams
* Used by tools like GitHub, GitLab, and Bitbucket

## ☁️ What is GitHub?
* GitHub is a cloud-based hosting platform that uses Git for version control.
It allows you to store your repositories online and collaborate with others.
### 💡 In Simple Words:
* Git is the tool that manages your code history;
* GitHub is the website where your Git projects live.

## 🧰 Basic Git / GitHub Commands:
### First Command when you installed git tools on your systems.
* git --version
* git config --global user.name "Your Name"
* git config --global user.email "you@example.com"
* git config --list

### 🔹 1. Initialize a Local Repository 
* git init

### 🔹 2. Clone a Remote Repository (from GitHub)
* git clone <repository_url>

### 🔹 3. Check Status
* git status

### 🔹 4. Add Files to Staging Area
### Add a specific file
* git add "filename"
### Add all files     
* git add .                

### 🔹 5. Commit Changes
* git commit -m "Your commit message"

### 🔹 6. Connect Local Repo to GitHub
* Create First SSH-key take public-key and add to github, then.
* ssh-keygen
* git remote add origin <repository_url>

### 🔹 8. Pull Latest Changes from GitHub
* git pull origin main

### 🔹 7. Push to GitHub
* git push -u origin main

### 🔹 9. View Commit History
* git log

### 🔹 10. Create and Switch Branches
### Create branch
* git branch <branch_name>
### Switch branch   
* git checkout <branch_name>
### Merge branch into main
* git merge <branch_name>

### 🔹 11. Remove Remote Connection
* git remote remove origin

## 🧾 Common GitHub Work Flow Example:-
* git init
* git add .
* git commit -m "Initial commit"
* git branch -m main
* git remote add origin https://github.com/username/repo.git
* git pull origin main
* git push --set-upstream origin main >> for 1st time you pushing git to github.
* git push -u origin main >> for pushing same dir again and again git to github.

