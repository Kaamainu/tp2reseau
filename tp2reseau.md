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



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTc1ODg0MTEwLC0xNTY5ODIxMzQ0LDYwNT
k1NDYyMiw5NDQ5MTMwODFdfQ==
-->