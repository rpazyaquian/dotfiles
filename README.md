# pragmaticivan' dotfiles

[![Build Status][tb]][tp]
[![Powered by Antibody][ab]][ap]

> It's a fork from https://github.com/caarlos0/dotfiles

> Config files for ZSH, Node, Go, Editors, Terminals and more.

[ap]: https://github.com/getantibody/antibody
[ab]: https://img.shields.io/badge/powered%20by-antibody-blue.svg?style=flat-square
[tb]: https://img.shields.io/travis/pragmaticivan/dotfiles/master.svg?style=flat-square
[tp]: https://travis-ci.org/pragmaticivan/dotfiles

## Installation

### Dependencies

First, make sure you have all those things installed:

- `git`: to clone the repo
- `curl`: to download some stuff
- `tar`: to extract downloaded stuff
- `zsh`: to actually run the dotfiles
- `sudo`: some configs may need that

### Install

Then, run these steps:

```console
$ git clone https://github.com/pragmaticivan/dotfiles.git ~/.dotfiles
$ cd ~/.dotfiles
$ ./script/bootstrap
$ zsh # or just close and open your terminal again.
```

> All changed files will be backed up with a `.backup` suffix.

### Recommended Software

For macOS, I recommend:

- iTerm: a better terminal emulator;

For Linux:

- Terminator: a better terminal emulator;

For both Linux and macOS:

- [`diff-so-fancy`](https://github.com/so-fancy/diff-so-fancy):
better git difs (you'll need to run `dot_update` to apply it);
- [`fzf`](https://github.com/junegunn/fzf):
fuzzy finder, used in `,t` on vim, for example;
- [`exa`](https://the.exa.website/): for better `ls`;
- [`mmake`](https://github.com/tj/mmake): a modern `make`.
- [`hub`](https://hub.github.com/): a command-line wrapper for git that makes
  you better at GitHub;

### macOS defaults

You use it by running:

```console
$DOTFILES/macos/set-defaults.sh
```

And logging out and in again.

## Further help:

- [License](/LICENSE.md)
