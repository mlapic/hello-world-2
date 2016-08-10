

SSH:
git@github.com:mlapic/JsCookieNotes.git


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



echo "# JsCookieNotes" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:mlapic/JsCookieNotes.git
git push -u origin master



