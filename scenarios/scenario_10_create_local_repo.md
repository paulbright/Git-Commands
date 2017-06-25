# Create Local Repository
This scenario describes how to create a new local git repository from scratch. The scenario starts by using basic bash commands to determine the current directory structure and then the creation of a new local git repository. The scenario further describes how to list the files and directories within the local git repository.

## Git Command(s)
The following git command is used to create a local git repository.

***EXECUTE:***

```bash
$ git init [repo name]
```

## Scenario: Create a Local Repository
The following scenario is created in my Ubuntu 17.04 server.

### Step1: Determine the working directory
The first step is to determine working directory to ensure the local git repository is created in the correct place. The pwd command is used to print the working directly and allows us to determine in which directly we are currently in.

***EXECUTE:***

```bash
$ pwd
# /home/starlord/learing-git
```

### Step 2: Create Local Repository
The second step is to create the local git repository with an appropriate name. The name will be used to create a directory within the current working directory. The new local git repository will also have a hidden _.git_ directory which contains all the hooks, config and branches that makes up a git repository.

***EXECUTE:***

```bash
$ git init my_git_repo1
# Initialized empty Git repository in /home/starlord/learing-git/my_git_repo1/.git
```

### Step 3: View the Local Repository

Go to the new directory call _my_gitrepo1_ and list all the contents of the directory. You will see that there is no files in the newly created git repository except for the hidden _git_ directory.

***EXECUTE:***

```bash
$ cd my_git_repo1
$ ls -la
# total 12
# drwxrwxr-x 3 starlord starlord 4096 Jun 22 11:06 .
# drwxrwxr-x 3 starlord starlord 4096 Jun 22 11:06 ..
# drwxrwxr-x 7 starlord starlord 4096 Jun 22 11:06 .git
```

### Step 4: View the Local Repository Tree Structure
To get a better understanding of all the content within the local repository, you can execute the _tree_ command within the directory and it will print all the contents of the local repository out in a tree structure out on the screen. Please note that the _tree_ command is not a standard bash command and needs to be installed by your package manager of your operating system.

***EXECUTE:***

```bash
$ tree -a
```
![Create Local Repository 001](https://raw.githubusercontent.com/Code2Bits/Git-Commands/master/images/scenario_create_local_repo_001.png)

## Conclusion
To view other ways of creating a local repository, visit the [Git Official Site](http://git-scm.com/)
