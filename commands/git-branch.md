# Command: git branch
The *git branch* command lists, creates or deletes branches.

## Synopsis
```
git branch [--color[=<when>] | --no-color] [-r | -a]
	[--list] [-v [--abbrev=<length> | --no-abbrev]]
	[--column[=<options>] | --no-column] [--sort=<key>]
	[(--merged | --no-merged) [<commit>]]
	[--contains [<commit]] [--no-contains [<commit>]]
	[--points-at <object>] [--format=<format>] [<pattern>…​]
git branch [--set-upstream | --track | --no-track] [-l] [-f] <branchname> [<start-point>]
git branch (--set-upstream-to=<upstream> | -u <upstream>) [<branchname>]
git branch --unset-upstream [<branchname>]
git branch (-m | -M) [<oldbranch>] <newbranch>
git branch (-d | -D) [-r] <branchname>…​
git branch --edit-description [<branchname>]
```

## Conclusion
There are many more ways to list, create or delete branches in the git repository by making use
of the *git branch* command. Not all the options options and permutations are documented
on this page, only the most used commands. For more information about the *git branch*
command, the official documentation can be found at the following link:

* [GIT Documentation](https://git-scm.com/docs/git-branch)

Alternatively you can type the following within a terminal:
```bash
$ man git-branch
```
