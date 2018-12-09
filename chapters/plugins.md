# Plugins

Existem várias maneiras de se instalar um plugin no Vim.

A que eu achei mais legal foi usando o [Vundle](https://github.com/VundleVim/Vundle.vim), pois acabou sendo parecido com o uso do Package Control com Sublime.

A instalação do Vundle é simples. Você vai criar uma pasta chamada `.vim` em `/home` (se ela ainda não existir), clonar o projeto com Git e configurar todo o resto no seu `.vimrc`.

Para ativar corretamente o Vundle é necessário deixar as seguintes linhas no seu
`.vimrc`:

```
 "Configure Vundle
 set nocompatible
 "filetype off

 "Vundle config
 set rtp+=~/.vim/bundle/Vundle.vim
 call vundle#begin()

 "need this to install Vundle
 Plugin 'gmarik/Vundle.vim'

 " ---- Plugins ----
```

Todos os plugins você pode adicionar abaixo da linha onde deixei: `" ----
Plugins ----`.