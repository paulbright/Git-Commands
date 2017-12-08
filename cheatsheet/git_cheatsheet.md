# GIT Cheatsheet


### Initial setup
```bash
$ git config --global user.name "Star-Lord"
$ git config --global user.email "star.lord@knowhere.com"
$ git config --global core.autocrlf input
$ git config --global core.safecrlf true
```

### Git Configurations
```bash
$ git config user.name
$ git config user.email
$ git config --global --list
```
### Git Colors
```bash
$ git config --global color.ui "auto"
```
### Create Git repository
```bash
$ git init
$ git init [repo name]
$ git clone [repo url]
```

### Inspect Repository (Status & Difference)
```bash
$ git status

$ git diff
$ git diff --cached
$ git diff HEAD
$ git diff commit1 commit2

$ git blame [filename]
$ git show [commit]:[filename]

$ git log
$ git log --pretty=oneline
$ git log -p [filename/directory]
```
### Add Files & Commit
```bash
$ git add .
$ git add [filename]

$ git commit -m "[My Message]"
$ git commit -am "[My Message]"

$ git reset [filename]
$ git reset --hard
```
### Remove Files
```bash
$ git rm [filename]
```
### Remote Repository
```bash
$ git remote add origin [repo url]
$ git remote -v

$ git fetch
$ git pull
$ git pull --rebase
$ git push [origin] [master]
```
### Branches
```bash
$ git branch
$ git branch -av
$ git checkout [branch_name]
$ git branch [branch_name]
$ git branch -d [branch_name]

-- Merge Branch A into Branch B
$ git checkout [Branch B]
$ git merge [Branch A]

$ git tag [tag_name]
```
### Help
```bash
$ git version

$ git help
$ git help [command]
$ git [command] --help
```
