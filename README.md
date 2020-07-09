# Dotfiles

## A quoi ça sert ?

Ce dépot sert à sauvegarder mes fichiers de configuration GNU/Linux au fur et à mesure de leur personnalisation.

Ces fichiers sont très souvent présents dans le répertoire d'accueil de l'utilisateur, quel que soit le système d'exploitation.

Par exemple :
- .tmux.conf (fichier de configuration de tmux)
- .vimrc (fichier de configuration de vim)

Le but est ici de retrouver sur toutes les machines que j'administre les mêmes fichiers de configuration afin de me sentir "chez moi" lorsque j'utilise un programme ou un environnement commun quelle que soit la machine sur laquelle je suis.

## Comment faire cela ?

Pour effectuer ce suivi, j'utilise le programme libre `chezmoi` décrit sur [son site web](https://www.chezmoi.io) ou son [repo github](https://github.com/twpayne/chezmoi).

Se référer à la documentaion du programme pour connaître les commandes à appliquer.

Ce programme est basé sur `git`.

Un autre programme assez similaire s'appelle [yadm](https://yadm.io/). Basé sur git également. A tester. Peut-être un peu moins difficile (mais rencontré plus tôt) au niveau de la syntaxe des templates. Un article y est consacré dans [Linux pratique n° 119](https://boutique.ed-diamond.com).

## Notes

Je ne souhaite pas pour l'instant "suivre" beaucoup de fichiers, ceci afin de me familiariser avec l'outil.
