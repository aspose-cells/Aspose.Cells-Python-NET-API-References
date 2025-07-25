---
title: ConditionalFormattingCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 280
url: /fr/aspose.cells/conditionalformattingcollection/
is_root: false
---
##  ConditionalFormattingCollection classe
Encapsule une collection de [`FormatCondition`](/cells/python-net/fr/aspose.cells/formatcondition) objets.



Le type ConditionalFormattingCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells/conditionalformattingcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells/conditionalformattingcollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells/conditionalformattingcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/conditionalformattingcollection/index_of/#aspose.cells.formatconditioncollection-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/conditionalformattingcollection/index_of/#aspose.cells.formatconditioncollection-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells/conditionalformattingcollection/last_index_of/#aspose.cells.formatconditioncollection) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/conditionalformattingcollection/last_index_of/#aspose.cells.formatconditioncollection-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/conditionalformattingcollection/last_index_of/#aspose.cells.formatconditioncollection-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`remove_area(self, start_row, start_column, total_rows, total_columns)`](/cells/python-net/fr/aspose.cells/conditionalformattingcollection/remove_area/#int-int-int-int) | Supprimez toute la mise en forme conditionnelle dans la plage.|
| [`add(self)`](/cells/python-net/fr/aspose.cells/conditionalformattingcollection/add/#) | Ajoute un FormatConditions à la collection.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells/conditionalformattingcollection/binary_search/#aspose.cells.formatconditioncollection) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Get Conditional Formatting
cformattings = sheet.conditional_formattings
# Adds an empty conditional formatting
index = cformattings.add()
# Get newly added Conditional formatting
fcs = cformattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Add condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Add condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`FormatCondition`](/cells/python-net/fr/aspose.cells/formatcondition)
