## Macroutils

Starts your vim with some useful macros preloaded.


#### @c

Takes a comma separated list of words and wraps them with single quotes.

`words, words, words` becomes `'words', 'words', 'words` with `3@c`.  (You'll have to add the last quote yourself.)


#### @j and @J

Takes a return separated list of words wrapped in double quotes.  E.g.,

hello
hi
how are you

would become:

```
"hello",
"hi",
"how are you"`
```

with `@J`, they are joined into one line:

`"hello", "hi", "how are you"`


#### @l

If you have a line that is longer than 80 characters long, this macro will find the word closest to the 80th character line and create a line break at the end of that word.


#### More to come...


## Installation

You've done that, you can install this plugin using [pathogen.vim](https://github.com/tpope/vim-pathogen) with the following commands:

```
cd ~/.vim/bundle
git clone https://github.com/peterhurford/macroutils.vim
```
