# Dicas de VIM para Noobs

> Sinta-se hackudo

## Por que desse repositório?

Criei esse repositório com o objetivo de ser um local para guardar minhas anotações enquanto aprendo a usar o editor.

Se tiver alguma dica legal de uso do VIM, [manda pra mim!](mailto:w.oliveira542@gmail.com). :D

[Pular Introdução](#usando-o-vim)

## Introdução

**O que é VIM?**

Se você caiu nesse repositório e nem mesmo sabe o que é [VIM](http://www.vim.org/), da uma olhada [aqui](http://aurelio.net/vim/vi-vim-venci.html) e, se quiser baixar um livro legal sobre o editor, olha [aqui](https://code.google.com/p/vimbook/downloads/list).

**Por que usar VIM?**

Pra se sentir Hackudo/Hackero/Hackerzaum/Monstro das programaçaum/pra parecer Hacker de filme, etc

Quem olhar você digitando texto nessa tela:

![VIM](./images/vim-hackudo.gif "Imagem do editor VIM com um arquivo aberto.")


Vai te achar um monstro das hackeragem, o próprio [Kevin Mitnick](https://en.wikipedia.org/wiki/Kevin_Mitnick "Kevin Mitnick, o Hackudo monstraum.").

Eu decidi testar o VIM quando, em um [Meetup](http://meetup.com/ "Site meetup.com."), vi um cara escrever a seguinte linha de texto no Terminal:

```
sufocar cara_da_frente
```

Pressionar um `ESC` e digitar `:wq` e o cara que estava sentado na frente dele começou a ficar sem ar!

Isso foi incrível cara.

Me mostrou os poderes do lado negro da força. Eu pensei: *"Preciso de todo esse poder!"*

**Brincadeira**

Muita gente diz que usar o VIM é mais produtivo do que outros editores como o Sublime (:heart:). Então eu resolvi testar e tirar minhas conclusões de com qual editor vou me dar melhor.

Para facilitar o workflow criei esse repo para deixar os comandos que mais utilizo, configurações, etc.

##Usando o VIM

- [Primeiros passos com o VIM](./chapters/initial.md "Primeiros passos com o VIM")
  - [Formando comandos no VIM](./chapters/initial.md#formando-comandos-no-vim "Formando comandos no VIM")
- [Edição de texto](./chapters/editing.md "Edição texto")
  - [Abrindo um arquivo](./chapters/editing.md#abrindo-um-arquivo "Abrindo um arquivo")
  - [Alternando entre arquivos](./chapters/editing.md#alternando-entre-arquivos "Alternando entre arquivos")
  - [Inserindo texto](./chapters/editing.md#entrando-no-modo-de-inserção "Inserindo texto")
  - [Movimentos do cursor](./chapters/editing.md#movendo-o-cursor "Movimentos do cursor")
  - [Salvando e fechando arquivos](./chapters/editing.md#salvando-ou-fechando-arquivos "Salvando e fechando arquivos")
  - [Salvar como...](./chapters/editing.md#salvar-como "Salvar como...")
  - [Deletando texto](./chapters/editing.md#comandos-para-deletar "Deletando texto")
  - [Copiar e colar dentro do VIM](./chapters/editing.md#copiar-e-colar "Copiar e colar dentro do VIM")
  - [Recortar e colar dentro do VIM](./chapters/editing.md#recortar-e-colar-comando-put "Recortar e colar dentro do VIM")
  - [Replace](./chapters/editing.md#substituir-replace "Replace")
  - [Replace em massa usando o operador de pesquisa](./editing.md#substituir-em-massa "Replace em massa usando o operador de pesquisa")
  - [Desfazendo as coisas](./editing.md#desfazendo-as-coisas "Desfazendo as coisas")
  - [Buscar texto dentro do arquivo](./chapters/editing.md#pesquisando-em-um-arquivo "Buscar texto dentro do arquivo")
- [Executando comandos externos](./chapters/external_comands.md#executando-comandos-externos "Executando comandos externos")
- [Dicas uteis](./chapters/util.md "Comandos e dicas uteis")
  - [Criando Marcas](./chapters/util.md#marcas "Criando Marcas")
  - [Criando Folders (ou dobras no texto)](./chapters/util.md#folders "Criando Folders (ou dobras no texto)")
- [Personalizando o VIM](./chapters/personalize.md "Personalizando o VIM")
  - [Não precisar setar configurações sempre](./personalize.md#não-precisar-setar-configurações-sempre "Não precisar setar configurações sempre")
  - [Comandos e atalhos personalizados](./chapters/personalize.md#comandos-e-atalhos-personalizados "Comandos e atalhos personalizados")
  - [Mudando o tema](./chapters/personalize.md#mudando-o-tema "Mudando o tema")
  - [Adicionando sintaxes](./chapters/personalize.md#adicionando-sintaxes "Adicionando sintaxes")
- [Plugins](./chapters/plugins.md "Adicionando plugins")
  - [Instalando plugins no VIM](./chapters/plugins.md#instalando-os-plugins-com-vundle "Instalando plugins no VIM")
  - [Removendo plugins](./chapters/plugins.md#removendo-plugins-com-vundle "Removendo plugins")
  - [Alguns plugins maneiros](./chapters/suggestions.md#alguns-plugins-maneiros "Alguns plugins maneiros")
  - [Temas legais](/chapters/suggestions.md#temas-legais "Temas legais")
  - [Comandos uteis no .vimrc](./chapters/suggestions.md#comandos-uteis-no-vimrc "Comandos uteis no .vimrc")
- [Trabalhando em Janelas dentro do VIM](./chapters/windows.md "Trabalhando em Janelas dentro do VIM")
  - [Dividindo em janelas](./chapters/windows.md#dividindo-em-janelas "Dividindo em janelas")
  - [Pulando de uma janela para outra](./windows.md#pulando-de-uma-janela-para-outra "Pulando de uma janela para outra")
  - [Fechando janelas](./chapters/windows.md#fechar-janelas "Fechando janelas")
