# dotfiles

## Chage default shell to bash
chsh --shell /bin/bash <your-username>

## Install starship
* > curl -sS https://starship.rs/install.sh | sh
* add to .bashrc 
```sh
eval "$(starship init bash)"
```
* add starship config ~/.config/starship.toml

## Install neovim
### Dependencies
[Ripgrep](https://github.com/BurntSushi/ripgrep)

## Install tmux
> git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm
