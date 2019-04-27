# Brewfile

*Install or update all your macOS applications with `brew bundle`*

## Usage

### Install homebrew

*Homebrew is the missing package manager for macOS*

```bash
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Install mas-cli

*Mac App Store command line interface*

```bash
$ brew install mas

# Search for applications by name
$ mas search Xcode
497799835 Xcode
```

### Brew bundle

*Bundler for non-Ruby dependencies from Homebrew*

```bash
$ git clone https://github.com/laozhu/brewfile
$ cd brewfile
$ brew bundle
```

Now it's time to enjoy your macOS 🎉

### Credits

- [homebrew](https://brew.sh/)
- [homebrew-cask](https://github.com/Homebrew/homebrew-cask)
- [homebrew-cask-fonts](https://github.com/Homebrew/homebrew-cask-fonts)
- [homebrew-bundle](https://github.com/Homebrew/homebrew-bundle)
- [homebrew-services](https://github.com/Homebrew/homebrew-services)
- [homebrew-dart](https://github.com/dart-lang/homebrew-dart)
- [mas-cli](https://github.com/mas-cli/mas)
- [quick-look-plugins](https://github.com/sindresorhus/quick-look-plugins)
