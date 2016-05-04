# Dotfiles

These are my dotfiles. They are based on [Gerardo's dotfiles
](https://github.com/gerardo/dotfiles), with some modifications to be useful
also for scientists.

## Installation

```bash

$ git clone git://github.com/muammar/dotfiles ~/.dotfiles
$ cd ~/.dotfiles
$ ./install.sh
```

## Environment

I use this setup on Linux and Mac OSX systems. I use ZSH as my preferred shell,
but there's some older bash files around too. Really, you should switch to
ZSH, just change your shell with the following command:

` chsh -s /bin/zsh `

and you're all set!

The environment is in the lines of Python, Django, Homebrew, Vim, Git,
OSX/Linux.

### Sensible OS X defaults

When setting up a new Mac, you may want to set some sensible OS X defaults (it supports Yosemite!):

```bash
$ ./.osx
```

## Feedback

Suggestions and improvements [welcome](https://github.com/muammar/dotfiles/issues)!

## Thanks to…

* Gerardo Curiel [dotfiles](https://github.com/gerardo/dotfiles) repository.
