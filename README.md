# dotfiles
Configuration files managed using [chezmoi](https://www.chezmoi.io/).

# Requirements
Brew. Then:
```
touch ~/.zshrc
brew install \
  alacritty \
  neovim \
  tmux \
  fzf \
  tpm \
  ripgrep \
  fd \
  rust-analyzer
```

# Tmux
Install plugins with `C-A I`.
Start session with `tmux $TMUX_OPTIONS new-session -As auto`.

