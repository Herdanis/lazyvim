# 💤 LazyVim

A starter template for [LazyVim](https://github.com/LazyVim/LazyVim).
Refer to the [documentation](https://lazyvim.github.io/installation) to get started.

## ️🖇 List Addon Plugin <a name = "plugin"> </a>

- OneDarkPro - olimorris/onedarkpro.nvim
- Indent-Blankline - lukas-reineke/indent-blankline.nvim
- NeoTree - nvim-neo-tree/neo-tree.nvim
- NeoDev - folke/neodev.nvim
- Peek - toppair/peek.nvim
- Nvim-Surround - kylechui/nvim-surround (dissabled)
- ToggleTerm - akinsho/toggleterm.nvim

## ⌨️ List Keymaps <a name = "keymaps"> </a>

Key Description

- \<Leader> == Space
- \<C> == ⌃
- Alt == fn + ⌥
- \<A> == ⌥
- \<S> == ⇧

Mode Abbreviation

- N = Normal
- I = Insert
- V = Visual

| Keymap                  | Description                  | Mode    |
| ----------------------- | ---------------------------- | ------- |
| gcc                     | comment/uncomment            | N,V     |
| yy                      | copy one line                | N       |
| y                       | copy block                   | V       |
| p                       | paste                        | N, V    |
| dd                      | delete one line              | N       |
| d                       | delete block                 | V       |
| gg                      | go to first line             | N, V    |
| G                       | go to end line               | N, V    |
| w                       | go to next first character   | N, V    |
| b                       | go to back first character   | N, V    |
| e                       | go to next last character    | N, V    |
| ge                      | go to back last character    | N, V    |
| gsa + character pair    | add surround pair character  | V       |
| gsr + character pair    | change surround pair         | N       |
| gsd + character pair    | delete surround pair         | N       |
| \<S> v                  | block one line               | N       |
| \<A> k                  | move one line up             | N, V    |
| \<A> j                  | move one line down           | N, V    |
| \<S> h                  | switch buffer left           | N       |
| \<S> l                  | switch buffer right          | N       |
| \<C> \|                 | toogle horizontal CLI        | N       |
| \<C> h                  | jump to left window          | N       |
| \<C> l                  | jump to right window         | N       |
| \<C> k                  | jump to upper window         | N       |
| \<C> j                  | jump to lower window         | N       |
| \<C-S> arrow up/down    | resize window vertical       | N       |
| \<C-S> arrow left/right | resize window horizontal     | N       |
| \<C> e                  | scroll down                  | N, V    |
| \<C> y                  | scroll up                    | N, V    |
| \<C> d                  | scroll half screen down      | N, V    |
| \<C> u                  | scroll half screen up        | N, V    |
| \<C> d                  | scroll screen down           | N, V    |
| \<C> f                  | scroll screen up             | N, V    |
| \<leader> bd            | close buffer                 | N       |
| \<leader> gg            | open Lazygit                 | N, V    |
| \<leader> fF            | search                       | N, V    |
| \<leader> E             | open NeoTree                 | N, V    |
| \<leader> q             | quit vim                     | N, V    |
| \<leader> ,             | switch buffer                | N, V    |
| \<leader> gp            | gitsigns show changes        | N       |
| \<leader> gt            | gitsigns show toggle blame   | N       |
| s                       | open split vertial window    | NeoTree |
| S                       | open split horizontal window | NeoTree |
| x                       | mark cut file/dir            | NeoTree |
| y                       | mark copy file/dir           | NeoTree |
| c                       | copy file/dir                | NeoTree |
| m                       | move file/dir                | NeoTree |
| p                       | paste file/dir               | NeoTree |
| a                       | add file/dir                 | NeoTree |
| d                       | delete file/dir              | NeoTree |
| v                       | block file/dir               | NeoTree |
| p                       | pull remote                  | Lazygit |
| P                       | push to remote               | Lazygit |
| c                       | commit                       | Lazygit |
| \<leader>               | add file                     | Lazygit |
| \<C> d                  | scroll page down             | Lazygit |
| \<C> u                  | scroll page up               | Lazygit |
| A                       | amend last commit            | Lazygit |
| r                       | refresh                      | Lazygit |
| s                       | stash all                    | Lazygit |
| a                       | stash/unstash all            | Lazygit |
| q                       | exit LazyGit                 | Lazygit |
