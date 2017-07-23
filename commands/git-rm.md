# Command: git rm
The *git rm* command removes files from the working tree and from the index.

## Synopsis
```
git rm [-f | --force] [-n] [-r] [--cached] [--ignore-unmatch] [--quiet] [--] <file>…
```

## Examples
#### Example 1:  Remove a file from the Index and from the Working Directory
This command removes a filename called filename.txt from git index and from the working directory. 
```
$ git rm filename.txt
```

#### Example 2:  Remove a directory from the Index and from the Working Directory
```
$ git rm -r directory_name
```

#### Example 4:  Remove a file from the Index, but not from the working directory
```
$ git rm --cached filename.txt
```

#### Example 4:  Remove a directory from the Index but not from the working directory
```
$ git rm --cached -r directory_name
```

## Conclusion
There are many more ways to remove files from the working tree and from the index by making use
of the *git rm* command. Not all the options options and permutations are documented
on this page, only the most used commands. For more information about the *git rm*
command, the official documentation can be found at the following link:

* [GIT Documentation](https://git-scm.com/docs/git-rm)

Alternatively you can type the following within a terminal:
```bash
$ man git-rm
```
