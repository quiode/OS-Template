# !THEOS!

# Table of Contents

1. [Introduction](#introduction)
1. [Installation](#installation)
1. [Usage](#usage)

# Introduction

This repository is meant to easly setup a new Computer with my personal settings. It is meant to first cleanly install the [OS](!THEOS!) and then directely run the script.

# Installation

## Using the [GitHub CLI](https://github.com/cli/cli)

This is not tested as the GitHub Cli doesn't work on my machine.

```bash
gh clone quiode/!THEOS!
cd !THEOS!/scripts
chmod +x get install set
./install
```

## Using [Git](https://git-scm.com/)

```bash
git clone https://github.com/quiode/THEOS!
cd !THEOS!/scripts
chmod +x get install set
./install
```

# Usage

- Install the dotfiles with [install](./scripts/install).
- Update the dotfiles on the system with the files in the repository with [update](./scripts/set).
- Update the dotfiles in the repository with the files in the system with [update](./scripts/get).
