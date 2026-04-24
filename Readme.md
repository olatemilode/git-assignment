#  Git Assignment — Version Control Workflow
A structured hands-on project demonstrating real-world Git 
and GitHub workflows from repository setup to remote collaboration.

##  Project Overview

This project covers core Git version control concepts through 
practical exercises — building disciplined commit habits,branching strategies, and remote repository management on GitHub.

### Repository Setup
- Initialising a local Git repository
- Configuring Git username and email
- Connecting local repo to remote GitHub repository

### Commit Workflow
- Staging files with `git add`
- Writing meaningful, structured commit messages
- Viewing commit history with `git log`

###  Remote Repository Management
- Pushing code to GitHub using PAT authentication
- Pulling remote changes
- Resolving conflicts
  
##  Tech Stack

| Tool | Usage |

| Git | Version control system 
| GitHub | Remote repository hosting 
| Linux/WSL | Local development environment 
| VSCode | Code editor 

##  Key Commands Used

```bash
# Initialise repo
git init

# Stage changes
git add .

# Commit with message
git commit -m "meaningful commit message"

# Create and switch branch
git checkout -b feature-branch

# Push to remote
git push origin main

# Pull latest changes
git pull origin main

# Check status
git status

# View commit history
git log --oneline
commit 
