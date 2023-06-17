# clone
```
git clone <repo>
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
# branching strategy
To make main branch look clean, use rebase in case of small group
in large group
use pull request - merge strategy.
developer just create new branch to add feature.
maintainer or director review the branch when merge with pull request
