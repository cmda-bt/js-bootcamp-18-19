# ![Getting Started][banner-guide]

# Getting Started

## Table of Contents

*   [Prerequisites](#prerequisites)
*   [Installation](#installation)
*   [Communication](#communication)

## Prerequisites

### Text Editor
If you don’t have one yet, install a text editor. [Atom](https://atom.io), [Sublime](https://www.sublimetext.com) and [VSCode](https://code.visualstudio.com/) are good choices. 

> Be ware that lecturers may not be able to help you with problems in some editors.

### GitHub

If you haven’t already, [sign up for
GitHub](https://help.github.com/articles/signing-up-for-a-new-github-account/).

Take some time to set up your [GitHub profile](https://github.com/settings/profile).
Include your name, a profile picture, and a URL to your homepage.
You’re allowed to stay anonymous online for this course by omitting sensitive
information, but a good looking GitHub profile can help you get an internship
or job later.

## Installation

### CLI

*Windows:*  
If you’re on Windows, you should upgrade to Windows 10 (64 bit) and install the Windows Subsystem for Linux using [this guide](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/)
(takes about 15 minutes). Follow it until you see “Installation successful”. Now, open CMD (hit **Start**, type **cmd**, and press **Enter**), and type **bash** (and press **Enter**) to start Bash.

> Be ware that lecturers may not be able to help you with problems on Windows.

*MacOS:*  
Apple already has a terminal emulator by default to provide a command line interface. Just search for `terminal` in **spotlight** or find it in your applications folder.

### Git

*Windows:*  
If you installed the [Windows Subsystem for Linux](#subshell) just now, install
Git by running `apt-get install git` in Bash.

*MacOS:*  
Install Git from their website, by [downloading the latest release](https://git-scm.com).

Connect Git and GitHub together like so:

```sh
git config --global user.name "Mona Lisa"
git config --global user.email "mona@lisa.com"
```

Use the same email for Git as you used to sign up for GitHub. Open source is about people after all, don't forget to update your **bio information** and choose a nice **profile picture**!

## Setting up your repository

We would like you to have one 'repo' for the *JavaScript bootcamp*. This makes it easier for us to find your files and grade your assignments. You are going to hand in your exercises from this bootcamp trough GitHub. 

* Create a repository called `js-bootcamp`
* Add the `.js` files of the `template-repo` folder to your repository.
  * There are files for all the exercises, you will put your answers there.
  * There is also a `notes.md` where you can type notes after reading chapters of the book.

## Hand In


1. **Push your changes:**  
Hand in your progess in your repository on GitHub under your username.

1. **Create an issue:**  
Mark this as complete by opening an issue on our [GitHub issue tracker][issues]. Fill in the issue template with the correct information. 

## Communication

### Slack

Sign up for our Slack workspace on `cmda-tech.slack.com`.
Get invited by clicking on the invite link on our [class page on
Moodle][moodle].
Join the `js-bootcamp` channel in our workspace.

Get your Slack set up properly, and then send your lecturer a direct message
including your **real name**, **student number**, **class**, and **GitHub
username**.
We’ll use this info to link your GitHub and Slack to our administration files.

### Questions

If you have questions (in this order):

*   [Search StackOverflow][stackoverflow]
*   [Use a search engine like DuckDuckGo][duckduckgo]
*   [Ask questions on Slack][slack]
*   [Contact a lecturer][synopsis]

[moodle]: https://moodle.cmd.hva.nl/course/view.php?id=431
[examples]: examples
[stackoverflow]: https://stackoverflow.com
[duckduckgo]: https://duckduckgo.com
[synopsis]: #synopsis
[slack]: https://cmda-tech.slack.com/
[banner-guide]: https://cmda-bt.github.io/js-bootcamp-18-19/assets/banner-guide.svg
[issues]: https://github.com/cmda-bt/js-bootcamp-18-19/issues/new/choose