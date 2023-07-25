My vim configure file
Follow the next steps to install VIM settings:

1 - make a directory and clone this repository
```console
mkdir new_directoy
git clone https://github.com/andresnino1/myvim.git
```

2 - create a new directory under ~/.vim
```console
cd ~
mkdir .vim
```

3 - create a colors directory in the /.vim 
```console
cd .vim
mkdir colors
```

4 - copy the colors directory that was cloned in new_directory in step 1 to the colors directory in /.vim
5 - copy the file .vimrc in home directory ~/
6 - if you are using VIM in a Raspberrypi, you probably are using vim-tiny, so you would need to uninstall vim-tiny
```console
sudo apt-get remove vim-tiny
```
7 - update the linux packages
```console
sudo apt update
sudo apt upgrade
```
8 - install VIM
```console
sudo apt install vim
```
9 - clone the vim package manager in the ~/.vim directory
```console
git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```
10 - open vim and then execute :PluginInstall
