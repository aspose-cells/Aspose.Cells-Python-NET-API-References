---
title: LightCellsDataHandler classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1030
url: /fr/aspose.cells/lightcellsdatahandler/
is_root: false
---
##  LightCellsDataHandler classe
Représente le gestionnaire de données de cellules pour lire des feuilles de calcul volumineuses en mode léger.



Le type LightCellsDataHandler expose les membres suivants :

###  Méthodes
| Méthode| Description|
| :- | :- |
| [start_sheet](/cells/python-net/fr/aspose.cells/lightcellsdatahandler/start_sheet/#aspose.cells.Worksheet) | Commence à traiter une feuille de calcul.|
| [start_row](/cells/python-net/fr/aspose.cells/lightcellsdatahandler/start_row/#int) | Se prépare à traiter une ligne.|
| [process_row](/cells/python-net/fr/aspose.cells/lightcellsdatahandler/process_row/#aspose.cells.Row) | Commence à traiter une ligne.|
| [start_cell](/cells/python-net/fr/aspose.cells/lightcellsdatahandler/start_cell/#int) | Se prépare à traiter une cellule.|
| [process_cell](/cells/python-net/fr/aspose.cells/lightcellsdatahandler/process_cell/#aspose.cells.Cell) | Commence à traiter une cellule.|



###  Remarques

Lors de la lecture d'un classeur avec ce mode, [`LightCellsDataHandler.start_sheet`](/cells/python-net/fr/aspose.cells/lightcellsdatahandler/start_sheet) sera vérifié lors de la lecture de chaque feuille de calcul du classeur.
Pour une feuille, si [`LightCellsDataHandler.start_sheet`](/cells/python-net/fr/aspose.cells/lightcellsdatahandler/start_sheet) donne vrai, alors toutes les données et propriétés des lignes/cellules de cette feuille seront vérifiées
et traités par la mise en œuvre de cette interface. Pour chaque ligne, le [`LightCellsDataHandler.start_row`](/cells/python-net/fr/aspose.cells/lightcellsdatahandler/start_row) sera appelé pour vérifier si elle doit être traitée.
Si une ligne doit être traitée, les propriétés de cette ligne seront lues en premier et l'utilisateur pourra accéder à ses propriétés par [`LightCellsDataHandler.process_row`](/cells/python-net/fr/aspose.cells/lightcellsdatahandler/process_row).
si les cellules de la ligne doivent également être traitées, alors [`LightCellsDataHandler.process_row`](/cells/python-net/fr/aspose.cells/lightcellsdatahandler/process_row) devrait renvoyer vrai, puis [`LightCellsDataHandler.start_cell`](/cells/python-net/fr/aspose.cells/lightcellsdatahandler/start_cell) sera
appelé pour chaque cellule existante de cette ligne pour vérifier si une cellule doit être traitée. Si une cellule doit être traitée,
alors [`LightCellsDataHandler.process_cell`](/cells/python-net/fr/aspose.cells/lightcellsdatahandler/process_cell) sera appelé pour traiter la cellule par la mise en œuvre de cette interface.


Veuillez noter que l'utilisateur ne doit opérer que sur les valeurs et les propriétés de l'objet Row/Cell actuel fourni par la méthode correspondante.
Étant donné que les données des cellules sont lues à partir du fichier modèle en continu, la plupart des autres objets peuvent être réinitialisés/mis à jour ultérieurement.
une fois les données des cellules chargées. Ainsi, lorsque l'utilisateur utilise d'autres objets dans cette implémentation,
ces opérations peuvent ne pas être en mesure d’affecter les objets existants dans le classeur. Ou pire encore, ces opérations peuvent
provoquer des données incohérentes dans le classeur, puis provoquer un problème ou une exception inattendue plus tard.
Ainsi, pour tous les autres objets tels que les formes, la largeur et les styles de colonnes, les mises en forme conditionnelles, ... etc.,
veuillez ne les utiliser dans aucune des méthodes de cette implémentation.
Au lieu de cela, veuillez les gérer une fois le classeur créé.

###  Voir également
* module [`aspose.cells`](..)
