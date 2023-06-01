# Vim Workshop

## Introduction

This workshop is for people who are new to Vim or have used it before but want to learn more about it. It is a hands-on workshop, so you will be using Vim throughout the workshop. The workshop is divided into three parts:

- Part 1: Introduction to Vim and installation
- Part 2: Basic Vim
- Part 3: Configuration of Vim

## Part 1: Introduction to Vim and installation

### What is Vim?

Vim is an editor in the terminal. It is a modal editor, which means that it has different modes. The most important modes are:

- Normal mode: This is the mode you are in when you open Vim. You can use this mode to navigate through your file and to execute commands.
- Insert mode: This is the mode you are in when you want to insert text. You can enter this mode by pressing `i` in normal mode.
- Command mode: This is the mode you are in when you want to execute commands. You can enter this mode by pressing `:` in normal mode.
- Visual mode: This is the mode you are in when you want to select text. You can enter this mode by pressing `v` in normal mode.

### Installation

#### Linux

##### Ubuntu

```bash
sudo apt install vim
```

##### Arch Linux

```bash
sudo pacman -S vim
```

#### macOS

```bash
brew install vim
```

#### Windows

Download the installer from [here](https://www.vim.org/download.php#pc).

## Part 2: Basic Vim

### Vimtutor

Vim comes with a built-in tutorial. You can start it by typing `vimtutor` in your terminal. It is recommended to do the tutorial before continuing with this workshop.

You can also use [openvim](https://www.openvim.com/) to learn Vim with a nice ui.

If you would like to lean how to move in Vim you can use [vim-adventures](https://vim-adventures.com/).

### Try out Vim

Try to make a Hello World in c using Vim.

## Part 3: Configuration of Vim

Vim is configured in vimscript in the .vimrc
Inside if you put this line you can have a configuration for Epitech
```vim
set shiftwidth=4 smarttab       " is use to transform the tab key in 4 spaces
set expandtab                   " it forces vim to use space and never tab
set number                      " display the number
" or
set relativenumber              " display the number that help for jump
```

If you want to configure something for vim you can go to Youtube, Stack Overflow, Github or Reddit and ask some question

But you can use neovim if you want more options and it's configuration is in Lua
