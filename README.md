# Brewfile

> Install or update all your macOS applications with `brew bundle`

## Usage

### Install homebrew

> Homebrew is the missing package manager for macOS

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Install mas-cli

> Mac App Store command line interface

```bash
$ brew install mas

# Search for applications by name
$ mas search Xcode
497799835 Xcode
```

### Brew bundle

> Bundler for non-Ruby dependencies from Homebrew.

```bash
$ git clone https://github.com/laozhu/brewfile
$ cd brewfile
$ brew bundle
```

Now it's time to enjoy your macOS 🎉
