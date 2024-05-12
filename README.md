Package tblr-extras: Extra libraries for tabularray package.
Copyright (C) 2024 Manuel E. Merino <manuel.merino.pe@gmail.com>

The package may be distributed and/or modified under the conditions
of the LaTeX Project Public License, either version 1.3c of this
license or (at your option) any later version. The latest version
of this license is in
http://www.latex-project.org/lppl.txt
# Usage
Just use `\usepackage{tblr-extras}` after loading tabularray.
Activate the libraries using `\UseTblrLibrary` command.
## Caption Library
Use caption package to typeset tabularray tall and long tabulars captions.
Enable this library with `\UseTblrLibrary{caption}`
## Babel Library
Translate `contfoot` and `conthead` to current `babel`/`polyglossia` language. 
Currently only supports ngerman, french, spanish, russian and ukrainian translations.
Enable this library with `\UseTblrLibrary{babel}`
