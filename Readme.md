Vim, syntax highlighting for ANTLR versions 3 and 4.

If you are using [VundleVim/Vundle.vim](https://github.com/VundleVim/Vundle.vim), add `Plugin 'dylon/vim-antlr'` to your `.vimrc` and install it via `:PluginInstall`.  Otherwise, copy the files `antlr3.vim` and `antlr4.vim` into ~/.vim/syntax, and add the following to your `.vimrc`:
```vim
au BufRead,BufNewFile *.g set syntax=antlr3
au BufRead,BufNewFile *.g4 set syntax=antlr4
```
