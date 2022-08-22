### Vim
---
[Vim](http://www.vim.org/) is a highly configurable text editor built to make creating and changing any kind of text very efficient. It is included as "vi" with most UNIX systems and with Apple macOS.

#### Installation
```
brew install vim
```

#### The Ultimate vimrc
[The Ultimate vimrc](https://github.com/amix/vimrc) is a collection of vimrc configurations to make easy the usage of vim.

##### Download vimrc 
```
git clone https://github.com/amix/vimrc.git ~/.vim_runtime
```
To install the complete version:
```
sh ~/.vim_runtime/install_awesome_vimrc.sh
```

To install the basic version:
```
sh ~/.vim_runtime/install_basic_vimrc.sh
```

##### Update
```
cd ~/.vim_runtime && git pull --rebase && cd -
```

#### Maximum Awesome
[Maximum Awesome](https://github.com/square/maximum-awesome) is a collection of vim configuration and plugins, like a configuration manager for the vim environment.

##### Download Maximum Awesome
```
git clone https://github.com/square/maximum-awesome.git
```

##### Install
```
cd maximum-awesome
rake
```
>`rake` command will install all dependencies needed.


