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

### Não precisar setar configurações sempre

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

## Comandos e atalhos personalizados

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

## Mudando o tema

Para encontrar um  esquema de cores maneiro para o seu VIM, você pode
acessar o site [vimcolors.com](http://vimcolors.com/).

Alguns temas tem suporte ao Vundle, portanto será possível instalar com o mesmo, assim como acontece com [plugins](./plugins.md#instalando-os-plugins-com-vundle).

Será necessário criar uma pasta dentro de `~/.vim` (se a pasta .vim ainda não
existir, crie ela agora).

Os temas podem ser clonados dentro de `~/.vim/colors` para melhor organização, porém o Vundle, por exemplo, coloca dentro de `./vim/bundle`.
Normalmente na documentação do próprio tema tem um passo a passo de instalação, mas basicamente
você sempre vai fazer:

```
cd ~/.vim/colors #Pasta com esquemas de cores
git clone esquemadecores.git
```

E adicionar a linha do esquema no seu `.vimrc`.

Ex. do [esquema de cores](https://github.com/sickill/vim-monokai) que eu uso atualmente:

```
colorscheme monokai 
```

## Adicionando sintaxes

O mesmo que acontece com os temas ocorre com as sintaxes das linguagens, alguns poderão ser facilmente instalado com o Vundle, outras serão facilmente instaladas manualmente. :)

Basicamente você poderia fazer isso em uma instalação manual:

```
cd ~/.vim/syntax
git clone arquivo_sintaxe
```

*Porém o Vundle também coloca esse tipo de arquivo dentro de `./vim/bundle`.*

E adicionar ao `.vimrc`

```
au FileType type call SyntaxFoo()
```
