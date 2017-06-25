# Create Local Repository
D

## Create Local Repo on Linux
The following examples are created in my Ubuntu 17.04 server.

**EXECUTE:**
The pwd command is used to print the working directly and allows us to determine in which directly we are currently in.
```bash
$ pwd
# /home/starlord/learing-git
```

```bash
$ git init my_git_repo1
# Initialized empty Git repository in /home/starlord/learing-git/my_git_repo1/.git
```

```bash
$ cd my_git_repo1
```

```bash
$ ls -la
# total 12
# drwxrwxr-x 3 starlord starlord 4096 Jun 22 11:06 .
# drwxrwxr-x 3 starlord starlord 4096 Jun 22 11:06 ..
# drwxrwxr-x 7 starlord starlord 4096 Jun 22 11:06 .git
```

To get a better understanding of all the
```bash
$ tree -a
```
![Create Local Repository 001](https://raw.githubusercontent.com/Code2Bits/Git-Commands/master/images/scenario_create_local_repo_001.png)

## Conclusion
To view other ways of creating a local repository, visit the [Git Official Site](http://git-scm.com/)
