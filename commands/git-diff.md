# Command: git diff
The *git diff* command shows changes between:
* the working tree and the index or a tree,
* changes between the index and a tree,
* changes between two trees,
* changes between two blob objects, or
* changes between two files on disk.


## Synopsis
```
git diff [options] [<commit>] [--] [<path>…​]
git diff [options] --cached [<commit>] [--] [<path>…​]
git diff [options] <commit> <commit> [--] [<path>…​]
git diff [options] <blob> <blob>
git diff [options] [--no-index] [--] <path> <path>
```

## Conclusion
There are many more ways to show the changes between different entities within the
git repository. Not all the options options and permutations are documented
on this page, only the most used commands. For more information about the *git diff*
command, the official documentation can be found at the following link:

* [GIT Documentation](https://git-scm.com/docs/git-diff)

Alternatively you can type the following within a terminal:
```bash
$ man git-diff
```
