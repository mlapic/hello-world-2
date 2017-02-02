
git@github.com:userName/repo.git
https://github.com/userName/repo.git

GLOBAL CONFIG
=============

git config --global user.email "you@example.com"
git config --global user.name "Your Name"

ADD SSH KEY
===========

cd ~/.ssh
ssh-keygen
cat id_rsa.pub
add key to github.com/settings/ssh

INIT, COMMIT & PUSH TO REPOSITORY
=================================

touch README.md
git init
git add README.md

git commit -m "first commit"
git commit -a -m "first commit" // commit all changed files

git remote add origin git@github.com:userName/repo.git
git remote add origin https://github.com/userName/repo.git
git remote -v
git push -u origin master
