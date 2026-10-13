# homebrew-fvm

Homebrew formula for [FVM](https://github.com/btwld/fvm).

## Installing

```sh
brew tap btwld/fvm
brew install btwld/fvm/fvm
```

## Migrating from leoafarias/fvm

The tap has moved to `btwld/fvm`. To move an existing installation:

```sh
brew tap btwld/fvm
brew uninstall fvm
brew untap leoafarias/fvm
brew install btwld/fvm/fvm
```

This reinstalls the FVM executable; your cached Flutter SDKs and project configuration are retained. If you installed a versioned formula, use its name (for example, `fvm@4.3.1`) in the uninstall and install commands.

## Uninstalling

```sh
brew uninstall fvm
brew untap btwld/fvm
```
