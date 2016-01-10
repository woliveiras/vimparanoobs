# Editando

## Abrindo um arquivo

```
$ vim caminho/arquivo
```

Caso esteja em um arquivo com referência a outro arquivo, você pode abrir o mesmo usando  ` CTRL-w-f` com o cursor sobre o caminho.

Ex.:

` ` `
/etc/hosts
` ` `

Se usar o comando  ` CTRL-w-f`, o VIM irá abrir o arquivo hosts.

## Entrando no modo de inserção

O VIM possui dois modos de operação:

- Modo de inserção: Modo para edição propriamente dita do texto.
- Modo visual: Modo onde as letras do teclado funcionam como comandos (operadores).

`i`   - Entra no modo de inserção no local onde o cursor se encontra

`I`   - Entra no modo de inserção no começo da linha

`a`   - Entra no modo de inserção na frente de onde o cursor se encontra

`A`   - Entra no modo de inserção no final da linha

`o`   - Adiciona uma linha abaixo de onde estiver o cursor e entra em modo de inserção

`O`   - Adiciona uma linha acima e entra em modo de inserção

`ESC` - Volta ao modo visual

*Todos os comandos devem ser digitados no __modo visual__.*

## Movendo o cursor

`h`: Esquerda

`j`: Baixo

`k`: Cima

`l`: Direita

---

Para ir ao final de um arquivo use: `G`

Para voltar ao topo: `gg`

Para mover ao final de uma palavra: `e`

Para mover ao final de uma palabra voltando o cursor: `ge`

Para mover até o começo da próxima palavra: `w`

Para mover até o começo de uma palavra voltando o cursor: `b`

Para mover ao pŕoximo caractere específico use: `f[caractere]`

Para mover ao começo de uma linha, use: `0`

Para mover ao final de uma linha, use: `$`

Para pular ao final do parágrafo: `}`

Para pular para o fechamento de um parentese/colchete/chaves: `%`

Para saber sua posição no documento: `CTRL+G`

Podemos voltar onde estávamos a partir de qualquer local fazendo: `numero_da_linha + G`

O VIM mantem um histórico de alterações e para mover o cursor até a ultima alteração use `g;`, para mover para a próxima na lista `g,`

## Salvando ou fechando arquivos

`:q`  - Sai sem salvar. Será solicitado confirmação se existirem alterações não salvas.

`:!q` - Sai sem salvar descartando as alterações

`:w`  - Salva o arquivo (escreve)

`:wq` - Salva e sai do arquivo

`:x`  - Salva e sai do arquivo

`ZZ`  - Salva e sai do arquivo

## Salvar como...

Se você estiver em um arquivo e desejar salvar criando um novo, pode usar algo parecido com um "Salvar como...".

Execute ` :w nome ou caminho/nome`.

Se quiser salvar e sair, pode usar o ` :wq nome ou caminho/nome`.

## Comandos para deletar

`x`  - Deleta o caractere onde o cursor estiver

`X`  - Deleta o caractere de trás do cursor

`dw` - Deleta a partir do cursor até o começo da próxima palavra

`d$` - Deleta do cursor até o fim da linha

`dd` - Deleta a linha iteira, incluindo o [enter] que ouver no final

`C`  - Deleta de onde o cursor estiver até o final da linha e entra em modo de inserção a partir dali

`ce` - Deleta do cursor até o final da palavra e entra em modo de inserção

## Alternando entre arquivos

Podemos abrir outro arquivo enquanto estamos no vim usando `:e nome ou caminho/nome`

Quando estamos editando mais de um arquivo podemos usar `CTRL+6` para alternar entre um e outro.

## Copiar e colar

`y`  - Para copiar e `p` para colar

`yy` - Para copiar uma linha inteira

A maneira mais fácil de fazer o copy & paste é entrar no modo visual (`v`), selecionar o texto e então pressionar o y.

## Recortar e colar (comando PUT)

Para recortar e colar use algum comando para exclusão (x, dd, dw, d$ ou algum comando formado por você), cambie até o local onde deseja salvar e use o comando `p`.

A ultima coisa deletada será inserida depois do cursor.

## Substituir (replace)

Use `rx`, onde x é o novo caractere a ser inserido onde estiver o cursor.

Outra maneira é fazer com `R`.

Executando dessa maneira irá aparecer na barra inferior o alerta: *-- REPLACE --*, então basta digitar a nova palavra.

## Substituir em massa

`:s/antiga/nova`      - Substitui a ocorrência de *antiga* para *nova* na mesma linha

`:#, # s/atiga/nova`  - Substitui a ocorrência desde # até # linha do arquivo (um range)

`:% s/antiga/nova`    - Substitui em todo o arquivo

`:% s/antiga/nova/gc` - Substitui no arquivo inteiro, mas solicita confirmação a cada ocorrência

## Desfazendo as coisas

`u`      - Desfaz a ultima alteração

`U`      - Desfaz todas as mudanças efetuadas em uma linha inteira

`CTRL+R` - Desfaz o ultimo u/U (refaz :P)

## Pesquisando em um arquivo

`/termo_a_ser_pesquisado` - Pesquisa para baixo do arquivo

`?/termo`                 - Pesquisa para cima do arquivo

`//`                      - Busca o ultimo termo pesquisado

`/palavra/+numero`        - Posiciona o cursor *numero* de linhas após a ocorrência da palavra

Ao entrar no modo de busca, o VIM deixa o */palavra* na barra inferior, então podemos usar:

`n` - Para a próxima ocorrência
`N` - Para a ocorrência anterior
