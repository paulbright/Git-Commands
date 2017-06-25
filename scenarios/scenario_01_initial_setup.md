# Git Initial Setup
The git initial setup is performed only once after the installation is successful. This page will focus on the minimum set of properties that should be configured before you can use git.

## Git Command(s)
The following git commands are used to perform the initial setup of git by setting the user name and email properties.

***EXECUTE:***
```bash
$ git config --global user.name "Star-Lord"
$ git config --global user.email "star.lord@knowhere.com"
```

## Scenario: Initial Setup (Username & Email)

**Your Identity**

Git requires you to setup your user name and email address before you can use git. The reason for this is that git uses this information as part of the commit function. To set your user name and email address, run the following commands within the terminal.

```bash
$ git config --global user.name "Star-Lord"
$ git config --global user.email "star.lord@knowhere.com"
```

To ensure that your identity has been set correctly, you can execute the command below within a terminal. This command prints the user name, that has been set in the Global config file, out to the console.

```bash
$ git config user.name
# Star-Lord
```

This command prints the user email address, that has been set in the Global config file, out to the console.

```bash
$ git config user.email
# star.lord@knowhere.com
```

Alternatively, the following command can be used to list all the properties that has been set in the global configuration file.

```bash
$ git config --global --list
# user.name=Star Lord
# user.email=star.lord@knowhere.com
```

## Conclusion
The intent of this page is to focus on the initial setup required by git before you can start using it. The minimum settings required for Git to work are the user name and email. For more information about *git* and the other properties you can set, please look at the official documentation that can be found at the following link:

* [GIT Documentation](https://git-scm.com/docs/)
