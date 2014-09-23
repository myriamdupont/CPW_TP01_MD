#INTALLER SUBLIME TEXT 3

* * *

**Note:** Quand des raccourcis commençant par `CTRL`sont signalés, il convient de remplacer `CTRL`par `CMD`si on traville sur Mac. 

* * *

##1. Télécharger ST3
Rendez-vous sur le site de Sublime Text 3 : [http://www.sublimetext.com/3](http://www.sublimetext.com/3)

- Pour Windows : cliquer sur le lien [Windows](http://c758482.r82.cf2.rackcdn.com/Sublime%20Text%20Build%203065%20Setup.exe) (le 2e) => Sublime Text Build 3065 Setup.exe
- Pour Mac : cliquer sur le lien [OS X](http://c758482.r82.cf2.rackcdn.com/Sublime%20Text%20Build%203065.dmg) (le 1er) => Sublime Text Build 3065.dmg

##2. Installer ST3
Exécuter le fichier .exe récupéré (double-cliquer dessus)
   
#CONFIGURER SUBLIME TEXT 3

##1. Installer Package Control
*Package Control* est une extension de Sublime Text (ST) qui permet de trouver, d’installer et de maintenir à jour des packages pour ST.

###1.1. Télécharger Package Control
1. Rendez-vous sur le site [https://sublime.wbond.net/](https://sublime.wbond.net/)
2. Cliquer sur le bouton vert `Install Now`

###1.2. Installer Package Control
1. Copier le code qui se trouve dans la fenêtre « SUBLIME TEXT 3 »
2. Ouvrir ST
3. Choisir dans le menu : `View` > `Show Console`
4. Coller le code dans la ligne tout en bas puis `Enter`
5. Attendre que ST se connecte => il le fait

##2. Installer des packages (procédure générale)

###2.1. Voir la liste des packages disponibles
1. `CTRL`+`MAJ`+`P` pour avoir la liste des commandes disponibles
2. Taper *« list »* => choisir `Package Control: List Packages`
3. On voit apparaître la fenêtre de *Package Control* avec, dedans, la liste des packages installés

###2.2. Intaller un package
La procédure est la même pour tous les packages qu’on souhaite installer.
On utilise la commande `Package Control: install Package` de ST et on choisit dans la liste le package qu’on souhaite installer.

Procédure détaillée :

1. `CTRL`+`MAJ`+`P` pour avoir la liste des commandes disponibles 
2. Taper *« instal »* => choisir `Package Control: Install Package`
3. On voit apparaître la fenêtre de *Package Control* avec, dedans, la liste des packages non encore installés, qu’on peut donc installer
3. Taper un des mots constituant le nom du package qu’on veut installer => il le propose dans la liste => le choisir, il l’installe

###2.3. Quelques package intéressants pour démarrer
- **Side Bar Enhancements**
	* Permet d’avoir dans un menu latéral *(side bar)* la liste des dossiers et fichiers cotenus dans le dossier qu’on a ouvert
	* Permet aussi, quand on choisit un fichier  dans la *side bar*, d’avoir un menu contextuel plus complet avec, notamment, l’option `open in browser`, qui permet d’ouvrir directement le fichier dans un navigateur sans devoir quitter ST. (N.B. On peut chosir le navigateur avec lequel ST va ouvrir le fichier en modifiant les préférences de ST, voir plus loin).
	* Installation : 
		1. `CTRL`+`MAJ`+`P`
		2. Taper *« instal »* => choisir `Package Control: Install Package`
		3. Taper *« sidebar »* => choisir `SideBarEnhancements`
	* Utilisation :
		- la *side bar* s’ouvre directement au démarrage de ST dès lors qu’on ouvre un dossier contenant plusieurs fichiers ;
		- Sinon, dans le menu, choisir l’option `View` > `Side Bar`> `Show Side Bar`
- **Markdown Preview**
	* Permet d’afficher des fichiers balisés en markdown dans un navigateur (cette extension exporte le fichier markdown ouvert en HTML et l’ouvre directement dans le navigateur)
	* Installation :
		1. `CTRL`+`MAJ`+`P`
		2. Taper *« instal »* => choisir `Package Control: Install Package`
		3. Taper *« markdown »* => choisir `Markdown Preview`
	* Utilisation :
		1. Vous êtes dans ST avec un fichier .md ouvert
		2. `CTRL`+`MAJ`+`P`
		3. Taper *« markdown »* => choisir `Markdown Preview: Preview in Browser` puis `markdown`dans la 2e liste fournie
- **All Auto Complete**
	* Permet de faire de l’auto-complétion
	* Installation : 
		1. `CTRL`+`MAJ`+`P`
		2. Taper *« instal »* => choisir `Package Control: Install Package`
		3. Taper *« complete »* => choisir `All Auto Complete`
- **Emmet**
	* Permet d’utiliser des raccourcis et des alias, voir [Emmet Sheat Sheet](http://docs.emmet.io/cheat-sheet/))
	* Installation : 
		1. `CTRL`+`MAJ`+`P`
		2. Taper *« instal »* => choisir `Package Control: Install Package`
		3. Taper *« emmet »* => choisir `Emmet`
	* Utilisation :   
		1. Pour HTML :
			* Permet de taper rapidement des balises ou des blocs de balises HTML tout faits
			* *Comment ?* On tape des expressions raccourcies, ou une suite de balises séparées par des opérateurs (quantificateus, sélecteurs CSS, etc.) + `TAB`
				- Ex. a + `TAB`
				- Ex.	: html:5 + `TAB`, ou `!` + `TAB`
				- Ex. : ul>li*5 + `TAB` 
			* Voir [Emmet Sheat Sheet](http://docs.emmet.io/cheat-sheet/) pour les possibilités détaillées  
		2. Pour CSS :
			* Permet de taper une propriété CSS rapidement
			* *Comment ?* On tape le nom de la propriété raccourcie + `TAB`
			* Voir [Emmet Sheat Sheet](http://docs.emmet.io/cheat-sheet/) pour les possibilités détaillées
- **Sublime Codeintel**
	*Permet aussi de faire de l’auto-complétion
- **AdvencedNewFile**
	* Permet de générer des fichiers/dossiers en entrant un chemin
	* Installation : 
		1. Télécharger le zip ici : [skuroda/Sublime-AdvancedNewFile](https://github.com/skuroda/Sublime-AdvancedNewFile) (Car plus disponnible depuis le package controle il me semble)
		2. Suivez les instructions données sur cette même page
	* Utilisation : 
		* `ctrl + alt + n` => entrez un chemin ou un nom de fichier, si les dossiers n'existent pas, ST va les créer
- **etc.**
		  
##3. Changer les préférences générales de ST
1. Récupérer les préférences par défaut de ST pour pouvoir les modifier :
	* Choisir dans le menu `Sublime Text`> `Preferences` > `Settings - Default`
	* Récupérer les préférences par défaut : tout sélectionner (`CTRL`+A), copier (`CTRL`+C)
	* On va coller ce contenu dans Settings - User
	
2. Enregistrer nos préférences dans le fichier des préférences de l’utilisateur :
	* Choisir dans le menu `Sublime Text`> `Preferences` > `Settings - User`
	* Initialiser (ou réinitialiser) si nécessaire les préférences de l’utilisateur en y insérant les préférences par défaut : on sélectionne tout (pour écraser) (`CTRL`+A), on colle les préférences par défaut récupérées à l’étape 1 (`CTRL`+V), on sauve (`CTRL`+S)
	* Opérer dans le fichier ainsi obtenu les modifications souhaitées, par exemple :
		- Changer la police : `CTRL`+F : font => "font_face": "consolas", (ou "courrier new")
		- Passage à la ligne : `CTRL`+F : wrap => "word_wrap": "true",
		- Convertir TAB en espaces : `CTRL`+F : translate => "translate_tabs_to_spaces": true
				
##4. Changer les préférences d’un package installé

Il s’agit de la même procédure que pour changer les préférences générales de ST, si ce n’est qu’on modifie cette fois le fichier *Settings - User* du package souhaité (par exemple *Side Bar*) qui se trouve dans *Package Settings*, et non plus le fichier *Settings - User*  de ST (qui se trouvait dans *Preferences*).

On utilise cette procédure pour, par exemple, changer le navigateur par défaut avec lequel ST va ouvrir notre fichier (quand on choisit `open in browser` dans la *Side Bar*).

En détail, cela donne dans ce cas :

1. Récupérer les préférences par déafut du package *Side Bar* pour pouvoir les modifier :
	* Choisir dans le menu `Sublime Text`> `Package Settings` > `Side Bar`> `Settings - Default`
	* Récupérer les préférences par défaut : tout sélectionner (`CTRL`+A), copier (`CTRL`+C)
	* On va coller ce contenu dans Settings - User
	
2. Enregistrer nos préférences dans le fichier des préférences de l’utilisateur :
	* Choisir dans le menu `Sublime Text`> `Package Settings` > `Side Bar`> `Settings - User`
	* Initialiser (ou réinitialiser) si nécessaire les préférences de l’utilisateur en y insérant les préférences par défaut : on sélectionne tout (pour écraser) (`CTRL`+A), on colle les préférences par défaut récupérées à l’étape 1 (`CTRL`+V), on sauve (`CTRL`+S)
	* Opérer dans le fichier ainsi obtenu les modifications souhaitées, par exemple :
		- Changer navigateur par défaut : `CTRL`+F : browser => "default_browser": "firefox"


##5. Quelques raccourcis utiles

1. `CTRL`+S
	* Enregistre le fichier
	
2. `CTRL`+F
	* Permet de rechercher une ou plusieurs occurrences d’un mot ou d’une expression

3. `CTRL`+A
	* Sélectionne tout
	
4. Sélection puis `CTRL`+C
	* Copie la sélection
	
5. Sélection puis `CTRL`+X
	* Coupe la sélection
	
6. Curseur positionné à l’endoroit choisi puis `CTRL`+V
	* Colle la sélection précédememnt copiée

7. Sélection puis `CTRL`+D
	* Permet de sélectionner toutes les occurrences suivantes d’une sélection
	* Rend possible l’édition multiple

8. `ALT` + Souris : 
	* Rend possible la sélection en colonne

9. `CTRL`+`SHIFT`+`W`
	* Permet d’encadrer une sélection avec une balise HTML
	
10. `CTRL`+`MAJ`+`P`
	* Donne la liste des commandes disponibles 
	* => quand on tape des mots de ce qu’on veut, il complète (logique floue)  
	et on a la liste de ce qui contient ces mots-là qui apparaît
	* => `ENTER` pour choisir la première proposition
	* => flèche pour se balader dans la liste et `ENTER`quand on est sur celle qu’on veut


