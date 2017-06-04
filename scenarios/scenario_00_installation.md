# Git Installation
Depending on the operating system, there are numerous ways to install git. This page provides information on how to install git on Linux, Windows and Mac OS X.

## Install Git
This page contains some of the commands to install git, and also links to pages containing detailed explanations on how to install git.

* [Installing Git on Linux](#installing-git-on-linux)
* [Installing Git on Windows](#installing-git-on-windows)
* [Installing Git on Mac](#installing-git-on-mac)

### Installing Git on Linux
Installing git on a linux distribution is made easy with the help of the package manager of the linux distribution. Each linux distribution has a different package manager, but the concept is the same.

**Debian-based Distributions (Ubuntu)**

APT (Advanced Package Tool) is an advanced interface to the Debian packaging system. The apt-get program forms part of the APT tool. The apt-get program retrieves and install packages from multiple sources, and is used to install the git.

The following commands should be typed within a terminal on a Debian-based operating system like Ubuntu to install git.

```bash
$ sudo apt-get update
$ sudo apt-get upgrade
$ sudo apt-get install git
```

**RedHat-based Distributions**

YUM (Yellowdog Updater Modified) is an open source command-line package management tool for RPM (RedHat Package Manager) based Linux systems. YUM is used to query and fetch packages from repositories, also to install and uninstall these packages. YUM can be used to install git on RPM-based linux distributions.

The following commands should be typed within a terminal on a RPM-based operating system like Centos or RHEL to install git.

```bash
$ sudo yum upgrade
$ sudo yum install git
```

### Installing Git on Windows
To install git on windows, follow the instructions below:

1. Click [here](http://git-for-windows.github.io) to download and install Git. Choose between the 32-bit or 64-bit options.
2. After the download has completed successfully, launch the installation files. Follow the Git Setup wizzard screens by selecting the applicable options and complete the installation.

### Installing Git on Mac
There are several ways to install Git on a Mac. You might already have git installed as part of XCode or Command Line Tools, so first check if it is not already installed.

Open a terminal and enter the following command.

```bash
 $ git --version
 ```
Depending on the output of the command, you can determine if it is installed or not. If the output is the version of git, then git is installed, anything else and you need to install git.

**Git for Mac Installer**

1. Download the Git for Mac Installer from [here](https://sourceforge.net/projects/git-osx-installer/files/).
2. After the download has completed successfully, launch the installation files. Follow the Git Setup wizzard screens by selecting the applicable options and complete the installation.

**Install Git with Homebrew**

If you already have Homebrew installed on your MAC, you can run the following command within a terminal.

```bash
$ brew install git
```

**Other**

Click [here](http://git-scm.com/download/mac) for more information on how to install git on a MAC.


## Validate Installation
To validate that the git installation was successful, run the following on the command line. Depending on the version of git that was installed, the output from the git version command will be different.

```bash
$ git --version
# git version 2.11.0
```

## Conclusion
To view other ways of installing git visit one of the following sites:
* [Git official site](http://git-scm.com/book/en/Getting-Started-Installing-Git)
* [Git Installation (Atlassion)](https://www.atlassian.com/git/tutorials/install-git)
