# dotfiles

###Install Necessary apps
####Homebrew
```
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
####Oh-My-ZSH
```
$ sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

###Download and Move Vim Files
```
$ git clone https://github.com/alewitt/dotfiles ~/dotfiles
$ cp ~/dotfiles/.vimrc ~/
$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

###Install Vim and Plugins
1. Install Vim (should be version 7.4 or higher)
  * Mac `$ brew install vim --with-override-system-vi`
  * Ubuntu `$ apt-get install vim`
1. Install Plugins
  * `$ vim +PluginInstall +qall`
  * `$ cp ~/dotfiles/.zshrc ~/`


