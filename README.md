# 2021-09-01-git_dan

- `git init`: initialize git repository in current location
   - `pwd` : tell you where you are
- `git status` : tells you the git status
- `git add` <FILE> : adds <FILE> to the staging area
- `git commit`: opens editor
-  take notes
- `git log` : shows you the log
- `git diff` : dif current changes to last git state
- `git checkout <HASH> <FILE>`: revert file to the version in hash
 -`git checkout <HASH>` : revert everything to <HASH> in a detached HEAD
    - `git checkout main` /`git switch main`: to go back 

## Remotes

- `git add` <NAME> <URL>  : add a remore <NAMe> using the <URL>
   - `git remote add origin`
- `git remote -` : shows you what remotes you have
<<<<<<< HEAD
- `git push <REMOTE> <BRANCH>` : push our local changes 
- `git push <REMOTE> <BRANCH> : push our local changes in <BRANCH>

## Branches

- `git branch <NAME>`: create a branch where you are
- `git switch <NAME>`: move to branch
   - `git checkout <NAME>` 

- `git switch -c <BRANCH>` : creat and move to branch in 1 step

- pull request: merging a branch on the remote
  -update PR by pushing to the branch
  -merge the PR in the remote
  -delete branch on remote
- `git fetch --prune` : delete any local references where the remote branch was deleted
   - `git branch -D <BRANCH>`: force delete branch without merging
