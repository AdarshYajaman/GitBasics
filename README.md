# GitBasics

git config --global user.name "adarsh yajaman"

git config --global user.email "rulz.adarsh@gmail.com"

git config user.name

git config user.email

git init  /*Initialize 

git status /*check status

git add $fileName$ /*stage files

git rm --cached $fileName$ /* UnStage files

or

git restore --staged $filename$ /* UnStage files

git log /* list of commits

git commit -m "commit message here" 

git branch /* list of branches

git branch $branchName$ /* create a branch

git checkout $branchName$ /* Switch to a new branch

git diff $fileName$ /* check file diff

git merge $sourceBranchName$ /*This merges source branch to destination. The destination branch has to be checkedout first before making this change

git tag -a V1.0.0 -m "Created Version 1.0.0"


Bit bucket password - ATBBPT64PLcUmDXWtVT7zayRDfepB32040F2

git push origin master /* Push local changed to remote repo

git pull /* Pull changes from remote repo

ssh-keygen

git remote add origin <remote repo URL>

/Reading needed/
git reset soft, git reset mixed, and git reset hard.  

vim .gitconfig
