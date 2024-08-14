
# Starter Guide to Linux

## Overview

- [Introduction](#introduction)
- [Why Linux?](#why-linux)
- [Installation](#installation)
- [The Terminal](#the-terminal)
- [The File System](#the-file-system)
- [Resources](#useful-resources)
- [Package Managers](#package-managers)

## Introduction

Linux is technically a kernel, which is the core part of an operating system.
However, it is often referred to as an operating system because it is commonly
used with a collection of software tools and libraries that make up a complete
OS. It is known for its stability, security, and flexibility. It is widely used
by programmers and system administrators due to its ability to be customized
and modified for various purposes.

## Why Linux?

**Open Source:** Linux is an open-source kernel, meaning its source code is
available to everyone and can be freely modified and distributed. This allows
programmers and IT professionals to customize and optimize their systems to
meet their specific needs.

**Open Source:** Linux is an open-source operating system, meaning its source
code is available to everyone and can be freely modified and distributed. This
allows programmers and IT professionals to customize and optimize their systems
to meet their specific needs.

**Stability and Security:** Linux is known for its stability and security,
being less vulnerable to malware and hacking compared to Windows and macOS.
This is partly due to the strict access control and separation of user
privileges built into Linux.

**Scalable:** Linux can run on everything from small devices to large servers
and supercomputers. This makes it ideal for both small and large projects, and
it can easily be scaled up or down as needed.

**Freedom to Choose:** With Linux, you have the freedom to choose and
[customize](https://www.reddit.com/r/unixporn/) your software, including the
operating system, [desktop
environment](https://wiki.gentoo.org/wiki/Desktop_environment), applications,
and tools. This allows programmers and IT professionals to work with the tools
they prefer and tailor their workflows to their needs.

**Community and Support:** Linux has a large and active
[community](https://www.reddit.com/r/linux/) of developers and users who offer
free support, help, and guidance. This can be very useful for programmers and
IT professionals who encounter technical challenges or need help choosing the
best tools for their work.

## Installation

To install Linux, you first need to download a Linux distribution. Some of the
most popular [distributions](https://distrowatch.com/) include `Ubuntu`,
`Debian`, `Fedora`, `Arch`, `Gentoo`, and `CentOS`.

---

Once you have downloaded the ISO file, you can "flash" it onto a USB drive
using tools like [Rufus](https://rufus.ie/en/) or [Balena
Etcher](https://www.balena.io/etcher). You may need to disable [fast
startup](https://help.uaudio.com/hc/en-us/articles/213195423-How-To-Disable-Fast-Startup-in-Windows-10).

After booting from the USB drive, you will typically be guided through the
installation process. It is VERY important to choose the correct partitions for
installing Linux, so make sure to back up your data before proceeding.

> Backup, backup, backup!

## Basic Linux Features

### The Terminal

The terminal is one of the most important features in Linux, used to
communicate with the operating system via commands. You can typically [open the
terminal](https://www.makeuseof.com/how-to-open-terminal-in-linux/) by pressing
`Ctrl + Alt + T` or by searching for it in the start menu. Your terminal will
typically use `bash` as your
[shell](https://www.gnu.org/software/bash/manual/html_node/What-is-a-shell_003f.html).
Bash is the most widespread and considered the "standard." Other shells include
`fish` and `zsh`.

> With great power comes great responsibility.

### The File System

Linux has a hierarchical [file
system](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/4/html/reference_guide/s1-filesystem-fhs),
where all files and directories are placed under a root directory, typically
`/`. Other important directories include `/home`, which contains user data, and
`/var`, which contains system log files.

### Package Managers

[Package management](https://itsfoss.com/package-manager/) is an important
feature in Linux that allows you to easily and securely install and manage
software on your computer. Some of the most popular package managers include
`apt`, `yum`, `pacman`, `portage`, and `dnf`.

## Useful Resources

- [Linux Journey](https://linuxjourney.com/) - An interactive tutorial on the
Linux operating system and its components.
- [Linux Survival](https://linuxsurvival.com/linux-tutorial-introduction/) - A
comprehensive introduction to Linux and its key features and tools.
- [Ubuntu Help](https://help.ubuntu.com/community/UsingTheTerminal) - A guide
to using the terminal on the Ubuntu operating system, including basic commands
and tips.
- [Linux Command Library](https://lym.readthedocs.io/en/latest/) - A textbook
on Linux commands and system administration.
- [Ryan's Tutorials](https://ryanstutorials.net/linuxtutorial/) - A practical
guide to learning the Linux terminal from scratch and gradually building
complexity.
