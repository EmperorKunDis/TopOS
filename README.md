# TopOS
Its just next funny project for my portfolio ;)
**Welcome to WSL (Windows Subsystem for Linux) Install Guide**

Table of Contents
=================

*   [System Requirements](#system-requirements)
*   [Software Installation](#software-installation)
*   [WSL Installation](#wsl-installation)
*   [Installing Additional Linux Distros](#installing-additional-linux-distros)

**System Requirements**
------------------------

Before installing WSL, ensure you meet the following system requirements:

*   **Windows Version**: Windows 10 (64-bit) or later
*   **CPU**: 1.4 GHz or faster CPU (Intel Core i3 or equivalent)
*   **RAM**: 4 GB RAM (8 GB or more recommended)

**Software Installation**
-------------------------

### Step 1: Install the Microsoft Store

WSL can be installed from the Windows Store.

### Step 2: Search for WSL in the Store

Search for "Windows Subsystem for Linux" in the Microsoft Store.

### Step 3: Download and Install WSL

Download and install WSL from the store.

**WSL Installation**
-------------------

### Step 1: Open PowerShell as Administrator

Open a new PowerShell window with administrator privileges.

### Step 2: Enable WSL

Run the command `Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-for-Linux`

### Step 3: Install WSL

Run the command `wsl --install`

**Installing Additional Linux Distros**
--------------------------------------

You can install additional Linux distros from the Windows Store or using the command line.

### Method 1: Installing from the Store

Search for your desired Linux distro in the Microsoft Store, and follow the installation instructions.

### Method 2: Installing using the Command Line

Run the command `wsl --install -d <distroname>` to install a specific Linux distro.

**Running Windows Commands inside Linux**
------------------------------------------

You can run Windows commands inside Linux by prefixing them with "wsl" followed by the command.

Example:

*   Run `ipconfig` by typing `wsl ipconfig`
*   Open files with Notepad using `notepad.exe <filename>`
*   Open the current directory in Windows Explorer using `explorer.exe .`

**Filtering Output using Linux Commands**
-----------------------------------------

You can filter output from Windows commands using Linux commands.

Example:

*   Run `ipconfig` and pipe it to `grep 10.` by typing `wsl ipconfig | grep 10.`
*   Use the `cat` command to view files: `wsl cat <filename>`

This comprehensive README.md file covers all aspects of WSL installation, additional Linux distro installation,
running Windows commands inside Linux, and filtering output using Linux commands.

Note that this is a generated version based on your provided text. Be sure to review and edit it as necessary to
suit your specific needs.
