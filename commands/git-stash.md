# Command: git stash
The *git stash* command stash the changes in a dirty working directory away.


## Synopsis
```
git stash list [<options>]
git stash show [<stash>]
git stash drop [-q|--quiet] [<stash>]
git stash ( pop | apply ) [--index] [-q|--quiet] [<stash>]
git stash branch <branchname> [<stash>]
git stash save [-p|--patch] [-k|--[no-]keep-index] [-q|--quiet]
	     [-u|--include-untracked] [-a|--all] [<message>]
git stash [push [-p|--patch] [-k|--[no-]keep-index] [-q|--quiet]
	     [-u|--include-untracked] [-a|--all] [-m|--message <message>]]
	     [--] [<pathspec>…​]]
git stash clear
git stash create [<message>]
git stash store [-m|--message <message>] [-q|--quiet] <commit>
```

## Conclusion
There are many more ways to stash the changes in a dirty working directory away by making use
of the *git stash* command. Not all the options options and permutations are documented
on this page, only the most used commands. For more information about the *git stash*
command, the official documentation can be found at the following link:

* [GIT Documentation](https://git-scm.com/docs/git-stash)

Alternatively you can type the following within a terminal:
```bash
$ man git-stash
```
