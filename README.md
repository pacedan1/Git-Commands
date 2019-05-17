|`git fetch` | Download objects and refs from another repository |

## Branches
| Command | Description |
| ------- | ----------- |
|`git branch` | lists all LOCAL branches |
|`git branch -av` | lists all branches including remote with description |
|`git branch -d [branch name]` | deletes a local branch |
|`git checkout` | reint current branch |
|`git checkout [branch name]` | switch working branch |
|`git checkout -b [branch name]` | create a branch and switch to it |


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

