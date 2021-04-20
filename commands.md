# GIT COMMANDS

Some useful commands to use in command-prompt.


## Command-prompt

* $ clear == Clear command prompt
* $ cd [path] = Change directory
* $ mkdir [folder_name] = Create a folder
* $ touch [filename].[file_extension] == Create file


## Initialize a repository

* $ git clone [HTTPS]
* $ git init = Initialize empty repository
* $ git remote add [origin] [HTTPS]
* $ git remote -v


## Configuration

* $ git config --global user.name "[username]"
* $ git config --global user.email "[mail@email.com]"


## Commit and push

* $ git status
* $ git add [file_name]
* $ git commit -m "[commit_message]" -m "[commit_description]"
* $ git push -u origin [HEAD:main] 


## Branches

* $ git branch
* $ git checkout [branch_name]
* $ git checkout -b [branch_name]


## Merge and pull

* $ git diff [branch_name]
* $ git merge [branch_name]
* $ git branch -d [branch_name]
* $ git pull origin [main]


## Commit log and revert changes

* $ git reset [file_name]
* $ git reset HEAD~1
* $ git log => (SPACEBAR, Q)
* $ git reset --hard [commit_hash]
