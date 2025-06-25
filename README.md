# Mega's dotfiles
Installation
------------

Your first step is to clone this repository:
```
https://github.com/MEGAMMS/dotfiles
git clone https://github.com/MEGAMMS/dotfiles ~/.dotfiles
```
### Manual Installation

Create symbolic links for the configurations you want to use, e.g.:
```
ln -s ~/.dotfiles/vim/.vimrc ~/.vimrc
```
### Using [GNU Stow](https://www.gnu.org/software/stow/)

Install GNU Stow _(if not already installed)_
```
Mac:      brew install stow
Ubuntu:   apt-get install stow
Fedora:   yum install stow
Arch:     pacman -S stow
```
Then simply use `stow` to install the dotfiles you want to use:
```
cd ~/.dotfiles
stow vim
stow tmux
```


