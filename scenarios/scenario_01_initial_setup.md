# Git Initial Setup
The git initial setup is performed only once after the installation is successful. This page will focus on the minimum set of properties that should be configured before you can use git.

## Git Command(s)
The following git commands are used to perform the initial setup of git by setting the user name and email properties.

***EXECUTE:***
```bash
# ---------- Set Properties ----------
$ git config --global user.name "Star-Lord"
$ git config --global user.email "star.lord@knowhere.com"
$ git config --global core.autocrlf input
$ git config --global core.safecrlf true
```
```bash
# ----------  List Properties ----------
$ git config user.name
$ git config user.email
$ git config --global --list
```

## Scenario: Initial Setup (Username, Email & Line Ending)

### Step 1: Setup Your Identity
Git requires you to setup your user name and email address before you can use git. The reason for this is that git uses this information as part of the commit function. To set your user name and email address, run the following commands within the terminal.

***EXECUTE:***
```bash
$ git config --global user.name "Star-Lord"
$ git config --global user.email "star.lord@knowhere.com"
```

### Step 2: Print Identity Properties
To ensure that your identity has been set correctly, you can execute the command below within a terminal. This command prints the user name, that has been set in the Global config file, out to the console.

***EXECUTE:***
```bash
$ git config user.name
# Star-Lord
```

This command prints the user email address, that has been set in the Global config file, out to the console.

***EXECUTE:***
```bash
$ git config user.email
# star.lord@knowhere.com
```

### Step 3: Setup Line Ending Properties
Windows uses both a carriage-return character and a linefeed character for newlines in its files, whereas Mac and Linux systems use only the linefeed character. These properties ensure that will not run into line-ending issues when multiple people are working on both Windows, Unix and Mac.

Unix/MAC Users:

***EXECUTE:***
```bash
$ git config --global core.autocrlf input
$ git config --global core.safecrlf true
```

Windows Users:

***EXECUTE:***
```bash
$ git config --global core.autocrlf true
$ git config --global core.safecrlf true
```

### Step 4: Print All Properties
Alternatively, the following command can be used to list all the properties that has been set in the global configuration file.

***EXECUTE:***
```bash
$ git config --global --list
# user.name=Star Lord
# user.email=star.lord@knowhere.com
```

## Conclusion
The intent of this page is to focus on the initial setup required by git before you can start using it. The minimum settings required for Git to work are the user name and email. For more information about *git* and the other properties you can set, please look at the official documentation that can be found at the following link:

* [GIT Documentation](https://git-scm.com/docs/)
