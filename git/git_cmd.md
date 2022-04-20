
GitHub Account: [nandinisingasani](https://github.com/nandinisingasani/)

# Commands

Created **public** repository https://github.com/nandinisingasani/dev_learn 

Cloned repository to local
```
cd ~/Desktop/nandini/gitRepos/

ls -l

git clone https://github.com/nandinisingasani/dev_learn.git

ls -l
```

```
cd dev_learn

# To see hidden files
ls -la

# Created git folder
mkdir git
cd git

# Created file
touch git_cmd.md

ls -l

vi git_cmd.md
```

```
git status

cd ..

git status

git add git/

git status

git diff

git commit -m "added git/git_cmd.md"

git log

git status

git push origin main
```

Verify https://github.com/nandinisingasani/dev_learn.git


## ssh type clone

Added below public key under https://github.com/settings/keys
```
cat ~/.ssh/id_rsa.pub 
```

```
git clone git@github.com:nandinisingasani/dev_learn.git
```
