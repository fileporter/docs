---
title: Getting Started
layout: default
nav_order: 0
---

* TOC
{:toc}

# Getting Started

> **requirements:**
> python (≥3.8)
> {: .label }
> python3-venv
> {: .label }
> bash
> {: .label }
> git
> {: .label }
> exiftool
> {: .label }
> imagemagick
> {: .label }
> libmediainfo-dev
> {: .label }

<sup>(An earlier version (≥3.5) of Python might also work but no guaranty)</sup>

```bash
sudo apt install -y python3 python3-venv bash git exiftool imagemagick libmediainfo-dev
```

# Setup

## Installation

```bash
curl -s https://raw.githubusercontent.com/fileporter/fileporter/main/scripts/installer | bash
```

it is also possible to specify the directory name
```bash
curl -s https://raw.githubusercontent.com/fileporter/fileporter/main/scripts/installer | bash -s -- {directory-name}
```

after that you have to add the following line to `~/.bashrc`.
(the correct line is printed by the installer)
```bash
source /path/to/the/repo/fileporter/scripts/bashrc
```

this adds the fileporter-executable to the path, adds autocompletion and adds a `man fileporter` page.

## Configuration

[see here for configuration](../configuration/index.md)

# Running

To start fileporter you can simply run the `fileporter` command anywhere your want
(`fileporter [ARGS]`)
