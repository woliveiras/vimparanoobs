# Comandos e dicas uteis

## Marcas

Marcas são como um [teleport](http://www.wowhead.com/spell=48020/demonic-circle-teleport) ;D

Você deixa configurado um ponto com uma marca e depois pode voltar a ela ou utilizar para outras coisinhas legais.

Criando a marca:

`ma`    - A marca `a` foi criada onde o cursor estiver

Imagine que esteja em outra parte do texto. Para voltar basta rodar: ``a`

## Coisas legais de se fazer com marcas

Marque um local e delete até ele com 

```
d'marca
```

Criar uma marca Global (um ponto onde você pode voltar até mesmo pulando de outro arquivo):

`mA`   - Onde m define a marca A. Com A maiusculo podemos acessar de qualquer local

## Folders

Podemos pegar todo um bloco e ocultar ele, como dobrar uma parte do texto. Ao utilizar um folder de 10 linhas, por exemplo, o texto ficará com:

```
+-- 10 linhas -------------------------------------------------------------
```

Para isso faríamos:

```
xf10j
```

Para abrir novamente essas linhas, cambiamos o cursor até o local com `+-- 10...` e executar:

```
zo
```

Uma maneira mais fácil de criar os folders é entrando no modo visual (v), selecionando o bloco e pressionando `zf`.

Isso vai criar um folder na seleção ativa.

Comandos:

`zfap`  - Cria uma dobra para o parágrafo atual
`zf/palavra` - Cria uma dobra até a "palavra"
`zo`    - Abre a dobra onde o cursor estiver
`zR`    - Abre todas as dobras do arquivo atual
`zc`    - Fecha a dobra onde o cursor estiver
`zd`    - Apaga o folder (o conteúdo não é apagado)
`zj`    - Desce até a próxima dobra
`zk`    - Sobe até a próxima dobra
