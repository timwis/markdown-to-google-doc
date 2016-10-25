# markdown-to-google-doc
Converts a markdown file to `.docx` and then imports it to Google Drive 

## Dependencies
Requires [pandoc](http://pandoc.org) and [gdrive cli](https://github.com/prasmussen/gdrive).

## Usage
```bash
md2gd import <file>
md2gd export <docid>
```

## Installation
1. Clone this repository
2. Create a configuration file using: `echo MD2GD_DIR=$(pwd) > ~/.md2gdrc`
3. Either add the repository's directory to your $PATH or symlink it to a directory that's
already exposed on the path, ie. `ln -s ./md2gd ~/bin/md2gd`

