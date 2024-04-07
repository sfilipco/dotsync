# dotfiles
Configuration files managed using [chezmoi](https://www.chezmoi.io/).

# Requirements
Brew. Then:
```
touch ~/.zshrc.local
brew install \
  alacritty \
  neovim \
  tmux \
  fzf \
  tpm \
  ripgrep \
  fd \
  rust \
  rust-analyzer \
  gh \
  MisterTea/et/et \
  nushell \
  chezmoi
```

# FZF
Run `fzf` to generate `.fzf.zsh`.

# Tmux
Install plugins with `C-A I`.
Start session with `tmux $TMUX_OPTIONS new-session -As auto`.

# Neovim
See package manager to install: 
  https://github.com/wbthomason/packer.nvim#quickstart
