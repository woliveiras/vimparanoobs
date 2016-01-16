# Criando Folders (ou dobras no texto)

Podemos pegar todo um bloco e ocultar ele. É como dobrar uma parte do texto.

Ao criar um folder de 10 linhas, por exemplo, o texto ficará assim:

```
+-- 10 linhas -------------------------------------------------------------
```

Para isso faríamos:

```
xf10j
```

Para abrir novamente essas linhas, movemos o cursor até o local com `+-- 10...` e executamos:

```
zo
```

Uma maneira mais fácil de criar os folders é entrando no modo visual (`v`), selecionando o bloco e pressionando `zf`.

Isso vai criar um folder na seleção ativa.

Comandos:

`zfap`        - Cria uma dobra para o parágrafo atual

`zf/palavra`  - Cria uma dobra até a "palavra"

`zo`          - Abre a dobra onde o cursor estiver

`zR`          - Abre todas as dobras do arquivo atual

`zc`          - Fecha a dobra onde o cursor estiver

`zd`          - Apaga o folder (o conteúdo não é apagado)

`zj`          - Desce até a próxima dobra

`zk`          - Sobe até a próxima dobra