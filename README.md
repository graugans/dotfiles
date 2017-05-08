# Christian Ege's Dotfiles

This is a collection of dotfiles and scripts I use for customizing They should be cloned to your home directory so that the path is `~/.dotfiles/`.

## Getting started

### Prerequisites

- Follow the install instructions for [powerline fonts](https://github.com/powerline/fonts#quick-installation)

### Clone the repository

```
git clone https://github.com/graugans/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
git submodule init
git submodule update
```

### Create symlinks

You may create backups of your previous config files

```
rm -rf ~/.vim ~/.vimrc
ln -s ~/.dotfiles/vim ~/.vim
```


## License

The code is available under the [MIT license](LICENSE).
