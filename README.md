# Git Commands

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
git push -u "Clone URL" main
```
