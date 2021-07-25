<h1 align="center">tuterm</h1>

<p align="center">
  <a href="https://aur.archlinux.org/packages/tuterm/"> <img src="https://img.shields.io/aur/version/tuterm?label=AUR" alt="AUR"/> </a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-blueviolet" alt="License"/></a>
</p>

<p align="center">
  <a href="https://asciinema.org/a/427112" target="_blank">
    <img src="https://asciinema.org/a/427112.svg" />
  </a>
</p>

Tuterm is a framework for running and creating real-time interactive tutorials
and demonstrations of CLI programs.

Key features:

**For users**
* Ridiculously easy to use
* Customizable
* Step by step instructions
* Learn at your own pace

**For tutorial creators**
* Nothing more than a bash extension
* Create interactive tutorials and non-interactive demos with the same code
* Simple framework and minimalistic design
* Well documented
* Doesn't reinvent the wheel

**UNDER CONSTRUCTION:** [A collection of tutorials for your favorite CLI programs][collection]

# Installation

After cloning this repository or downloading the source code, simply run

```shell
make install
```
(You may need to use `sudo`)

This will install tuterm under `/usr/local`. You can change this by setting `PREFIX=/your/path/of/choice`.

# Documentation

Everything is documented inside the man page that is installed with tuterm.

# Contributing

Please, feel free to report any issues or feature requests [here][issues].
But before you do that, have a look at [TODO](./TODO.org).
(this file will steadily dissolve into GitHub issues)

If you want to submit a bug fix, you can simply open a pull request. But if you
want to add a new feature, open an issue so we can discuss it first.

Everyone is welcome to contribute.

*A note: Tuterm is a simple program, so most issues or features should be a good choice for a beginner.*

[collection]: https://github.com/HarisGusic/tuterm-collection
[issues]: https://github.com/HarisGusic/tuterm/issues
