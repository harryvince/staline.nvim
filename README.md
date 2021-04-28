# staline.nvim
A simple statusline for neovim written in lua.

### Screenshots
![normal mode](https://i.imgur.com/1gXX22o.png)
![insert mode](https://i.imgur.com/0bP6y0S.png)
![visual mode](https://i.imgur.com/v1sejC8.png)
![command mode](https://i.imgur.com/TD9CGJ6.png)


### Installation
* Vim-plug:
    ```vim
    Plug 'tamton-aquib/staline.nvim'
    ```
* Packer
    ```lua
    use { 'tamton-aquib/staline.nvim' }
    ```

### Setting up

* Default configuration
    ```lua
    require('staline').setup{
            leftSeparator   = "",
            rightSeparator  = "",
            cool_symbol     = " "
    }
    ```

### Features
* Lightweight (~3 kb)
* Fast
* Unicode current mode info.

### TODO

- [x] Break into modules.
- [x] Git info.
- [ ] User configuration options.
- [ ] Include more filetype support.
