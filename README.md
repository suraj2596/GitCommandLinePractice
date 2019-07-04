## Intro:
By Corey M Schafer [link][1]

## Notes:

### Video 1/6:

 1. `git --version` 
 2. `git config `
 3. `git init `
 4. `git status `
 5. `git ignore `
 6. `git add -A`
 7. `git reset`
 8. `git commit -m “…” `
 9. `git log `
 10. `git remote -v `
 11. `git branch -a :lists local and remote branches `
 12. `git diff `
 13. `git pull origin master `
 14. `git push origin master `
 15. `git branch `
 16. `git branch `
 17. `git checkout `
 18. `git merge  `
 19. `git branch -d `
 20. `git push --delete origin `

### Video 2/6:

 1. `git checkout`  : undo recent uncommited changes
 2. `git commit --amend -m ""` : change message of the latest commit. But changes the git hstory
 3. `git commit --amend` : incase u forgot to commit a file, doing this will add it to the latest commit. Do this only if you haven't pushed your changes to other people(because it changes the git history) 
 4. `git log --stat` : Shows detailed logs
 5. `git cherry-pic `
 6. `git reset --soft ` : resets to specified commit but later files stay in stafing area
 7. `git reset ` : resets to specified commit but later files DONT stay in staging area
 8. `git reset --hard ` : removes later files
 9. `git clean -df` : cleans the staging area
 10. `git reflog` : logs of what you've been doing. And u can restore using checkout and the hash shown. But hwne we do this, we'll be in a detached head state. so, we need to save these changes by creating another branch 
 11. `git revert ` : This adds a new commit without changing the git history.
 
 
### Video 3/6:

 1. `git stash save "message"` : saves changes and reverts the file
 2. `git stash list` : lists all the stash messages
 3. `git stash apply stash@{}` : puts back the changes. But doesnt remove the stash's saved messages
 4. `git checkout --.` : undos 
 5. `git stash pop` : takes the recent stash and applies it and removes that saved stash
 6. `git stash drop stash@{}` : removes the specified saved stash
 7. `git stash clear` : removes all saved stashes
 8. 
 
### Video 4/6:
 1. diffmerge - A tool for viewing and merging with a GUI
 2. 
 
### Video 6/6 : Difference between add -a, add -A and other ways of adding files to the staging area...

 1. `git add -A` : all in the git directory
 2. `git add -A ` : Adds files below this directory
 3. `git add ` : same as above
 4. `git add --no-all` : doesn't stage deleted files
 5. `git add -u` : doesn't add untracked files
 6. `git add .` : Adds files from current directory
 7. `git add *` : wont be able to add hidden/deleted files as is* is a shell command
 8. 








































  [1]: https://www.youtube.com/watch?v=FdZecVxzJbk&list=PL-osiE80TeTuRUfjRe54Eea17-YfnOOAx&index=2
