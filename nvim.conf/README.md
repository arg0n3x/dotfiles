# Vim or Neovim Configuration File

## Description

This file contains the basic configurations for using Vim or Neovim, along with some utility shortcuts. The only important point to consider is the installation process.

### Installation for **Vim**

* Copy or move the file to the HOME directory:

```bash
 $ cp $PWD/vim $HOME/.vimrc

 $ mv $PWD/vim $HOME/.vimrc
```

* Create a symbolic link

```bash
 $ ln -svf $PWD/vim $HOME/.vimrc
```

### Installation for Neovim

* Create the nvim directory

```bash
 $ mkdir -m 700 -p $HOME/.config/nvim
```

* Copy or move the file to the HOME directory:

```bash
 $ cp $PWD/vim $HOME/.config/nvim/init.vim

 $ mv $PWD/vim $HOME/.config/nvim/init.vim
```

* Create a symbolic link

```bash
 $ ln -svf $PWD/vim $HOME/.config/nvim/init.vim
```

### Shortcuts

* Double press Esc to clear search results when using /search.

* Navigate with Ctrl + h, j, k, l in INSERT mode.
