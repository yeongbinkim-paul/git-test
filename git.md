# clone
```
git clone <repo>
```
# init in <directory>
```
git init
```
# check status
```
git status
git lg
git log
git diff
git diff head
```

# branch
```
git checkout -b branch #create new branch
git checkout branch #switch head branch
git branch -d branch #delete a local branch
git branch -m <name> #rename current branch
```
# add file/directory
```
git add <file/directory path>
```
# add with detail
```
git add -p
```
# commit
## simple commit
```
git commit -m "commit message"
git tag <tagname> # mark current current commit
git push --tags # publish tag
```
## detailed commit
```
git commit
>>
enter commit message
```
## append trivial change to previous commit
```
git add <change>
git commit --amend
```
# working with remote
## update remote
```
git fetch #don't integrate into head
git pull #directly integrate
```

# undo + revert changes in remote
```
git reset --hard <commit hash>
git push -f origin master
```
# branching strategy
To make main branch look clean, use rebase in case of small group
```
git rebase master
git rebase --continue #after resolving conflict
```

in large group
use pull request - merge strategy.
developer just create new branch to add feature.
maintainer or director review the branch when merge with pull request
