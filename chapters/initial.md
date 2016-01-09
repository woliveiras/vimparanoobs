# Basico

## Instalação do VIM

Em sistemas baseados no Debian

```bash
$ sudo apt-get install vim
```

[Em outros sistemas operacionais.](http://www.vim.org/download.php "Página de Download oficial.")

## Aprender a usar o básico

Rode no Terminal

```
$ vimtutor
```
## Não esquecer

Se usar o comando :h  ou :help será aberto um helper. Quando  encontrar uma referência a um comando com letra maiúscula, é letra maiúscula mesmo (`SHIFT + Letra`).

Ex.: G - para pular para o final do arquivo.

Você deve pressionar o `SHIFT+G`.

Todo comando (operação) deve ser executado no modo visual. Portanto acosume-se a digitar o texto e pressionar `ESC` para poder executar o comando.

## Formando comandos no VIM

operator count motion

Onde:

operator - Comando
count    - Contador para repetir o mesmo comando
motion   - Movimento ou direção para onde executar

[Manipulando arquivos](./files.md "Manipulando arquivos").
