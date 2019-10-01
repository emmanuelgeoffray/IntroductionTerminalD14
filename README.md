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


                                                      
# **BOLIDE TIME**

 ![](https://i.imgur.com/7aKpIQl.gif)

<resume>Au cours de cette matinée, nous avons appris à être des petits hackeurs malins. Sur mac, nous avons utilisé le terminal, et sur PC, git bash. C'est super chouette, j'adore, c'est très utile.</resume>
<lol>Essayez dont la commande sudo -rl /*</lol>


* cd =  change directory
* ls =  liste directory
* cd + première lettre du document + tab = quick select du fichier
* . =  dossier dans lequel je suis 
* .. = dossier précédent
* cd ../.. =  Retour de 2 vers précédent
* cd documents/images = aller de dossier en dossier 

* ls -laih =   h =  human readable
* ( cmd -option 1 -option2 -option3 etc. OU cmd -option123 etc.)
* ( exemple de l'option i : intégrer tous les fichiers commençant par un . exemple .bash_history)
* cat .bash_history

* flèche du haut = retour sur dernière commande
* man ls = centre d’aide (donne toutes les options de la commande)
* Sortir d’une commande = q 
* cat =  décrire un document (pas un dossier)
* ctlr D =  kill task
* cat psd/less 
* alt maj L = |

* vim titre.txt = création d'un fichier texte
* vimtutor = tutoriel vim

* i = insert
* u = undo
* r = redo
* esc = retour mode normal
* :q = quitter
* :q! = quitter sans sauvegarder
* :wq = quitter avec sauvergarde

* grep = search
* cat bolide.txt | grech oli 
* (cherche oli dans le fichier bolide.txt)

* cat bolide.txt | wc -l >> bolide.txt
* (>> = append)

bonus:
* yes minh = minh minh minh minh minh minh minh minh 
* CTRL + C pour arrêter ouf...

> Patricio Gonzalez => tuto bash
> http://patriciogonzalezvivo.com/teaching.php
> https://github.com/patriciogonzalezvivo/Shell-Initiation


<merci>Ce compte rendu vous est fourni par le collectif le plus stylé et "swaginolant" (mot pas français très moche) : le Bolide</merci>

![](https://i.imgur.com/ZenTaxR.mp4)

