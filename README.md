## Git Cheat Sheet

Summary of useful `git` commands.
### Basic Commands
* `git init` - Initialize local git repository
* `git status` - Show status of working directory
* `git add .` - Add everything in current directory to git index
* `git commit -m "Some message"` - Commit current work to local repo
* `git log` - Show git commit history
* `git log --oneline` - Show git commit history (compact)
* `git config -l` - List git configuration

### Branching Commands
* `git branch` - List branches in current repository
* `git branch someBranch` - Create branch `someBranch`
* `git checkout someBranch` - Move to branch `someBranch`
* `git checkout -b otherBranch` - Create and checkout `otherBranch`
* `git pull origin main` - Pull remote `main` into current branch
* `git push origin newBranch` - Push current committed branch to remote

### Remote Commands
* `git remote add origin URL` - for github `URL`
