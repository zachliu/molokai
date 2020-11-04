# Molokai Color Scheme for Neovim

Let's cut to the chase. It's bright. It has hight contrast.

## Installation

Use `vim-packager`

```vim
call packager#add('git@github.com:zachliu/molokai.git')
```

Use `vim-plug`

```vim
Plug 'zachliu/molokai'
```

## Toggle

I believe there is a color for every mood. If you are anxious, `PaperColorSlim` may soothe you. If you are perky, try `Molokai`.

```vim
function ToggleColorSchemes()
    if (g:colors_name == "PaperColorSlim")
        colorscheme Molokai
    else
        colorscheme PaperColorSlim
    endif
endfunction

nnoremap <silent> <leader>c :call ToggleColorSchemes()<CR>
```
