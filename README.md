# neovim_config

## Prerequisites

Make sure you have _nvim_ installed.

## Setup Guide

```Bash
cd ~
mkdir .config
cd .config
git clone https://github.com/shaunyuencw/neovim_config
cd nvim
```

## Additional Steps

Open plugins-setup.lua once and save the file for packer to install all plugins

```Bash
nvim lua/shaun/plugins-setup.lua
```

Followed by :w to initialize installation

# Known Issues

## If live grep does not work, you might not have ripgrep installed

```Bash
brew install ripgrep
```

## tree-sitter CLI not found: 'tree-sitter' is not executable

```Bash
npm install -g tree-sitter-cli
```
