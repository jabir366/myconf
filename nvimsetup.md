#My Neovim setup
sudo apt-get install neovim

for installing vim-plug
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
download vimrc
wget https://gist.githubusercontent.com/HansPinckaers/6ddcc534aef531fef897fba985d31258/raw/04f9d6c03570eba3663a1ea7029e3dfa590523cf/.vimrc

restart neovim and :PlugInstall
https://github.com/amacgregor/dot-file://github.com/amacgregor/dot-files


=============================
curl -LO https://github.com/neovim/neovim/releases/download/stable/nvim.appimage
chmod u+x nvim.appimage
mv nvim /usr/local/bin
sudo mv nvim /usr/local/bin
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
cp ~/.vimrc ~/.config/nvim/init.vim
# make sure that call plug#begin('~/.config/nvim/plugged') is in init.vim 
