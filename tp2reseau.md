*Marc BERNARD ; B1B*
#  **TP2** - Réseau 



***Table des matières***	
 - 
 - Exploration locale en solo
	 - 
	 - Affichage d'information sur la pile TCP/IP locale
		 - en ligne de commande
		 - En graphique (GUI : Graphical User Interface)
	-Modification des informations 

## Exploration Locale en solo

### Affichage d’information sur la pile TCP/IP locale

#### En ligne de commande

Pour voir ces informations, il faut ouvrir Windows PowerShell (dans mon cas car je suis sous windows).

Une fois l’interface ouverte, il suffit d’utiliser la commande « ipconfig /all » pour afficher les informations que l’on cherche. On obtient donc :

| | Interface WiFi | Interface Ethernet | 
|--|--|--| 
| Nom |Intel(R) Wireless-AC 9462 | Realtek PCIe GBE Family Controller |
| Adresse Mac | 7C-76-35-A9-92-F5 | 30-9C-23-91-CB-53 |
 IP | 10.33.0.31| X |
 Masque sousréseau | <![endif]--> 255.255.252.0 (/22) | X | 
 Adresse Réseau | 10.33.0.0/22 | X|
 Adresse Broadcast | 10.33.3.254/22 | X | 
 Adresse Passerelle | 10.33.3.253/22 | X

Pour l’interface Ethernet, l’adresse MAC et la seule information que l’on peut avoir car la carte Ethernet n’est pas connectée.

#### En graphique (GUI : Graphical User Interface)
Pour commencer faites un clique droit sur l'icône du Wi-Fi en bas à droite de votre barre tes tâches.
Vous obtenez normalement cela:
<img src="wifi.png">



Sélectionnez ensuite "Ouvrir les paramètres réseau et Internet".
La fenêtre ci dessous est à présent ouverte :


<img src="cliquedroit.png">

Sélectionnez "Centre Réseau et partage", cette fenêtre apparaît ensuite:
<img src="centrereseau.png">

Sélectionnez ensuite votre réseau Wi-fi, dans mon cas ce sera le Wi-fi d'Ynov.
Vous obtiendrez cela :

Choisissez ensuite le bouton "Détails..." pour avoir enfin la fenêtre avec les informations, ce qui donne :

Une Gateway est l'adresse IP par laquelle un hôte doit passer pour pouvoir communiquer avec un réseau extérieur.

#### Modification des informations

Pour changer votre IP ;
Comme montré précédemment il vous faut revenir à cette fenêtre et sélectionnez "Propriétés":


Ensuite il faut choisir " Protocole Internet version 4(TCP/IPv4)" puis prenez à nouveau "Propriétés":





Arrivé ici cocher la case «Utiliser l’adresse IP suivante : » puis vous avez ensuite à entrer l’IP souhaité qui correspondra à la nouvelle adresse d’hôte que vous aurez dans le réseau, par exemple ici on prend la première adresse d’hôte possible dans ce réseau. La dernière étant 10.33.0.252 car celle après est prise par la passerelle par défaut.

   
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTY5OTMwNjczNywtMTM5MzM2Mzc4MSwtMT
U2OTgyMTM0NCw2MDU5NTQ2MjIsOTQ0OTEzMDgxXX0=
-->