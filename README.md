# saur (Simple AUR Helper)

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
