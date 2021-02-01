git init

git add .

git commit -m "add README.md"

git remote add origin git@github.com:JunjieYang1997/oose_hw2.git

git branch -M main

git push -u origin main

git add .

git commit -m "locally update README.md"

git push

git pull

git add .

git commit -m "solve merge conflicts"

git push

git branch new-feature

git checkout new-feature

git add .

git commit -m "try to commit the new feature"

git push

git push --set-upstream origin new-feature

git checkout main

git pull

git branch bug-1

git branch bug-2

git checkout bug-1

git add .

git commit -m "Working on bug-1"

git push --set-upstream origin bug-1

git checkout bug-2

git stash

git checkout bug-2

git add .

git commit -m "Fixed bug-2"

git push --set-upstream origin bug-2

git checkout bug-1

git stash apply stash@{0}

git add .

git commit -m "Fixed bug-1"

git checkout main

git push origin --all
