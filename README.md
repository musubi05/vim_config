# vim_config

## Install

```bash
cd ~
sudo apt install vim-gnome
git clone https://github.com/musubi05/vim_config.git
ln -s vim_config/.vim .vim
ln -s vim_config/.vimrc .vimrc
git clone https://github.com/Shougo/neobundle.vim.git vim_config/.vim/bundle/neobundle.vim
```

If you need .gvimrc.

```
ln -s vim_config/.gvimrc .gvimrc
```

Then you are asked whether to execute NeoBundle install from Vim.

Install is completed if you answer y(es) and reopen Vim.
