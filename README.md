|`git fetch` | Download objects and refs from another repository |

## Branches
| Command | Description |
| ------- | ----------- |
|`git branch` | lists all LOCAL branches |
|`git branch -av` | lists all branches including remote with description |
|`git branch -d [branch name]` | deletes a local branch |
|`git pull`| Updates the local branch with the remote branch|
|`git checkout` | reint current branch |
|`git checkout [branch name]` | switch working branch |
|`git checkout -b [branch name]` | create a branch and switch to it |

## Git Push
| Command | Description |
| ------- | ----------- |
|`git push `|Push local commits to upstream branch|
|`git push -u origin branch-name`|Create an upstream branch and push commits|


## Config File
| Command | Description |
| ------- | ----------- |
|`git config -l`|List all local config|
|`git config -l --global`|List global config|
|`git config [name] [value]`|Add the name and value to the local config file|
|`git config --global [name] [value]`|Add the name and value to the GLOBAL config file|

## info
| Command | Description |
| ------- | ----------- |
|`git status`|Show status of the working tree|
|`git status -s`|Show short status message|
|`git diff [filename]`|Show differences in filename between commits|

## Commits
| Command | Description |
| ------- | ----------- |
|`git add [filename]`|Add file to staging|
|`git commit -m "[msg]"`|Commit staging on local|

## Stash
| Command | Description |
| ------- | ----------- |
|`git stash`|Stash changes in a rough directory|
|`git stash pop`|Remove a single stash and apply it on the working tree
|`git stash list`|Lists all stashes|

## Rename Branch
1) Rename Local Branch: `git branch -m <old-name> <new-name>`
2) Replace Remote Branch: `git push origin :old-name <new-name>`
3) Reset Upstream Branch: `git push origin -u <new-name>`
