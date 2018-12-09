# Adicionando sintaxes

O mesmo que acontece com os [temas](/mudando-o-tema.md) ocorre com as sintaxes das linguagens, algumas poderão ser facilmente instaladas com o Vundle, outras serão, também facilmente, instaladas manualmente.

Basicamente você poderia fazer isso em uma instalação manual:

```
cd ~/.vim/syntax
git clone arquivo_sintaxe
```

*Porém o Vundle também coloca esse tipo de arquivo dentro de `./vim/bundle`.*

E adicionar ao `.vimrc`

```
au FileType type call SyntaxFoo()
```

Para encontrar a sintaxe da sua linguagem basta dar uma Googlada: `vim syntax <language>`