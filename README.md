VERY BETA
---------

Copy bitbucket.org or github.com current line url to clipboard.

Installation
------------

### Using [vim-plug](https://github.com/junegunn/vim-plug)

```vim
Plug 'opd/vcsurl.vim'
```

### Configuring

```vim
nmap <leader>bb :GetVCSLineUrl<CR>
```

### TODO

- Add configuring options
- Add branch, register params
- Add tests
- Add documentation
- Use default/current register
- Determine actual line number considering file changes
- Add option for using `hg identify $(hg paths default)` instead of default branch
