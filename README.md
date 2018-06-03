# Learning Git!

Learning how to use Git. 

Most used commands:
git status - tells you what has been updated.
git add filename - adding a file to staging and Git will start tracking changes.
git commit -m "message content" - registers changes to get ready to upload, a message is also required.
git push - pushing a file/changes on to Github.
*git pull - do it every time you get back to the project before you make any changes.


Other commands:
git diff filename - see the differences between the working directory and the staging area.
git log - to refer back or view previous versions.

The commit you are currently on/latest commit, is known as the HEAD commit.
git show HEAD - show info and all the file changes that have been committed.

Backtracking:
git checkout HEAD filename - restore the file to when you last made a commit.
git reset HEAD filename - removes the file from the staging area if you decide you don't want to commit it.
git reset commit_SHA - undo a commit, use the first 7 characters if the SHA (hash code) of a previous commit. 

Branching:
Having different branches allows you to work on multiple versions. Your main branch is known as the 'master' branch.
git branch - tells you which branch you're on.
git branch new_branch - to create a new branch.
git checkout branch_name - to switch to another branch.

=======


