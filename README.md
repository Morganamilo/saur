# saur (Simple AUR Helper)

[![Build Status](https://travis-ci.org/dylanaraps/saur.svg?branch=master)](https://travis-ci.org/dylanaraps/saur)
[![GitHub last commit](https://img.shields.io/github/last-commit/google/skia.svg)](https://github.com/dylanaraps/saur)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE.md)

The goal of this project is to create a dead simple and light on dependencies AUR helper. The main focus will be on installation and updating of packages.

This AUR helper will not be an interface to `pacman` commands but an entirely separate utility. I believe that local repos and the AUR should remain separate as they already are.

The only required dependencies are `curl`, `git`, `bash` and `pacman` which should already be installed on your system.


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
