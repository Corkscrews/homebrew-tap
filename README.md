# Corkscrews Homebrew tap

```bash
brew tap corkscrews/tap
brew trust corkscrews/tap  # Homebrew only loads casks from taps you trust
brew install --cask corkscrews/tap/fruit-screensaver
```

| Cask | Project |
|------|---------|
| `fruit-screensaver` | [Corkscrews/fruit](https://github.com/Corkscrews/fruit) |

Fruit isn't signed or notarized, so it isn't accepted in Homebrew's main cask repository. If macOS refuses to open it, clear the quarantine flag:

```bash
xattr -dr com.apple.quarantine ~/"Library/Screen Savers/Fruit.saver"
```
