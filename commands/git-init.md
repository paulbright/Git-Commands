# Command: git init
The *git init* command creates an empty Git repository, or reinitialize an existing
one.

## Synopsis
```
git init [-q | --quiet] [--bare] [--template=<template_directory>]
	  [--separate-git-dir <git dir>]
	  [--shared[=<permissions>]] [directory]
```

## Examples
There are a number of different ways that the *git init* command can be used. This
section contains a number of examples on how to use the command with different
options. This is definitely not a finite list of all the possible permutations,
but just a few of the better known ones.

### Example 1: Create a new empty repository
The *git init* command, on its own and in an empty directory, creates a new empty git repository.
It is safe to run the *git init* command in an existing repository. According to the official documentation
nothing will be overwritten, it is only to pick up newly added templates.

**Execute:**
```bash
$ git init
```

The output from the command shows the directory where the local git repository is created.

**Result:**
```bash
# /home/starlord/github/code2bits/learning-git/.git/
```

### Example 2: Create a new empty repository (Suppress Output)
The *git init -q* command will suppress all output except for errors and warnings, when creating
a new empty git repository.

**Execute:**
```bash
$ git init -q
```

Only errors and warnings will be printed to the console. All other output are suppressed.

**Result:**
```bash
.
```

## Conclusion
There are many more ways to create  or reinitialize a git repository by making use
of the *git init* command. Not all the options options and permutations are documented
on this page, only the most used commands. For more information about the *git init*
command, the official documentation can be found at the following link:

* [GIT Documentation](https://git-scm.com/docs/git-init)

Alternatively you can type the following within a terminal:
```bash
$ man git-init
```
