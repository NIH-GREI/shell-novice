---
title: Setup
---

## Download files

You need to download some files to follow this lesson.

1. Download [shell-lesson-data.zip][zip-file] and move the file to your Desktop.
2. Unzip/extract the file.
  **Let your instructor know if you need help with this step**.
  You should end up with a new folder called **`shell-lesson-data`** on your Desktop.

::::::::::::::::::::::::::::::::::::::::: callout

## Alternative Data Sources: Generalist Repositories

In addition to platforms like GitHub, researchers often use generalist repositories to store, share, and access datasets. These repositories are designed to preserve research outputs (like data, code, and workflows) in a citable, discoverable, and standardized way. They are particularly valuable for ensuring long-term accessibility and reproducibility of research.

### NIH-GREI Recommended Repositories
Under the NIH Generalist Repository Ecosystem Initiative ([GREI](https://datascience.nih.gov/data-ecosystem/generalist-repository-ecosystem-initiative)), several generalist repositories are recognized for hosting biomedical and scientific data. These include:

* Zenodo ([zenodo.org](https://about.zenodo.org/)): An open repository for EU-funded research but widely used globally.
* Dryad ([datadryad.org](https://datadryad.org/about)): A nonprofit repository focused on publishing and preserving research data.

These repositories assign DOIs (Digital Object Identifiers) to datasets, making them easier to cite and track.

### Why Use Generalist Repositories?

* Long-term preservation: Ensures data remains accessible beyond project lifetimes.
* Compliance: Meets funder (e.g., NIH) and publisher requirements for data sharing.
* Interoperability: Standardized metadata makes data reusable across disciplines.

For this lesson, we’ve provided the data via GitHub for simplicity, but we encourage you to explore these repositories for your own work.

::::::::::::::::::::::::::::::::::::::::::::::::::

## Install software

If you do not already have the shell software installed, you will need to
[download and install][install_shell] it.

## Open a new shell

After installing the software

3. Open a terminal.
  If you're not sure how to open a terminal on your operating system, see the instructions below.
4. In the terminal type `cd` then press the <kbd>Return</kbd> key.
  This step will make sure you start with your home folder as your working directory.

In the lesson, you will find out how to access the data files in this folder.

:::::::::::::::::::::::::::::::::::::::::  callout

## Where to type commands: How to open a new shell

The shell is a program that enables us to send commands to the computer and receive output.
It is also referred to as the terminal or command line.

Some computers include a default Unix Shell program.
The steps below describe some methods for identifying and opening
a Unix Shell program if you already have one installed.
There are also options for identifying and downloading a Unix Shell program,
a Linux/UNIX emulator, or a program to access a Unix Shell on a server.

If none of the options below address your circumstances,
try an online search for: Unix shell [your computer model] [your operating system].


::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::: solution

### Windows {#windows}

Computers with Windows operating systems do not automatically have a Unix Shell program
installed.
In this lesson, we encourage you to use an emulator included in [Git for Windows][install_shell],
which gives you access to both Bash shell commands and Git.

Once installed, you can open a terminal by running the program Git Bash from the Windows start
menu.

**For advanced users:**

As an alternative to Git for Windows you may wish to [Install the Windows Subsystem for Linux][wsl]
which gives access to a Bash shell command-line tool in Windows 10 and above.

Please note that commands in the Windows Subsystem for Linux (WSL) may differ slightly
from those shown in the lesson or presented in the workshop.

::::::::::::

:::::::::::: solution

### MacOS {#macos}

For a Mac computer running macOS Mojave or earlier releases, the default Unix Shell is Bash.
For a Mac computer running macOS Catalina or later releases, the default Unix Shell is Zsh.
Your default shell is available via the Terminal program within your Utilities folder.

To open Terminal, try one or both of the following:

- In Finder, select the Go menu, then select Utilities.
  Locate Terminal in the Utilities folder and open it.
- Use the Mac 'Spotlight' computer search function.
  Search for: `Terminal` and press <kbd>Return</kbd>.

To check if your machine is set up to use something other than Bash,
type `echo $SHELL` in your terminal window.

If your machine is set up to use something other than Bash,
you can run it by opening a terminal and typing `bash`.

[How to Use Terminal on a Mac][mac-terminal]

::::::::::::

:::::::::::: solution

### Linux {#linux}

The default Unix Shell for Linux operating systems is usually Bash.
On most versions of Linux, it is accessible by running the
[Gnome Terminal][gnome-terminal] or [KDE Konsole][kde-konsole] or [xterm],
which can be found via the applications menu or the search bar.
If your machine is set up to use something other than Bash,
you can run it by opening a terminal and typing `bash`.

::::::::::::

[zip-file]: data/shell-lesson-data.zip
[install_shell]: https://carpentries.github.io/workshop-template/install_instructions/#shell
[wsl]: https://learn.microsoft.com/en-us/windows/wsl/install
[mac-terminal]: https://www.macworld.co.uk/feature/mac-software/how-use-terminal-on-mac-3608274/
[gnome-terminal]: https://help.gnome.org/users/gnome-terminal/stable/
[kde-konsole]: https://konsole.kde.org/
[xterm]: https://en.wikipedia.org/wiki/Xterm



