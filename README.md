vim-ez80
=======

Vim syntax for EZ80 assembler (https://github.com/envenomator/agon-ez80asm/).

## Plugin installation
Plug 'tomm/vim-ez80'

## Manual installation
Run the following commands to install eZ80 syntax highlighting for the current user:
```
cd ~
git clone https://github.com/tomm/vim-ez80.git
cd vim-ez80
cp -r ftdetect ftplugin syntax ~/.vim
```

## Default file extension
`*.z80`

## Example config
```
autocmd Filetype asm setlocal ts=8 sw=8 noexpandtab
autocmd BufNewFile,BufRead *.asm set filetype=ez80
```
