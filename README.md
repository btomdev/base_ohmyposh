# base_ohmyposh
oh-my-posh base model


## Install Oh My Posh
```bash
brew install jandedobbeleer/oh-my-posh/oh-my-posh
```

## Install Font
```bash
oh-my-posh font install meslo
```

## Initialize Oh My Posh in `~/.zshrc`
```bash
if [ "$TERM_PROGRAM" != "Apple_Terminal" ]; then
  eval "$(oh-my-posh init zsh --config 'https://raw.githubusercontent.com/btomdev/base_ohmyposh/refs/heads/main/.base.omp.toml')"
fi
```
