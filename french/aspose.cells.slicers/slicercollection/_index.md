---
title: SlicerCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 50
url: /fr/aspose.cells.slicers/slicercollection/
is_root: false
---
##  SlicerCollection classe
Spécifie la collection de tous les objets Slicer sur la feuille de calcul spécifiée.



Le type SlicerCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.slicers/slicercollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add(self, pivot, dest_cell_name, base_field_name)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-str) | Ajouter un nouveau segment en utilisant un tableau croisé dynamique comme source de données|
| [`add(self, pivot, row, column, base_field_name)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-str) | Ajouter un nouveau segment en utilisant un tableau croisé dynamique comme source de données|
| [`add(self, pivot, row, column, base_field_index)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-int) | Ajouter un nouveau segment en utilisant un tableau croisé dynamique comme source de données|
| [`add(self, pivot, dest_cell_name, base_field_index)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-int) | Ajouter un nouveau segment en utilisant un tableau croisé dynamique comme source de données|
| [`add(self, pivot, row, column, base_field)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-aspose.cells.pivot.pivotfield) | Ajouter un nouveau segment en utilisant un tableau croisé dynamique comme source de données|
| [`add(self, pivot, dest_cell_name, base_field)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-aspose.cells.pivot.pivotfield) | Ajouter un nouveau segment en utilisant un tableau croisé dynamique comme source de données|
| [`add(self, table, index, dest_cell_name)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-int-str) | Ajouter un nouveau slicer en utilisant ListObjet comme source de données|
| [`add(self, table, list_column, dest_cell_name)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-aspose.cells.tables.listcolumn-str) | Ajouter un nouveau slicer en utilisant ListObjet comme source de données|
| [`add(self, table, list_column, row, column)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-aspose.cells.tables.listcolumn-int-int) | Ajouter un nouveau slicer en utilisant ListObjet comme source de données|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/index_of/#aspose.cells.slicers.slicer-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/index_of/#aspose.cells.slicers.slicer-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`get(self, name)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/get/#str) | Obtient le slicer par le nom du slicer.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.slicers/slicercollection/binary_search/#aspose.cells.slicers.slicer) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
pivot.refresh_data()
pivot.calculate_data()
slicers = sheet.slicers
tableIndex = sheet.list_objects.add("A1", "C9", True)
table = sheet.list_objects[tableIndex]
# do your business
book.save("out.xlsx")

```

###  Voir également
* module [`aspose.cells.slicers`](..)
