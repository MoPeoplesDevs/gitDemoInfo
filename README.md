# Git Notes

## Common Commands
```bash
git add <file>									# add single file to stage
git add -A										# add all files not ignored
git commit -m '<msg>'							# commits whats has been staged
git status										# shows where you are (branch) what has been added or removed or needs add/removed

git branch										# list of branches
git branch -D <branchName>						# deletes local branch
git checkout -b <branchName>					# makes a new branch
git chekcout									# switches context to target branch
git merge <branch>								# brings commits history from target branch to current branch

git pull origin <branchName>					# gets remote branch and merge
git fetch origin								# get remote branch info
git push origin <branchName>					# push specified local branch to remote

git log											# list of commit info 'q' to quit
git tag -a '<v1.0.0>' -m '<release msg>'		# tag the current branch most recent commit (HEAD)

git reset --hard <id or tag or HEAD>			# revert back to target and check it out 

```