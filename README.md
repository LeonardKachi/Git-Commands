# Git Commands Cheat Sheet 🚀

## Overview
This repository serves as a **comprehensive guide** to essential **Git commands** for version control and collaboration with **GitHub**. Whether you're a beginner or an experienced developer, this cheat sheet will help you efficiently manage repositories and streamline your workflow.

## Getting Started
Before using Git, ensure you have it installed:
```sh
# Check if Git is installed
git --version

# Install Git (for Debian-based systems)
sudo apt update && sudo apt install git -y
```

## Basic Git Commands
### Setup
```sh
# Configure Git with your name and email
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Repository Management
```sh
# Initialize a new repository
git init

# Clone an existing repository
git clone <repository-url>
```

### Working with Commits
```sh
# Check repository status
git status

# Add files to staging
git add <file>  # Add a specific file
git add .       # Add all files

# Commit changes
git commit -m "Your commit message"
```

### Branching & Merging
```sh
# Create a new branch
git branch <branch-name>

# Switch branches
git checkout <branch-name>

# Merge branches
git merge <branch-name>
```

### Pushing & Pulling
```sh
# Push changes to a remote repository
git push origin <branch-name>

# Pull updates from a remote repository
git pull origin <branch-name>
```

### Undoing Changes
```sh
# Unstage a file
git reset <file>

# Undo last commit
git reset --soft HEAD~1

# Hard reset (erases changes)
git reset --hard HEAD~1
```

### Handling Conflicts
```sh
# Check for merge conflicts
git diff

# Resolve conflicts, then commit changes
git add .
git commit -m "Resolved merge conflicts"
```

## Contributing
Feel free to contribute by submitting pull requests or opening issues. Let’s make this an even better resource for developers! 🚀

## License
This project is licensed under the MIT License. See the LICENSE file for details.
