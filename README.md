# haskell-ghc-mod atom package

Haskell Ghc-Mod opens pipe to ghc-modi and queries types, info and checks
for errors.

Error check is enabled by default on saving file.

File needs to be saved before querying types.

Current features:

* Show type (ghc-mod type)
* Show symbol info (ghc-mod info)
* Check for errors (ghc-mod check)
* Insert type (symbol :: Type)

Default shortcuts:

* ctrl+alt+t: show type of selection/symbol under cursor
* ctrl+alt+i: show info on selection/symbol under cursor
* ctrl+alt+c: check for errors (done automatically on save)
* ctrl+alt+shift+t: insert type into buffer at line above current (experimental)

Haskell-ghc-mod depends on [language-haskell][1] to detect
Haskell sources.

ghc-modi currently needs to be in your PATH for this to work.

![Screencast][2]

[1]: https://atom.io/packages/language-haskell
[2]: https://raw.githubusercontent.com/lierdakil/haskell-ghc-mod/master/screencast.gif
