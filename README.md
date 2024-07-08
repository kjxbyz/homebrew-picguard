# homebrew-picguard

[![Test](https://github.com/picguard/homebrew-picguard/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/picguard/homebrew-picguard/actions/workflows/test.yml)
[![Excavator](https://github.com/picguard/homebrew-picguard/actions/workflows/excavator.yml/badge.svg)](https://github.com/picguard/homebrew-picguard/actions/workflows/excavator.yml)
[![Add version](https://github.com/picguard/homebrew-picguard/actions/workflows/version.yml/badge.svg)](https://github.com/picguard/homebrew-picguard/actions/workflows/version.yml)

## Install

`brew install picguard/picguard/picguard`

Or `brew tap picguard/picguard` and then `brew install picguard`.

Or, in a [`brew bundle`](https://github.com/Homebrew/homebrew-bundle) `Brewfile`:

```ruby
tap "picguard/picguard"
brew "picguard"
```

## Install a specific version

If you want to install a specific release, you can include the version in the command. You can also view the list of releases [here](https://github.com/picguard/picguard/releases).

```shell
brew install picguard/picguard/picguard@1-0-0-plus-298
```

Or

```bash
brew tap picguard/picguard

brew install picguard@1-0-0-plus-298
```

## Debug

`brew audit --strict --fix --cask picguard`

`brew livecheck --debug picguard`

## Documentation

Your taps are Git repositories located at `$(brew --repository)/Library/Taps`

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
