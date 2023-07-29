#My Neovim setup thtththtthththt
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
sudo mv nvim.appimage /usr/local/bin/nvim
sudo mv nvim /usr/local/bin
curl -fLo ~/.local/share/nvim/site/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
cp ~/.vimrc ~/.config/nvim/init.vim
# make sure that call plug#begin('~/.config/nvim/plugged') is in init.vim 
# installing Coc.nvim
curl -sL install-node.now.sh/lts | bash
#https://github.com/neoclide/coc.nvim
# installing sourcecodepro
https://github.com/adobe-fonts/source-code-pro/archive/variable-fonts.tar.gz

useful link https://www.linode.com/docs/tools-reference/tools/how-to-install-neovim-and-plugins-with-vim-plug/#what-is-neovim
