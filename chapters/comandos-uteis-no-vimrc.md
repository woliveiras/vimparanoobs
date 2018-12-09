# Comandos uteis no .vimrc

Você pode achar vários comandos úteis dando uma olhada [nesses arquivos de .vimrc](/exemplos-de-vimrc.html).

No meu .vimrc só coloquei o que estou usando até agora:

```
"Cute ;D
syntax on
set encoding=utf8
set number
set tabstop=2
set eb
set expandtab
set hlsearch
set ignorecase
set incsearch
set showcmd
set showmatch
set textwidth=80
set cursorline
filetype indent on

" Smart way to move between windows
map <C-j> <C-W>j
map <C-k> <C-W>k
map <C-h> <C-W>h
map <C-l> <C-W>l

" space open/closes folds
nnoremap <space> za

"Theme
colorscheme monokai

```