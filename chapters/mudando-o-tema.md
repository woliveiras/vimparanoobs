# Mudando o tema

Para encontrar um  esquema de cores maneiro para o seu Vim, você pode acessar o site [vimcolors.com](http://vimcolors.com/).

Alguns temas tem suporte ao **Vundle**, portanto será o mesmo processo de instalação que os [plugins](./instalando-os-plugins-com-vundle.md).

Será necessário criar uma a pasta `~/.vim`, se a mesma ainda não existir.

Os temas podem ser clonados dentro de `~/.vim/colors` para melhor organização, porém o Vundle, por exemplo, coloca dentro de `./vim/bundle`.

Normalmente, na documentação do próprio tema tem um passo a passo de instalação, mas basicamente você sempre vai fazer:

```
cd ~/.vim/colors #Pasta com esquemas de cores
git clone esquemadecores.git
```

E adicionar a linha do esquema no seu `.vimrc`.

Ex. do [esquema de cores](https://github.com/sickill/vim-monokai) que eu uso atualmente:

```
colorscheme monokai
```
