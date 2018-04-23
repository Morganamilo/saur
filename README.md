# saur (Simple AUR Helper)

[![Build Status](https://travis-ci.org/dylanaraps/saur.svg?branch=master)](https://travis-ci.org/dylanaraps/saur)
[![GitHub last commit](https://img.shields.io/github/last-commit/google/skia.svg)](https://github.com/dylanaraps/saur)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE.md)

The goal of this project is to create a dead simple and light on dependencies AUR helper. The main focus will be on installation and updating of packages.

The only required dependencies are `curl`, `git`, `bash` and `pacman` which should already be installed on your system.

`saur` does not yet support complex AUR packages (`aws-cli-git`, `ros-lunar-desktop`) or selecting packages from a group (`clion`, `libc++`, `python-pyalsaaudio`). These features are being worked on but will only be implemented if they can be done so simply.


## Usage

```sh
# Install packages
saur pkg
saur pkg pkg pkg

# Update packages (saur with no arguments)
saur
```

## Install

Drop the script anywhere in your path.
