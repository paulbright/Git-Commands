# Create Local Repository
This scenario describe how to create a new local git repository from scratch. The scenario starts by using basic bash commands to determine the current directory structure and then how to create a new local git repository. The scenario further describe how to list the files and directories within the local git repository.

## Git Command
The following set of git commands is used to create a local git repository.
**EXECUTE:**

```bash
$ git init my_git_repo1
```

## Scenario: Create a Local Repository
The following examples are created in my Ubuntu 17.04 server.

**EXECUTE:**

The pwd command is used to print the working directly and allows us to determine in which directly we are currently in.
```bash
$ pwd
# /home/starlord/learing-git
```

**EXECUTE:**


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
