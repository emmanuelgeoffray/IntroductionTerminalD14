# IntroductionTerminalD14
Compte rendu de l'introduction au terminal


Mathilde, Léo, Léontine : 

# *COURS > le Terminal*

q = quit 
d = supprimer
.. = retour à la commande précédente
:w = sauvegarder
:q = quitter le terminal

* **Les trucs en LS (list directory contents)** **List in long format**
ls = Liste des elements présents dans l'élément selectionné
ls-s = Plus lisible
ls -lai = Plus d'informations
ls -laih = Plus d'informations, human readable 
*La taille du dossier passe en Ko*
ls-a = Liste des fichiers cachés

     ![](https://i.imgur.com/4fbskQo.png)



* **Les trucs en CD (change directory)**
CD = Change Directory, changer de dossier.
cd .. = Revenir d'un dossier en arrière
cd ../.. = Revenir de deux dossiers en arrière
*Exemple = cd Documents, nous emmène au dossier Documents*

* **Les trucs en CAT (catenate)**
cat = affiche les dossiers précédents
cat bash_history = Affiche les recherches précédentes

![](https://i.imgur.com/Nnc8AJQ.png)



* **Les trucs en VIM (Vi IMproved)**
VIM c'est l'éditeur de texte présent dans la console.
Pour l'utiliser, et créer un fichier texte, on tape
*vim nomdufichier.txt*
Il y a deux modes, un mode "édition", ou "insert" et un mode "normal".
On accède au mode "insert" pour pouvoir insérer des caractères dans le texte avec la touche *i*. On revient dans le monde normal avec la touche *ESC*.
Dans le mode normal, on tape des commandes comme dans la console classique.

*cw* = pour changer word, permet de changer un mot.
*dw* = pour delete word, permet de supprimer un mot.
*dd* = pour delete, permet de supprimer une ligne.
*u* = pour undo, permet d'annuler la dernière action.
*CTRL R* = pour redo, permet de "refaire" la dernière action.

*:w* = pour write, permet d'enregistrer le fichier.
*:q* = pour quit, permet de quitter vim+revenir à la console.
*:wq* = pour write+quit fait les deux.

Il y a un guide intégré dans vim, il faut entrer la commande *vimtutor*. Compter une vingtaine de minutes pour suivre l'intrégralité du guide.

 ![](https://i.imgur.com/Gqmdmb3.png)


* **Les trucs en MAN (Manual)**
La commande MAN permet d'afficher le manuel d'aide.
*man ls*
*man*

* **Les trucs en GREP (globally search a regular expression and print)**
La commande GREP permet de faire une recherche à partir de critères. 
Exemple de recherche dans un à dossier à partir de certaines lettres :
*ls - lai | grep ocum*


* **Important : 2CB le poisson**
Il est en pleine forme et écoute attentivement ce cours. Dire qu'il va mourir bientôt c'est des *FAKE NEWS*

 ![](https://i.imgur.com/mSBUURW.jpg)
