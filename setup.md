---
layout: info_page
title: Installation instructions
---

## Download files

You need to download some files to follow this lesson.

1. Download [shell-lesson-data.zip][zip-file] and move the file to your Desktop.
2. Unzip/extract the file.
   **Let your instructor know if you need help with this step**.
   You should end up with a new folder called **`shell-lesson-data`** on your Desktop.

## Install software

If you do not already have the shell software installed, you will need to download and install it.

### Windows

Computers with Windows operating systems do not automatically have a Unix Shell program
installed.

In this lesson, we encourage you to use an emulator included in [Git for Windows][install_shell],
which gives you access to both Bash shell commands and Git.
Once installed, you can open a terminal by running the program Git Bash from the Windows start
menu.

**For advanced users**, as an alternative to Git for Windows, you may wish to [Install the Windows Subsystem for Linux][wsl] which gives access to a Bash shell command-line tool in Windows 10.
Please note that commands in the Windows Subsystem for Linux (WSL) may differ slightly from those shown in the lesson or presented in the workshop.

### MacOS

For a Mac computer running macOS Mojave or earlier releases, the default Unix Shell is Bash.
For a Mac computer running macOS Catalina or later releases, the default Unix Shell is Zsh.
Your default shell is available via the Terminal program within your Utilities folder.

To open Terminal, try one or both of the following:

* In Finder, select the Go menu, then select Utilities.
  Locate Terminal in the Utilities folder and open it.
* Use the Mac 'Spotlight' computer search function.
  Search for: `Terminal` and press <kbd>Return</kbd>.

To check if your machine is set up to use something other than Bash,
type `echo $SHELL` in your terminal window.

If your machine is set up to use something other than Bash,
you can run it by opening a terminal and typing `bash`.

Here are instruction on [how to Use Terminal on a Mac][mac-terminal]

### Linux

The default Unix Shell for Linux operating systems is usually Bash.
On most versions of Linux, it is accessible by running the
[Gnome Terminal][gnome-terminal] or [KDE Konsole][kde-konsole] or [xterm][xterm],
which can be found via the applications menu or the search bar.
If your machine is set up to use something other than Bash,
you can run it by opening a terminal and typing `bash`.

## Open a new shell

After installing the software
3. Open a terminal.
   If you're not sure how to open a terminal on your operating system, see the instructions under
   **Install Software** above.
4. In the terminal type `cd` then press the <kbd>Return</kbd> key.
   This step will make sure you start with your home folder as your working directory.

In the lesson, you will find out how to access the data files in this folder.

[zip-file]: {{ page.root }}/data/shell-lesson-data.zip
[wsl]: https://docs.microsoft.com/en-us/windows/wsl/install-win10
[mac-terminal]: http://www.macworld.co.uk/feature/mac-software/how-use-terminal-on-mac-3608274/
[gnome-terminal]: https://help.gnome.org/users/gnome-terminal/stable/
[kde-konsole]: https://konsole.kde.org/
[xterm]: https://en.wikipedia.org/wiki/Xterm
[install_shell]: https://carpentries.github.io/workshop-template/#shell
