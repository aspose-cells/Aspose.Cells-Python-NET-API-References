---
title: méthode set_header
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 200
url: /fr/aspose.cells/pagesetup/set_header/
is_root: false
---
##  set_header(self, section, header_script) {#int-str}
Définit un script formatant l'en-tête d'un fichier Excel.



```python

def set_header(self, section, header_script):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| section | int | : Section gauche, 1 : Section centrale, 2 : Section droite.|
| header_script | str | Script de format d'en-tête.|
###  Remarques

Commandes de script :

| Commande| Description|
| :- | :- |
| &P| Numéro de page actuel|
| &N| Nombre de pages|
| &D| Date du jour|
| &T| Heure actuelle|
| &UN| Nom de la feuille|
| &F| Nom de fichier sans chemin|
| &"<FontName>"|Nom de la police, par exemple : &"Arial"|
| &"<FontName>, <FontStyle>"| Nom de la police et style de police, par exemple : &"Arial,Bold"|
| &<FontSize>| Taille de police. Si cette commande est suivie d'un nombre simple à afficher dans l'en-tête, il sera séparé de la hauteur de police par un espace.|
| &K<RRGGBB>| Couleur de police, par exemple (ROUGE) : &KFF0000|
| &G| Script d'image|

Par exemple : « &Arial,Bold&8Note d'en-tête »


###  Voir également
* module [`aspose.cells`](../../)
* classe [`PageSetup`](/cells/python-net/fr/aspose.cells/pagesetup)
