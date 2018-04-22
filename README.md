# saur (Simple AUR Helper)

[![Build Status](https://travis-ci.org/dylanaraps/saur.svg?branch=master)](https://travis-ci.org/dylanaraps/saur)
[![GitHub last commit](https://img.shields.io/github/last-commit/google/skia.svg)](https://github.com/dylanaraps/saur)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE.md)

The goal of this project is to create a dead simple and light on dependencies AUR helper. The main focus will be on installation and updating of packages.

The only required dependencies are `git`, `bash` and `pacman` which should already be installed on your system.


## Usage

```sh
saur pkg
saur pkg pkg pkg
```

## Install

Drop the script anywhere in your path.


## TODO

- [ ] Add flags.
    - [ ] Install flag `-S`.
    - [ ] Update flag `-Syu`.
- [ ] Check for PKGBUILD updates.
- [ ] Add Travis for linting/testing.
    - [ ] Write some tests (*Test installation of various AUR packages*).
