# Replace

## Substituição simples

Use `rx`, onde x é o novo caractere a ser inserido onde estiver o cursor.

Outra maneira é fazer com `R`. Executando dessa maneira, irá aparecer na barra inferior o alerta **-- REPLACE --**, então basta digitar a nova palavra.

## Substituir em massa

`:s/antiga/nova`      - Substitui a ocorrência de *antiga* para *nova* na mesma linha

`:#, # s/atiga/nova`  - Substitui a ocorrência desde # até # linha do arquivo (um range)

`:% s/antiga/nova`    - Substitui em todo o arquivo

`:% s/antiga/nova/gc` - Substitui no arquivo inteiro, mas solicita confirmação a cada ocorrência