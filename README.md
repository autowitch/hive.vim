hive.vim
========

Vim syntax highlighting for hive


Append these line to ~/.vimrc:

```
" for .hql files
au BufNewFile,BufRead *.hql set filetype=hive expandtab

" for .q files
au BufNewFile,BufRead *.q set filetype=hive expandtab
```
