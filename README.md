# notebooks

Git
```
git log

# to revert to previous commit and maintain change
git reset --soft HEAD~1

# to revert to previous commit and discard change
git reset --hard HEAD~1

# to un-add file
git reset filename.py

# to un-add and discard change in file
git restore filename.py

# to pull and treat local commit as HEAD
git pull --rebase


### Squash multiple Commit into one
git rebase -i HEAD~3

in editor, pick a commit and squash all other, :wq to save and quit

git push -f origin branch_name

### check out remote branch
git fetch

# to list all available remote branch
git branch -v -a 

git checkout -b branch_name origin/remote_branch_name
# branch_name is name in local, rrecommand just to be same as remote_branch_name

```
