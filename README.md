# Dotfiles

## Instaling
```bash
# 1. Install Homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# 2. Install brew bundle
.dotfiles % brew bundle install --file ./Brewfile

# 3. Stow dotfiles
stow . -t ~

# 4. Install TMP
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
# 5. Start TMUX and run <prefix>I to install plugins
```
