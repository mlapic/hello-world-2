## A Little Help File

### Global Config

```
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

### Add SSH Key

```
cd ~/.ssh
ssh-keygen
cat id_rsa.pub
```

Add key to github.com/settings/ssh.

### Clone GIT Repository

```
git clone git@github.com:userName/repoName.git
git clone https://github.com/userName/repoName.git
```

### Init, Commit, Push & Pull Examples

```
touch README.md
git init
git add README.md

git commit -m "first commit"
git commit -a -m "first commit" // commit all changed files

git remote add origin https://github.com/userName/repoName.git
git remote -v
git remote set-url origin https://github.com/userName/repoName.git
git push -u origin master

git pull origin master
```
