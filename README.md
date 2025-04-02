# neovim-syntax-files

Neovim syntax files for DAX and Power Query M languages.

## Usage

Please both folders (`fpdetect` and `syntax`) in your Neovim [runtime path](https://neovim.io/doc/user/options.html#'runtimepath').
Open any DAX or pq file and syntax highlighting should be on automatically.

If for some reason file type is not detected, then set the file type manually:

```vim
:set filetype=dax
:set filetype=pq
```
