# homebrew-picguard

> PicGuard for Homebrew.

[![brew test-bot](https://github.com/picguard/homebrew-picguard/actions/workflows/tests.yml/badge.svg?branch=main)](https://github.com/picguard/homebrew-picguard/actions/workflows/tests.yml)

## Install

```shell
brew install picguard/picguard/picguard
```

Or

```shell
brew tap picguard/picguard

brew install picguard
```

Or, in a [`brew bundle`](https://github.com/Homebrew/homebrew-bundle) `Brewfile`:

```ruby
# Brewfile
tap "picguard/picguard"
brew "picguard"
```

## Debug

[Adding Software to Homebrew](https://docs.brew.sh/Adding-Software-to-Homebrew)

```shell
brew audit --strict --fix --cask picguard
```

[Brew Livecheck](https://docs.brew.sh/Brew-Livecheck)

```shell
brew livecheck --debug picguard
```

## Release

[How to Open a Homebrew Pull Request](https://docs.brew.sh/How-To-Open-a-Homebrew-Pull-Request)

```shell
brew bump --open-pr picguard
```

## Documentation

Your taps are Git repositories located at `$(brew --repository)/Library/Taps`

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
