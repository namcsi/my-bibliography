# My Bibliography

Repostory containing all my bibliography files, compiled from various
sources. I use the emacs ebib package to manage my bibliography
files. 

## ebib

The main database, containing all bibliographic entries is
main.bib, all other databases are "dependent databases" of main.bib,
in ebib parlance. This means that entries in dependent databases are always
subsets of the main database; however, edits made on entries are
propagated to the main database, and vice versa (if the entry is
present in the dependent.
