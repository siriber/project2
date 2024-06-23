git init
git status
git add .
git add README.md
git commit -m "message" -m "description"
git log

to add changes to your project
git add .
git commit -m "version 1" --ame

git reset (undo changes)

git Checkout (Use for viewing previous version of codes)

The syntax is 

git checkout Commit hash (e.g acf3f05a3531f19e7fd2ca4cf80b320db53503a5)

git shows the current commit and all the versions behind the current commit.
It does not show the versions in front of the current commit.

Example: If you have 3 commits (version 1, 2 and 3) and the current commit is 
version 2, git log will only show Version 2 (the current commit) and version 1 
(the version behind it. It will not show version 3 because version 3 commit is in front
of version 2.)

In order to show all the commits in our version history use the command prompt
git log --all

HEAD indicates the version we are currently viewing

git log --all --graphg
This shows branching effect in version history

If the command prompt do not allow you to type more commands
Press letter Q (for quite) on your keyboard to enable typing.

Branch Name

Branch names help us to easily switch versions
syntax
git checkout branch name e.g master 
this will switch your to a version named master

git master point to the latest commit in any given project


SUMMARY
Create Version
git init
git status
git add .
git commit -m "message"

View Previous Versions
git log --all --graph
git checkout <commit_hash>
git checkout <commit_branch_name>


Use this command to remove git from your project
rm -rf .git