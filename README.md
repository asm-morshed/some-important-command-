Some userful command 
===

Updating gh-pages from master
---
##First of all update your master branch using the following command
git add .
git status
git commit -m 'something'
git push origin master

##Then write this command to update your gh-pages branch
git checkout gh-pages  // changing branch
git rebase master
git push origin gh-pages
git checkout master
