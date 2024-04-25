# My Dotfiles Backup

My .dotfiles' backup using [Gnu Stow](https://www.gnu.org/software/stow/).

## Requirements

You must have the following installed on your system:

### Git

It usually comes with Mac Os, otherwise install it with your preferred package manager. Apple also ships a binary package of Git with [Xcode](https://developer.apple.com/xcode/)

### Brew

Or any other package manager.

[Brew](https://brew.sh/) (or Homebrew for that matter) can be installed by using the following command:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Stow

Having brew installed, install GNU Stow:

```bash
brew install stow
```

## Installation

Clone this project into your home folder, where the **dotfiles** would usually show up.
Then just change the directory into the cloned repo and run **stow** to create the symlinks:

```bash
cd dotfiles-stow
stow .
```
