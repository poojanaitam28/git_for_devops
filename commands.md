1. Create and Navigate to a New Directory
mkdir git_practice        # Create a new directory named 'git_practice'
cd git_practice/          # Navigate into the 'git_practice' directory
vim hello.txt             # Create a new file 'hello.txt' using Vim


2. Initialize a Git Repository
git init                  # Initialize an empty Git repository
ls -a                     # List all files, including hidden ones (to verify '.git' folder)


3. Working with Git Branches
git branch                # Check current branches
git checkout -b dev       # Create a new branch 'dev' and switch to it
git branch                # Verify the branches


4. Adding and Committing Changes
vim nibbu.txt             # Create or edit 'nibbu.txt' using Vim
git add nibbu.txt         # Stage 'nibbu.txt' for commit
git commit -m "added nibbu to dev branch"  # Commit the changes with a message


5. Switching Between Branches
git checkout master       # Switch back to the 'master' branch


6. Viewing Git Logs
git log --oneline         # View commit history in a condensed format


7. Final Branch Checks and Navigation
git checkout dev          # Switch back to 'dev' branch
ls                        # List files to verify branch contents
git checkout master       # Switch to 'master' branch again
ls                        # Confirm files on the 'master' branch.

