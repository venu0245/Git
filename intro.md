### GIT INTRODUCTION:

* git is used for sending folders in files in local repository (local system) to remote repository (github account)
* create a repository in github account

* git init=> initizating the local repository
* git add -A=> everything in a file can be added into a local repository
* git status=>check details
* git log=>check all details commit id's,unigue id,user name and email id 
* git config --global user.name<venu>/git config --global user.email <venu@gmail.com>=>know the the system levels
* git commit -m "first"=>commited everything data in file 
* git remote add origin https://github.com/venu0245/Git.git
* git push=>sending files in local repository to remote repository 
* git clone https://github.com/venu0245/Git.git =>copying folders/files in remote repository to  local repository
* git pull=>everything copy file to local repository
* git mv=> old_name to new_name for renaming the files
* git reset --hard=>when we delete a file or folder we execute a `git status`shows again we use `git reset --hard`

*  when we push the file local repository to remote repository we get a error we use `git pull` we enter the name of the repository code url it's shows the url https://github.com/venu0245/Git.git either we can enter the git pull https://github.com/venu0245/Git.git

* git log:take latest commit id 

* git cat-file -p -s -t <commit_id>

#### Git tag:
* Git tag is nothing but label for branches
* git tag rel_1.0
* git tag
* git tags are stored in `.git folder=> ref=>tags`
#### Git stash:
* Git stash:when changes are applied in a file we use 
*`git stash`
* changes will be gone and if get changes back again  we use  add and commit the changes into file
* `git stash list`
* `git stash apply`
#### Git cherry-pick:
* ```
  git status
  git log
  git cherry-pick aaccd51a6751dd92d2455eee31ff9e49d515a44d
  ```
#### Git rebase

* ```
  git checkout -b int
  git checkout -b sprint
  git rebase int
  ```
* in int branch have a file and modified that file can be add and commit 
* change the branch sprint whatever changes in the file in int branch that changes come back into sprint branch we use `git rebase int`  