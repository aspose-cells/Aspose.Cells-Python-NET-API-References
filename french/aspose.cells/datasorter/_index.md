---
title: DataSorter classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 410
url: /fr/aspose.cells/datasorter/
is_root: false
---
##  DataSorter classe
Description sommaire pour DataSorter.



Le type DataSorter expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [keys](/cells/python-net/fr/aspose.cells/datasorter/keys) | Obtient la liste des clés du trieur de données.|
| [has_headers](/cells/python-net/fr/aspose.cells/datasorter/has_headers) | Indique si la plage comporte des en-têtes.|
| [key1](/cells/python-net/fr/aspose.cells/datasorter/key1) | Représente le premier index de colonne trié (position absolue, la colonne A est 0, B est 1, ...).|
| [order1](/cells/python-net/fr/aspose.cells/datasorter/order1) | Représente l'ordre de tri de la première clé.|
| [key2](/cells/python-net/fr/aspose.cells/datasorter/key2) | Représente le deuxième index de colonne trié (position absolue, la colonne A est 0, B est 1, ...).|
| [order2](/cells/python-net/fr/aspose.cells/datasorter/order2) | Représente l'ordre de tri de la deuxième clé.|
| [key3](/cells/python-net/fr/aspose.cells/datasorter/key3) | Représente le troisième index de colonne trié (position absolue, la colonne A est 0, B est 1, ...).|
| [order3](/cells/python-net/fr/aspose.cells/datasorter/order3) | Représente l'ordre de tri de la troisième clé.|
| [sort_left_to_right](/cells/python-net/fr/aspose.cells/datasorter/sort_left_to_right) |Vrai signifie que l'orientation du tri s'effectue de gauche à droite.<br/>Faux signifie que l'orientation du tri s'effectue de haut en bas.<br/> La valeur par défaut est false.|
| [case_sensitive](/cells/python-net/fr/aspose.cells/datasorter/case_sensitive) | Obtient et définit si la casse est respectée lors de la comparaison d'une chaîne.|
| [sort_as_number](/cells/python-net/fr/aspose.cells/datasorter/sort_as_number) | Indique si le tri doit porter sur tout ce qui ressemble à un nombre.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add_key(self, key, order)`](/cells/python-net/fr/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder) | Ajoute un index de colonne trié et un ordre de tri.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/fr/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-str) | Ajoute un index de colonne trié et un ordre de tri avec une liste de tri personnalisée.|
| [`add_key(self, key, type, order, custom_list)`](/cells/python-net/fr/aspose.cells/datasorter/add_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-any) | Ajoute un index de colonne trié et un ordre de tri avec une liste de tri personnalisée.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/fr/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-list) | Ajoute un index de colonne trié et un ordre de tri avec une liste de tri personnalisée.|
| [`sort(self, cells, start_row, start_column, end_row, end_column)`](/cells/python-net/fr/aspose.cells/datasorter/sort/#aspose.cells.cells-int-int-int-int) | Trie les données de la zone.|
| [`sort(self, cells, area)`](/cells/python-net/fr/aspose.cells/datasorter/sort/#aspose.cells.cells-aspose.cells.cellarea) | Trier les données de la zone.|
| [`sort(self)`](/cells/python-net/fr/aspose.cells/datasorter/sort/#) | Trier les données dans la plage.|
| [`clear(self)`](/cells/python-net/fr/aspose.cells/datasorter/clear/#) | Effacer tous les paramètres.|
| [`add_color_key(self, key, type, order, color)`](/cells/python-net/fr/aspose.cells/datasorter/add_color_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-aspose.pydrawing.color) | Ajoute une clé de tri par couleur.|



###  Exemple

```python
from aspose.cells import CellArea, SortOrder, Workbook

# Instantiate a new Workbook object.
workbook = Workbook("Book1.xls")
# Get the workbook datasorter object.
sorter = workbook.data_sorter
# Set the first order for datasorter object.
sorter.order1 = SortOrder.DESCENDING
# Define the first key.
sorter.key1 = 0
# Set the second order for datasorter object.
sorter.order2 = SortOrder.ASCENDING
# Define the second key.
sorter.key2 = 1
# Create a cells area (range).
ca = CellArea()
# Specify the start row index.
ca.start_row = 0
# Specify the start column index.
ca.start_column = 0
# Specify the last row index.
ca.end_row = 13
# Specify the last column index.
ca.end_column = 1
# Sort data in the specified data range (A1:B14)
sorter.sort(workbook.worksheets[0].cells, ca)
# Save the excel file.
workbook.save("outBook.xls")

```

###  Voir également
* module [`aspose.cells`](..)
