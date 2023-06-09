# README #
# Learning Git

Important steps for git workflow:

1. Initialize repository with git init
1a. Create a .gitignore file with touch .gitignore
2. Create changes to project files like with nano fileName
3. Check status of those files with git status
4. Stage changes for commit with git add fileName for one file or git add . for everything
5. Commit changes to version history with git commit
6. Commit with a description git commit -m 'Commit Description, use single or double quotes.'
7. Review previous changes with git log
8. git branch branchName makes new branch
9. git checkout branchName moves to declared branch
10. git branch -b newBranchName makes and moves to new branch all at once
11. git branch by itself shows which branch you're on, along with all other branches 
12. git branch -d branchNameToDelete deletes branch, but it can't be working branch!
13. git branch -D branchNameToDelete deletes branch when there are no commits. BE CAREFUL
14. git merge branchNameToMerge (do this from main!)
15. git push -u origin main to push to remote repo
16. git fetch to like, stage to computer
17. git diff origin/main main to check changes
18. git pull --ff-only origin main #=> --ff-only to Fast Forward => 'OM' to say where it's going
19. Essentially, git pull --ff-only combines git fetch and git merge --ff-only into one command.
20. git clone <remote repository url or local repository absolute path> <(new or existing)local 
directory name(unspecified uses name from url)> will clone existing repo to local
21. DO NOT NEST REPOSITORIES, SIR!
