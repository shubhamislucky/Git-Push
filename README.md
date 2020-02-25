# Git-Push Error
If you get error in pushing to GitHub
# Normal Steps:
1. git init
2. git add .
3. git commit -m "First commit"
4. git remote add origin remote repository URL

![](git_copy.png)

5. git push -u origin master

## Error:
! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'https://github.com/usr/project.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

## Solution:

# git pull --rebase origin master
or 
# git pull --rebase (project link)
