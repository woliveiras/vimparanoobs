# Comandos e atalhos personalizados

Com a personalização conseguimos criar comandos no VIM através do .vimrc.

Ex.:

Mapa para os comandos de trocar de Janela com `CTRL+``j`/`k`/`h`/`l` para facilitar a vida.

```
map <C-j> <C-W>j
map <C-k> <C-W>k
map <C-h> <C-W>h
map <C-l> <C-W>l
```

Usando:

`map`  - Criamos um Mapeamento em modo comando

`imap` - Mapeamento em modo de inserção.

`cmap` - Mapeamento em modo de linha de comando

`vmap` - Mapeamento no modo visual