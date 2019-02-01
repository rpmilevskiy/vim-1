**Installation:**
1) Install vim
```
sudo apt-get install libncurses5-dev libgnome2-dev libgnomeui-dev \
  libgtk2.0-dev libatk1.0-dev libbonoboui2-dev \
  libcairo2-dev libx11-dev libxpm-dev libxt-dev
  
sudo apt-get install ruby-dev

git clone git@github.com:vim/vim.git vim
cd vim/src
./configure --with-features=huge --enable-rubyinterp --enable-gui=gnome2
make
sudo make install
```
2) clone
`````
git clone https://github.com/rpmilevskiy/vim-1.git ~/.vim
`````
3) create symlink
````````````
ln -s  ~/.vim/.vimrc ~/.vimrc
````````````
4) open gvim and enter:
``````````
:BundleInstall
``````````
start on the full window
``````````
sudo apt-get install ctags wmctrl
``````````

That’s it!
***

==========
