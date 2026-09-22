# Runtime Components

This program contains files for running Git in terminal

## .bashrc
- bash reads this file each time an interactive terminal is opened
- the file formats terminal output and adds command shortcuts

## .zshrc
- read by zsh, the default shell on macOS
- adds themes and command shortcuts

## .vimrc
- read by vim each time the editor is opened
- formats code editor and adds commands

## .gdbinit
- read by gdb to format terminal output and adjust window settings
  
## .gitconfig
- git reads this file each time it runs
- formats output and adds command aliases

## install.sh
- copies files to home directory
- sends files to git for configuration
- installs oh-my-zsh, if zsh is available
