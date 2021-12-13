## Git Cmds Cheat Sheet

## Basic Commands
* 'git init' - Initialize local Git repository
* 'git add .' - Add all files in and under current directory to index, staging them for commit
* 'git commit -m "Message"' - Commit changes to local repo with commit message "Message"

## Information Commands
* 'git status' - display current status of local working directory/repository
* 'git log' - Shows log history of commits
* 'git log --oneline' - Shows log history of commits compacted onto one line each

### Branching Commands
* 'git branch' - List local Git branches
* 'git branch newBranch' - Creates new newBranch
* 'git checkout newBranch' - check out local branch 'newBranch'
* 'git branch -M otherBranch' - renames current branch to 'otherBranch'

## Remote Commands
* 'git remote add origin remoteUrl' - Add alias "origin" for remote repository Url  "remoteUrl"
* 'git push origin main' - Push locally-committed changes to 'main' branch on remote repository
* 'git push - origin main' - Same, setting "origin main" as default for subsequent ' git push'

switched back to main from newBranch
checking add and commits
