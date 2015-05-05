## Macroutils

Starts your vim with some useful macros preloaded.

#### @c

Takes a comma separated list of words and wraps them with single quotes.

`words, words, words` becomes `'words', 'words', 'words` with `3@c`.  (You'll have to add the last quote yourself.)

#### @j

Takes a return separated list of words and joins them into one line, wrapped in double quotes.  E.g.,

hello
hi
how are you

would become `"hello", "hi", "how are you"`


#### More to come...
