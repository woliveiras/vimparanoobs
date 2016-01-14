# Plugins no VIM

Existem várias maneiras de se instalar um plugin no VIM. 

A que eu achei mais legal foi usando o [Vundle](https://github.com/VundleVim/Vundle.vim), pois acabou sendo parecido com o uso do Package Control com Sublime.

A instalação do Vundle é simples. Você vai criar uma pasta chamada `.vim` em `/home`, clonar o projeto com Git e configurar todo o resto no seu .vimrc.

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

## Instalando os Plugins com Vundle

Imagine que você vai instalar um plugin de Markdown Preview, esse
[aqui](https://github.com/JamshedVesuna/vim-markdown-preview).

Basta adicionar no seu `.vimrc`:

```
Plugin 'JamshedVesuna/vim-markdown-preview'
```

Abrir o VIM e rodar o comando:

```
:PluginInstall
```

Agora é só aguardar a instalação.

## Atualizando plugins com o Vundle

Caso vá atualizar todos os plugins basta rodar:

```
:PluginUpdate
```

Ou `:PluginUptade nome_do_plugin` para atualizar somente um.

## Buscando um plugin com o Vundle

Para pesquisar um nome de plugin ou saber se determinado plugin é instalável via
Vundle você pode fazer:

```
:PluginSearch nome_do_plugin
```

## Removendo plugins com Vundle

Você pode deixar o Vundle deletar os plugins que não são utilizados com:

```
:PluginClean
```

Ele irá pedir permissão a cada opção de delete.

Caso queira deixar tudo nas mãos do Vundle basta rodar:

```
:PluginClean!
```

## Listando os plugins instalados

Basta rodar:

```
:PluginList
```

Para outros comandos do Vundle, acesse a [documentação
oficial](https://github.com/VundleVim/Vundle.vim).

## Geradores de vimrc files

[vimconfig.com](http://vimconfig.com/)
[vim-bootstrap.com](http://vim-bootstrap.com/)

[Voltar ao início](https://github.com/woliveiras/vim-noobs/ "Voltar ao início")
