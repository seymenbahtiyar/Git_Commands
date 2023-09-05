# Git Commands

This GitHub project is a handy reference for essential Git commands. Git is a powerful version control system that helps developers track changes, collaborate on projects, and manage code effectively. Whether you're a beginner or an experienced developer, this collection of Git commands will assist you in your daily workflow.

```bash
# Check the version of Git.
git --version

# List global Git configuration settings.
# The --global flag lists settings that apply to all projects.
git config --global --list

# Set the global username.
git config --global user.name "Name Surname"

# Set the global user email address.
git config --global user.email "Email"

# Change the working directory in Git.
cd "Folder Path"

# Initialize a new Git repository.
git init

# Create a copy of a Git repository from a remote source onto your local machine.
git clone "Clone URL"

# Add all files in the working directory to the staging area for the next commit.
git add .

# Check the status of files in the working directory and the staging area.
git status

# Commit the staged changes with a descriptive message.
# Use the -m flag to provide a commit message.
git commit -m "First Commit"

# Push a local branch to a remote repository.
# The -u flag sets up tracking for the branch.
# Replace "Clone URL" with the URL of the remote repository.
git push -u "Clone URL" master
```
