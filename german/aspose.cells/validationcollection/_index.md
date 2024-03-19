---
title: ValidationCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1620
url: /de/aspose.cells/validationcollection/
is_root: false
---
##  ValidationCollection Klasse
Stellt die Datenvalidierungssammlung dar.



Der Typ ValidationCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells/validationcollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [add](/cells/python-net/de/aspose.cells/validationcollection/add/#) | Fügt der Sammlung eine Datenvalidierung hinzu.|
| [add](/cells/python-net/de/aspose.cells/validationcollection/add/#aspose.cells.CellArea) | Fügt der Sammlung eine Datenvalidierung hinzu.|
| [copy_to](/cells/python-net/de/aspose.cells/validationcollection/copy_to/#list) | Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [copy_to](/cells/python-net/de/aspose.cells/validationcollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [index_of](/cells/python-net/de/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom angegebenen Index bis zum letzten Element reicht.|
| [index_of](/cells/python-net/de/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der beim angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [last_index_of](/cells/python-net/de/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens in der gesamten Array-Liste zurück.|
| [last_index_of](/cells/python-net/de/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom ersten Element bis zum angegebenen Index reicht.|
| [last_index_of](/cells/python-net/de/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und beim angegebenen Index endet.|
| [remove_a_cell](/cells/python-net/de/aspose.cells/validationcollection/remove_a_cell/#int-int) | Entfernt alle Validierungseinstellungen für die Zelle.|
| [remove_area](/cells/python-net/de/aspose.cells/validationcollection/remove_area/#aspose.cells.CellArea) | Entfernt alle Validierungseinstellungen für den Bereich.|
| [get_validation_in_cell](/cells/python-net/de/aspose.cells/validationcollection/get_validation_in_cell/#int-int) | Ruft die auf die angegebene Zelle angewendete Validierung ab.|
| [binary_search](/cells/python-net/de/aspose.cells/validationcollection/binary_search/#aspose.cells.Validation) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichs nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import CellArea, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.LIST
validation.formula1 = "a,b,c,d"

```

###  Siehe auch
* Modul [`aspose.cells`](..)
