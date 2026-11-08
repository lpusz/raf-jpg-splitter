# raf-jpg-splitter

macOS CLI that sorts photos in a folder: `*.jpg` go to `JPG/`, `*.raf` go to `RAF/` (case-insensitive, top level only). Other files are left untouched; existing files are never overwritten.

    raf-jpg-splitter path/to/folder

## Install

    chmod +x raf-jpg-splitter
    mkdir -p ~/bin && cp raf-jpg-splitter ~/bin/
    echo 'export PATH="$HOME/bin:$PATH"' >> ~/.zshrc   # if ~/bin is not on PATH yet
