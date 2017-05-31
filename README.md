<img
    src="https://raw.githubusercontent.com/Code2Bits/Git-Commands/master/images/git.png"
    width="120"
    align="right"
/>
# Git Commands
This repository contains a list of GIT commands and explanations of how they work. The scenario
section describes how the combination of git commands can be used in different scenarios. The
reference section list several examples on how a single git command can be used in a number
of different ways.

## Overview
> This page came to life after I decided to learn git in a lot more details. I used numerous sources
like books, tutorials and online courses and made notes as I started to learn git in detail. The reason
for publishing yet another repository of git commands is because of the Feynman Technique. According to
Richard Feynman, you learn by teaching somebody else a topic in simple terms.

## Scenarios
**Git Installation**

The Git Installation and Setup scenarios are performed only once as part of the initial setup of
git on a specific computer.
* Installation
* [Initial Setup](scenarios/scenario_01_initial_setup.md)

**Create Git Repository**

There are two distinct ways in Git to create a local repository. The first is to create a new local
repository from scratch and the second is to download/clone an existing repository.
* Create Local Repository
* Link Remote Repository
* Clone Remote Repository

**Basic Workflow Usage**

The following scenarios describe how a combination of git commands can be used to perform a specific
task.
* Basic Git Commands (Add, Status, Commit, Log)
* Remote Repositories (Remote, Push, Pull)
* Housekeeping (Rename, Move, Delete)
* Branching
* History
* Ignoring Unwanted Files


## Reference
The git commands can be classified into different sections.

**Setup & Config**
* git
* git config
* git help

**Create & Get Repositories**
* [git init](commands/git-init.md)
* [git clone](commands/git-clone.md)

**Basic Snapshotting**
* [git add](commands/git-add.md)
* [git status](commands/git-status.md)
* [git diff](commands/git-diff.md)
* [git commit](commands/git-commit.md)
* [git reset](commands/git-reset.md)
* [git rm](commands/git-rm.md)
* [git mv](commands/git-mv.md)

**Branching & Merging**
* [git branch](commands/git-branch.md)
* [git checkout](commands/git-checkout.md)
* [git merge](commands/git-merge.md)
* [git mergetool](commands/git-mergetool.md)
* [git log](commands/git-log.md)
* [git stash](commands/git-stash.md)
* [git tag](commands/git-tag.md)

**Sharing & Updating Projects**
* [git fetch](commands/git-fetch.md)
* [git pull](commands/git-pull.md)
* [git push](commands/git-push.md)
* [git remote](commands/git-remote.md)


## Conclusion
This page contains the different scenarios in which git is used in a day to day fashion
as part of my work and also a reference to some of those commands. As part of the reference,
each command list the synopsis and also a number of examples on how to use the git command.

Not all the options options and permutations are documented on this page, only the most used commands.
For more information about the *git* commands, the official documentation can be found at the following link:

* [GIT Documentation](https://git-scm.com/docs)
