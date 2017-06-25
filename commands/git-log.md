# Command: git log
The *git log* command show commit logs.


## Synopsis
```
git log [<options>] [<revision range>] [[\--] <path>…​]
```

$ git log --pretty=oneline --max-count=2
$ git log --pretty=oneline --since='5 minutes ago'
$ git log --pretty=oneline --until='5 minutes ago'
$ git log --pretty=oneline --author=<your name>
$ git log --pretty=oneline --all
$ git log --all --pretty=format:'%h %cd %s (%an)' --since='7 days ago'

## Conclusion
There are many more ways to show commit logs by making use
of the *git log* command. Not all the options options and permutations are documented
on this page, only the most used commands. For more information about the *git log*
command, the official documentation can be found at the following link:

* [GIT Documentation](https://git-scm.com/docs/git-log)

Alternatively you can type the following within a terminal:
```bash
$ man git-log
```
