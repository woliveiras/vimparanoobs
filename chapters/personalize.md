#Personalizando o VIM

Para configurar o VIM, usamos alguns comandos do :set

Basta estar no modo Normal ou Command Mode e digitar os
comandos.

`:set autowrite` ou `:set aw` - Salva o arquivo a cada alteração
`:set errorbell` ou `:set eb` - Apita cada vez que você errar
um comando.


## Editando as preferências do VIM

O VIM possui um arquivo de configuração, o `.vimrc`.

Esse arquivo fica oculto em sua pasta `/home`. Para editar suas
preferências você pode usar: 

```
vim ~/.vimrc
```

### Não precisar setar comandos toda vez que abre o VIM

No arquivo ~/.vimrc você pode setar as configurações para
não precisar ficar setando tudo cada vez que abre o editor.

**Exemplo de arquivo .vimrc:**

```
syntax o
set encoding=utf8
set number
set tabstop=2
set eb
set autowrite
set expandtab
set hlsearch
set ignorecase
set incsearch
set showcmd
set showmatch
```

## Criando comandos no VIM

Com a personalização conseguimos criar comandos no VIM através do .vimrc.

Ex.:

```
map <C-j> <C-W>j
map <C-k> <C-W>k
map <C-h> <C-W>h
map <C-l> <C-W>l
```

Mapa para os comandos de trocar de Janela com CTRL+j/k/h/l para facilitar a vida.

Usando:

`map`  - Criamos um Mapeamento em modo comando

`imap` - Mapeamento em modo de inserção.

`cmap` - Mapeamento em modo de linha de comando

`vmap` - Mapeamento no modo visual

## Temas no VIM

Para encontrar um  esquema de cores maneiro para o seu VIM, você pode
acessar o site [vimcolors.com](http://vimcolors.com/).

Será necessário criar uma pasta dentro de `~/.vim` (se a pasta .vim ainda não
existir, crie ela agora).

Os temas serão instalados, assim como os plugins, dentro de `~/.vim/bundle`.
Normalmente no README do tema tem o passo a passo de instalação, mas basicamente
você sempre vai fazer:

```
cd ~/.vim/colors
git clone esquemadecores.git
```

E adicionar a linha do esquema no seu `.vimrc`.

Ex. do [esquema de cores](https://github.com/sickill/vim-monokai) que eu uso atualmente:

```
colorscheme monokai 
```
