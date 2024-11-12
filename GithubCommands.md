| Command                                        | Usage                                                     |
| ---------------------------------------------- | --------------------------------------------------------- |
| https://www.git-scm.com                        | git documentation                                         |
| https://git-scm.com/book/en/v2                 | git book                                                  |
| git config user.name                           | get user name                                             |
| git config user.email                          | get current user email                                    |
| git config --global user.name "Aditya Pathak"  | set user name to Aditya Pathak                            |
| git config --global user.email "test@test.com" | set user email to test@test.com                           |
| git status                                     | gives info on the current repo                            |
| git init                                       | Enables / Initializes git in current folder               |
| git add File.txt                               | Add the file to staging area.                             |
| git add . OR git add -A                        | Stage all changes                                         |
| git commit -m "My message"                     | Commit the changes from staging area with message         |
| git commit                                     | without message opens editor to add comments.             |
| git commit --amend                             | ammend changes in last commet                             |
| git commit -a -m "My message"                  | Add and commit in one step                                |
| git commit -am "My message"                    | Add and commit in one step                                |
| git log                                        | view log of commits in repo. q to exit log                |
| git log --oneline                              | shows log within one line                                 |
| git config --global core.editor "code --wait"  | configure VS code as default editor for commit messages   |
| .gitingnore file                               | to force git to ignore certain files                      |
| git branch                                     | list of branches in current repo                          |
| git branch Feature1                            | Create branch called Feature1 based on current            |
| git switch Feature1                            | switches to Feature1 Branch                               |
| git switch -c Feature1                         | Creates and switches to Feature1 Branch based on current  |
| git checkout Feature1                          | Switches to Feature1 Branch                               |
| git checkout -b Feature1                       | Creates and Switches to Feature1 Branch                   |
| git branch -d DeleteMe                         | Deletes DeleteMe branch                                   |
| git branch -m NewName                          | Move / Rename current branch                              |
| git branch -r                                  | list of remote branches local repo knows about            |
| git merge bugfix                               | Merge bugfix branch into current branch                   |
| git diff                                       | List changes in working directory that are not staged     |
| git diff HEAD                                  | changes in working tree since last commit                 |
| git diff --staged or --cached                  | changes between staging and last commit                   |
| git diff HEAD [filename1] [FileName2]          | show diff only in perticual file                          |
| git diff HEAD HEAD~1                           | Diff between current head and previous commit             |
| git diff Head~1                                | diff between current head vs previous commit              |
| git diff branch1..branch2                      | diff between 2 branches                                   |
| .. can be replaced with " " (space)            | it will have same effect                                  |
| git diff commit1Hash..commit2Hash              | diff between 2 commits                                    |
| git clone https://github.com/co...             | to clone git repo in local                                |
| git stash or git stash save                    | saves uncommited changes to stash                         |
| git stash list                                 | gives list of current stash                               |
| git stash pop                                  | brings back the changes to same or different branch       |
| git stash apply                                | changes remain on stash and also comes into branch        |
| git stash apply stash@{2}                      | apply changes from third last stash                       |
| git stash drop stash@{2}                       | delete third last stash                                   |
| git checkout commit 789798                     | moves to the older commit                                 |
| git checkout HEAD~2                            | Go 2 commits ago                                          |
| git sweitch -                                  | Go back to previous head location                         |
| git checkout HEAD dog.txt                      | changes in dog.txt will be rolled back to last commit     |
| git restore <file-name>                        | rollback changes to previous commit (head location)       |
| git restore --srouce HEAD~2 app.js             | rollback changes to third last commit                     |
| git restore --staged app.js                    | roll back stagged changes                                 |
| git reset 465423                               | force git to remove all commits after commit# 465423      |
| git reset --hard <commit hash>                 | changes are removed from local files as well.             |
| git revert <commit hash>                       | Undo changes to commit. Creates new commit                |
| git clone <url>                                | clones git repo in new local folder                       |
| git remote -v                                  | shows origin / source repo url                            |
| git remote add <name> <url>                    | Add a new remote for repo                                 |
| git push <remote> <branch>                     | push the code to github                                   |
| git push origin master                         | push local master branch to orign master branch           |
| git push origin pancake:waffle                 | push local pancake branch to waffle orgin branch          |
| git push -u oritin master                      | -u option connects to upstream                            |
| git checkout --track origin/puppies            | makes puppies branch avaialble locally                    |
| git switch puppies                             | makes puppies branch avaialble locally and switches to it |
| git fetch origin                               | pulls remote changes to local repo                        |
| git fetch origin master                        | pulls changes from origin/master branch to local repo     |
| git pull origin movies                         | pulls remote changes from movies branch workspace         |
| git pull                                       | pulls latest changes to current branch                    |
| git rebase master                              | make branch changes based on latest master                |
