# hello-world
git fetch origin
git checkout -b master origin/master
git merge readme-edits

git checkout readme-edits
git merge --no-ff master
git push origin readme-edits
