## To export:
```bash
brew list > brew-packages.txt & brew list --cask > brew-casks.txt
```

## To import:
```bash
xargs brew install < brew-packages.txt & xargs brew install --cask < brew-casks.txt
```
