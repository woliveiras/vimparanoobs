# Dicas de VIM para Noobs

> Sinta-se hackudo

## Sumário

- [Por que desse projeto](#por-que-desse-projeto)
- [Introdução](#introdução)
- [Como contribuir com o projeto](#como-contribuir-com-o-projeto)

## Por que desse projeto

Criei esse repositório com o objetivo de ser um local para guardar minhas anotações enquanto aprendo a usar o editor [VIM](http://www.vim.org/).

Com o passar do tempo o repositório ficou um [pouco grande](https://github.com/woliveiras/vimparanoobs/tree/master) e meio difícil de dar manutenção. Para facilitar minha vida e a de quem utiliza esse guia, transformei isso aqui em um [GitBook](https://www.gitbook.com/), porém utilizando meu próprio repositório com o [GitBookIO](https://github.com/GitbookIO/gitbook). - Dica do [Jota Teles](https://github.com/woliveiras/vimparanoobs/issues/1).

Se tiver alguma dica legal de uso do VIM, [manda pra mim!](mailto:w.oliveira542@gmail.com). :D

Leia o conteúdo inteiro no [Gitbook](http://woliveiras.com.br/vim-para-noobs/livro/)

## Introdução

**O que é VIM?**

Se você caiu nesse repositório e nem mesmo sabe o que é [VIM](http://www.vim.org/), da uma olhada [aqui](https://woliveiras.com.br/posts/Comecando-com-o-editor-de-texto-VIM/), [aqui](http://aurelio.net/vim/vi-vim-venci.html) e, se quiser baixar um livro legal sobre o editor, olha [aqui](https://code.google.com/p/vimbook/downloads/list).

**Por que usar VIM?**

Pra se sentir Hackudo/Hackero/Hackerzaum/Monstro das programaçaum/pra parecer Hacker de filme, etc

Quem olhar você digitando texto nessa tela:

![VIM](./images/vim-hackudo.gif "Imagem do editor VIM com um arquivo aberto.")


Vai te achar um monstro das hackeragem, o próprio [Kevin Mitnick](https://en.wikipedia.org/wiki/Kevin_Mitnick "Kevin Mitnick, o Hackudo monstraum.").

Eu decidi testar o VIM quando, em um [Meetup](meetup.com/ "Site meetup.com."), vi um cara escrever a seguinte linha de texto no Terminal:

```
sufocar cara_da_frente
```

Pressionar um `ESC` e digitar `:wq` e o cara que estava sentado na frente dele começou a ficar sem ar!

Isso foi incrível cara.

Me mostrou os poderes do lado negro da força. Eu pensei: *"Preciso de todo esse poder!"*

**Brincadeira**

Muita gente diz que usar o VIM é mais produtivo do que outros editores como o Sublime (:heart:). Então eu resolvi testar e tirar minhas conclusões de com qual editor vou me dar melhor.

*Quem sabe mais pra frente eu abandone de vez os outros editores.* ;D

## Como contribuir com o projeto

Caso você encontre algum erro ou tenha alguma sugestão, pode contribuir comentando direto na caixa de comentários que aparece em cada sessão do GitBook ou abrir uma issue nesse repositório.

Esse projeto é Open Source, então você também pode botar a mão na massa para melhorar ele, mas para isso vai precisar configurar em sua máquina.

Recomento que, antes de efetuar alguma alteração, dê uma lida na documentação do [GitBookIO](https://github.com/GitbookIO/gitbook) para entender como tudo funciona.

**Configurando o GitBookIO**

Siga o passo a passo para configuração do seu ambiente de desenvolvimento com GitBookIO utilizando o manual oficial da ferramenta, [aqui](https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md).

Assim que tiver tudo configurado, execute o comando:

`gitbook install`

Na raiz desse projeto, para instalar as dependências do Vim para Noobs.

**Rodando local**

Basta utilizar o comando:

`gitbook serve`

**Adicionando uma nova sessão/capitulo**

Para adicionar uma nova sessão, devemos criar um arquivo Markdown dentro da pasta `chapters`. Esse arquivo deve possuir um nome que condiz com o seu conteúdo.

Em seguida basta adicionar a referência ao arquivo no `SUMMARY.md`.

Ex.:

`/SUMMARY.md`

- [Nova sessão](/chapters/nova-sessao.md)

Atente-se para que a nova sessão tenha um fluxo com o que o livro tem seguido.

Por exemplo: 

- Introdução
- Matando demonios com o VIM
- Primeiros passos

Não seria algo intuitivo a um iniciante no VIM, pois apresentaria muita magia negra de uma só vez antes mesmo de ensinar os primeiros passos com o editor.

Caso você não saiba onde colocar sua nova sessão, podemos conversar nas issues. Basta abrir e informar o que está fazendo.

**Escrevendo a página**

A escrita dos capitulos é simples. É puro Markdown.

Caso você não saiba Markdown, recomendo dar uma olhada nesse [link](https://daringfireball.net/projects/markdown/syntax).

**Enviando sua contribuição**

Assim que finalizar suas alterações, envie um [Pull Request](https://help.github.com/articles/creating-a-pull-request/) e aguarde. :)

Não se preocupe com a parte de build e enviar para produção. Isso acontece depois da revisão de suas alterações.
