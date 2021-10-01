## Add existing local repository to Git

git init

git add .

git commit -m "First commit"

git remote add origin (remote repositpory URL)

git remote -v

git push -u origin master

## Git Pull, Commit, Push

git pull origin master

git commit -m "(Commit Message)"

git push origin master

## Git Pull to overwrite local changes

git fetch --all

git reset --hard origin/master

## Create new branch

git branch (new branch) (base branch - default to current HEAD)
