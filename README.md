# Git Hidden Folder

There is a hidden folder called `.git` which tells you that our project is a git repo.

If we wanted to create a git repo in a new project we' create the folder and the initalize that repo using `git init`

```
mkdir /workspaces/tmp/new-project
cd /workspaces/tmp/new-project
git init
touch Readme.md
code Readme.md
git status
git add Readme.md
# makes changes to readme.md
git commit -m "add readme file"
```


## Cloning

We can clone three ways: HTTPS, SSH, Github CLI

Since we are using GitHub Codespaecs we'll a create temporary directory in our workspace

```sh
mkdir /workspace/tmp
cd /workspace/tmp
```


### HTTPS
