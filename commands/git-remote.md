# Command: git remote
The *git remote* command manage set of tracked repositories.


## Synopsis
```
git remote [-v | --verbose]
git remote add [-t <branch>] [-m <master>] [-f] [--[no-]tags] [--mirror=<fetch|push>] <name> <url>
git remote rename <old> <new>
git remote remove <name>
git remote set-head <name> (-a | --auto | -d | --delete | <branch>)
git remote set-branches [--add] <name> <branch>…​
git remote get-url [--push] [--all] <name>
git remote set-url [--push] <name> <newurl> [<oldurl>]
git remote set-url --add [--push] <name> <newurl>
git remote set-url --delete [--push] <name> <url>
git remote [-v | --verbose] show [-n] <name>…​
git remote prune [-n | --dry-run] <name>…​
git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)…​]
```

## Conclusion
There are many more ways to manage a set of tracked repositories by making use
of the *git remote* command. Not all the options options and permutations are documented
on this page, only the most used commands. For more information about the *git temote*
command, the official documentation can be found at the following link:

* [GIT Documentation](https://git-scm.com/docs/git-temote)

Alternatively you can type the following within a terminal:
```bash
$ man git-temote
```
