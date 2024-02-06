# dotfiles :open_file_folder:
My dotfiles, installable using [Stow](http://www.gnu.org/software/stow/ "GNU Stow").
```
git clone https://github.com/brent-lemmon/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
stow .
```

# zsh
Clone the following dependencies:
```
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git $ZDOTDIR/themes/powerlevel10k
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZDOTDIR/plugins/zsh-syntax-highlighting
git clone https://github.com/zsh-users/zsh-autosuggestions $ZDOTDIR/plugins/zsh-autosuggestions
git clone https://github.com/zsh-users/zsh-history-substring-search.git $ZDOTDIR/plugins/zsh-history-substring-search
```