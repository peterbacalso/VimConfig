# VimConfig

1. Setup Vundle plugin manager
```
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

2. Install YouCompleteMe dependencies [https://github.com/ycm-core/YouCompleteMe](https://github.com/ycm-core/YouCompleteMe)

3. Download [RltvNmbr.vba.gz](https://www.vim.org/scripts/script.php?script_id=2351) and run the following in the terminal
```
vim RltvNmbr.vba.gz
:so % 
```

4. Install vim-markdown-preview dependencies
```
sudo apt-get update
sudo apt-get install -y markdown
sudo apt install xdotool
```

5. Open vim and install plugins with `:PluginInstall`
