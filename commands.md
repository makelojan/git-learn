# GIT COMMANDS

Some useful commands to use in command-prompt.


## Command-prompt

* $ cls == Clear command prompt screen
* $ clear == Clear command prompt screen
* $ cd [path] == Change directory
* $ mkdir [folder_name] == Create a folder
* $ touch [filename].[file_extension] == Create file
* $ exit == Exit the command prompt


## Initialize a repository

* $ git clone [HTTPS] == Clone a repository from GITHub
* $ git init = Initialize empty repository
* $ git remote add [origin] [HTTPS] == Remotely add a repository referance
* $ git remote -v == Check for remote repository refereances


## Configuration

Configure name and email for commitment user information.

* $ git config --global user.name "[username]"
* $ git config --global user.email "[mail@email.com]"


## Commit and push

* $ git status == Check the status of current branch
* $ git add [file_name] == Add changes to the future commit
* $ git commit -m "[commit_message]" -m "[commit_description]" == Commit changes with a descriptive message
* $ git push -u origin [HEAD:main] == Push changes and commitments to a remote repository


## Branches

* $ git branch == List existing and currently active branches
* $ git checkout [branch_name] == Switch branches
* $ git checkout -b [branch_name] == Create a new branch


## Merge and pull

* $ git diff [branch_name] == Compare the active branch with the target branch
* $ git merge [branch_name] == Merge the target branch into the active branch
* $ git branch -d [branch_name] == Delete target branch
* $ git pull origin [main] == Pull the target branch from a remote repository


## Commit log and revert changes

* $ git reset [file_name] == Revert an add command
* $ git reset HEAD~1 == Revert previous commit
* $ git log => (SPACEBAR, Q) == List commit history
* $ git reset --hard [commit_hash] == Change the current repository state into the target commitment state

