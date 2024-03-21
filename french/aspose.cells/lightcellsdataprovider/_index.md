---
title: LightCellsDataProvider classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1040
url: /fr/aspose.cells/lightcellsdataprovider/
is_root: false
---
##  LightCellsDataProvider classe
Représente le fournisseur de données pour enregistrer des fichiers de feuille de calcul volumineux en mode léger.



Le type LightCellsDataProvider expose les membres suivants :

###  Méthodes
| Méthode| Description|
| :- | :- |
| [start_sheet](/cells/python-net/fr/aspose.cells/lightcellsdataprovider/start_sheet/#int) | Commence à enregistrer une feuille de calcul.|
| [next_row](/cells/python-net/fr/aspose.cells/lightcellsdataprovider/next_row/#) | Obtient la ligne suivante à enregistrer.|
| [start_row](/cells/python-net/fr/aspose.cells/lightcellsdataprovider/start_row/#aspose.cells.Row) | Commence à enregistrer les données d'une ligne.|
| [next_cell](/cells/python-net/fr/aspose.cells/lightcellsdataprovider/next_cell/#) | Obtient la cellule suivante à enregistrer.|
| [start_cell](/cells/python-net/fr/aspose.cells/lightcellsdataprovider/start_cell/#aspose.cells.Cell) | Commence à enregistrer les données d'une cellule.|
| [is_gather_string](/cells/python-net/fr/aspose.cells/lightcellsdataprovider/is_gather_string/#) |Vérifie si la valeur de chaîne actuelle de la cellule doit être rassemblée dans un pool global.|



###  Remarques

Lors de l'enregistrement d'un classeur avec ce mode, [`LightCellsDataProvider.start_sheet`](/cells/python-net/fr/aspose.cells/lightcellsdataprovider/start_sheet) sera vérifié lors de l'enregistrement de chaque feuille de calcul du classeur.
Pour une feuille, si [`LightCellsDataProvider.start_sheet`](/cells/python-net/fr/aspose.cells/lightcellsdataprovider/start_sheet) donne vrai, alors toutes les données et propriétés doivent être enregistrées pour les lignes/cellules de cette feuille
seront fournis par la mise en œuvre de cette interface.
En premier lieu, [`LightCellsDataProvider.next_row`](/cells/python-net/fr/aspose.cells/lightcellsdataprovider/next_row) sera appelé pour que l'index de ligne suivant soit sauvegardé.
Si un index de ligne valide est renvoyé (l'index de ligne doit être dans l'ordre croissant pour que les lignes soient enregistrées),
alors un objet Row représentant cette ligne sera fourni par [`LightCellsDataProvider.start_row`](/cells/python-net/fr/aspose.cells/lightcellsdataprovider/start_row) pour que l'implémentation définisse ses propriétés.
Pour une ligne, [`LightCellsDataProvider.next_cell`](/cells/python-net/fr/aspose.cells/lightcellsdataprovider/next_cell) sera vérifié en premier.
Si un index de colonne valide est renvoyé (l'index de colonne doit être dans l'ordre croissant pour toutes les cellules de la ligne actuelle),
puis un objet Cell représentant cette cellule sera fourni par [`LightCellsDataProvider.start_cell`](/cells/python-net/fr/aspose.cells/lightcellsdataprovider/start_cell) pour implémentation afin de définir ses données et propriétés.
Après [`LightCellsDataProvider.start_cell`](/cells/python-net/fr/aspose.cells/lightcellsdataprovider/start_cell), la cellule sera enregistrée directement dans le fichier de feuille de calcul résultant.
Ensuite, la cellule suivante sera vérifiée et traitée.


Veuillez noter que l'utilisateur ne doit mettre à jour que les valeurs et les propriétés de l'objet Row/Cell actuel fourni par la méthode correspondante.
Étant donné que les données des cellules sont écrites dans le fichier résultant en continu, la plupart des autres objets peuvent avoir été écrits
au fichier résultant, ou ont été rassemblés et écrits des données globales pour eux. Ainsi, lorsque l'utilisateur met à jour d'autres objets
lors de la sauvegarde des données des cellules, ces opérations peuvent ne pas affecter les données enregistrées. Ou pire encore, ces opérations peuvent
provoquer l'enregistrement de données incohérentes dans le fichier résultant et finalement corrompre le fichier.
Ainsi, pour tous les autres objets tels que les formes, la largeur et les styles de colonnes, les mises en forme conditionnelles, ... etc.,
veuillez ne les utiliser dans aucune des méthodes de cette implémentation.
Au lieu de cela, veuillez les gérer et les ajuster à l'état final avant d'appeler la méthode "Enregistrer" du classeur.

###  Voir également
* module [`aspose.cells`](..)
