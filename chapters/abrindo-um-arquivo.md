# Abrindo um arquivo

```
vim arquivo
```

ou

```
vim caminho/arquivo
```

## Abrindoa partir de caminhos dentro do arquivo

Caso esteja em um arquivo com referência a outro arquivo, você pode abrir o mesmo usando  ` CTRL-w-f` com o cursor sobre o caminho.

Ex.:

Considere que está lendo um arquivo e encontrar no meio do texto:

```
/etc/hosts
```

Se usar o comando  ` CTRL-w-f` em cima dessa linha, o Vim irá abrir o arquivo hosts.

## Abrindo o arquivo em uma linha específica

Conseguimos descobrir onde está uma palavra ou bloco fazendo o seguinte (no linux):

```
grep -n "palavra" arquivo
```

Será exibido no Terminal a linha com o termo pesquisado:

```
numero_da_linha:termo_pesquisado
```

Então você consegue fazer:

```
vim +numero_da_linha nome_do_arquivo
```

E ele abre direto na linha específica.

> OBS: Isso não é uma mágica do Vim, outros editores fazem a mesma coisa no Linux. ;)