Package `colorbox`
==================
This package provides `tcolorboxes` designed to stand out and to contain
source code. The package currently supports `minted` only. (PR welcomed! :D)

Quick view
----------
`codebox` provides 1 environment (`codebox`) and 3 commands (`setmintedcodebox`,
`newcodeboxedmintedfile` and `code`).

Please see the file demo.pdf (TODO) for broader information.

### `codebox`
This environment simply creates the box with the given parameters:

```latex
\begin{codebox}[title=Title,icon=\faCode,right title=author: some guy,compact]
  the content you like
\end{codebox}
```

### `setmintedcodebox`
TODO

### `newcodeboxedmintedfile`
TODO

### `code`
Creates a small inline box a la GitHub to make code snippets inside sentences a bit fancier.

Requirements
------------
- xcolor
- tcolorbox
- ifthen
- keyval
- fontawesome
- minted
