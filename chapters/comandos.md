# Formando comandos

A maneira de agilizar a utilização de comandos no Vim é criando-os de acordo com sua necessidade.

A forma de se executar os comandos segue o seguinte padrão:

**operator** **count** **motion**

Onde:

`operator` - Operador

`count`    - Contador para repetir o mesmo comando

`motion`   - Movimento ou direção para onde executar

Ex.:

```
d4$
```

Deleta 4 linhas até o final (`d`, deletar, `4`, contador, `$`, até o final da linha).