# zephyr-nvim
A transparent neovim colorscheme written in lua and syntax based on
[nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter).
My goal in forking the original `zephyr` project was to improve it for transparent backgrounds and markdown.

### Install

eg: vim-plug
```vim
Plug 'gortnamearacaun/zephyr-clear.nvim'
Plug 'nvim-treesitter/nvim-treesitter'
```

### Usage

```lua
lua require('zephyr_clear')
```
or

```vim
colorscheme zephyr_clear
```

```lua
-- get zephyr color
local zephyr_clear =  require('zephyr_clear').
zephyr.yellow/teal/fg/bg
```
### Preview

![zephyr](https://user-images.githubusercontent.com/41671631/110207650-e291ee80-7ebf-11eb-813d-305fee299322.png)
