# !THEOS!

# Table of Contents

- [!THEOS!](#theos)
- [Table of Contents](#table-of-contents)
- [Introduction](#introduction)
- [Installation](#installation)
  - [Using the GitHub CLI](#using-the-github-cli)
  - [Using Git](#using-git)
- [Usage](#usage)

# Introduction

This repository is meant to easly setup a new Computer with my personal settings. It is meant to first cleanly install the [OS](!THEOS!) and then directely run the script.\

Versioning is done with a [version file](version.txt). The lines work as this:

1. Version of the config files
1. Version of the package list
1. Version of the additional programs
1. Version of the one time setup

# Installation

## Using the [GitHub CLI](https://github.com/cli/cli)

This is not tested as the GitHub Cli doesn't work on my machine.

```bash
gh clone quiode/!THEOS!
cd !THEOS!/scripts/main
chmod +x get.sh install.sh set.sh
./install.sh
```

## Using [Git](https://git-scm.com/)

```bash
git clone https://github.com/quiode/THEOS!
cd !THEOS!/scripts/main
chmod +x get.sh install.sh set.sh
./install.sh
```

# Usage

- Install the dotfiles with [install](./scripts/main/install.sh).
- Update the dotfiles on the system with the files in the repository with [update](./scripts/main/set.sh).
- Update the dotfiles in the repository with the files in the system with [update](./scripts/main/get.sh).
- After an installation, you can use the [!THEOS!](scripts/!THEOS!) script to update, install or set the dotfiles.

```
$ !THEOS! [install|update|set|--help]
```
