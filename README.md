.vim
====

This repository is forked from the excellent [jfrazelle/.vim](https://github.com/jfrazelle/.vim) repository. All credit and many thanks for its content goes to her.

My vim dot files. the `.vimrc` file is saved to [vimrc](https://github.com/petersellars/.vim/blob/master/vimrc).

Just run the following commands via terminal to get perfectly set up:

```console
$ cd ~/
$ git clone --recursive git@github.com:petersellars/.vim.git .vim
$ ln -sf $HOME/.vim/vimrc $HOME/.vimrc
```

### Pathogen
The vim dot files make use of the excellent [Pathogen](https://github.com/tpope/vim-pathogen) runtime path manager to install plugins and runtime files into their own private directiories.

Currently using version 2.2 of Pathogen

### Plugins Used

* Dockerfile 
* [ack](https://github.com/mileszs/ack.vim) - Search Tool
* [delimitMate](https://github.com/vim-scripts/delimitMate.vim) - Automatic
  closing of quotes, parenthesis, brackets, etc.
* [ember](https://github.com/dsawardekar/ember.vim) - Ember Support
* [minibufexpl](https://github.com/fholgado/minibufexpl.vim) - Buffer Status
* [nerdtree](https://github.com/scrooloose/nerdtree) - Filesystem Explorer
* [portkey](https://github.com/dsawardekar/portkey) - Move around Project Files
* [syntastic](https://github.com/scrooloose/syntastic) - Syntax Checking
* [tabular](https://github.com/godlygeek/tabular) - Tab Control
* [vim-airline](https://github.com/bling/vim-airline) - Lean status/tabline
* [vim-cfmt](https://github.com/crosbymichael/vim-cfmt) - C code formatter
* [vim-colors-solarized](https://github.com/altercation/vim-colors-solarized) - Solarized Colorscheme
* [vim-endwise](https://github.com/tpope/vim-endwise) - End certain structure
  automatically
* [vim-fugitive](https://github.com/tpope/vim-fugitive) - Git Wrapper
* [vim-flavored-markdown](https://github.com/jtratner/vim-flavored-markdown) - GitHub flavored Markdown
* [vim-gitgutter](https://github.com/airblade/vim-gitgutter) -Gif diff in
  'gutter'
* [vim-go](https://github.com/fatih/vim-go) - Go support
* [vim-indent-lines](https://github.com/Yggdroot/indentLine) - Display space
  indentation levels
* [vim-json](https://github.com/leshill/vim-json) - JSON support
* [vim-systemd](https://fedorapeople.org/cgit/wwoods/public_git/vim-scripts.git) - Fedora Support
* [vim-toml](https://github.com/cespare/vim-toml) - TOML support
