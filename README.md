# Homebrew tap

Homebrew formulae and casks maintained by [Chandler Klein](https://github.com/chandlerklein).

## Packages

| Package | Description | Platforms |
| --- | --- | --- |
| `ec` | [Everybody Codes CLI](https://github.com/chandlerklein/everybody-codes-cli) | macOS, Apple Silicon and Intel |

## Install

```sh
brew install --cask chandlerklein/tap/ec
ec --version
```

You can also add the tap once to browse its packages:

```sh
brew tap chandlerklein/tap
brew search chandlerklein/tap/
```

## Update

```sh
brew update
brew upgrade --cask chandlerklein/tap/ec
```

## Remove

```sh
brew uninstall --cask ec
```

## Maintenance

Stable releases of everybody-codes-cli automatically update `Casks/ec.rb` through GoReleaser. Its downloads and SHA-256 checksums come from that project’s GitHub releases. Prereleases do not update the cask. Additional packages can be added to `Formula/` or `Casks/`.
