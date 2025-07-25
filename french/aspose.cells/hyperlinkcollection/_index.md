---
title: HyperlinkCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 830
url: /fr/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection classe
Encapsule une collection de [`Hyperlink`](/cells/python-net/fr/aspose.cells/hyperlink) objets.



Le type HyperlinkCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells/hyperlinkcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add(self, first_row, first_column, total_rows, total_columns, address)`](/cells/python-net/fr/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | Ajoute un lien hypertexte vers une cellule spécifiée ou une plage de cellules.|
| [`add(self, cell_name, total_rows, total_columns, address)`](/cells/python-net/fr/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | Ajoute un lien hypertexte vers une cellule spécifiée ou une plage de cellules.|
| [`add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip)`](/cells/python-net/fr/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | Ajoute un lien hypertexte vers une cellule spécifiée ou une plage de cellules.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells/hyperlinkcollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.hyperlink) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Get Hyperlinks Collection
hyperlinks = worksheet.hyperlinks
# Adding a hyperlink to a URL at "A1" cell
hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Saving the Excel file
workbook.save("book1.xls")

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`Hyperlink`](/cells/python-net/fr/aspose.cells/hyperlink)
