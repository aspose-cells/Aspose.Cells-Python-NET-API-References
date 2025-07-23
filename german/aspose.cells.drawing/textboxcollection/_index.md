---
title: TextBoxCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 670
url: /de/aspose.cells.drawing/textboxcollection/
is_root: false
---
##  TextBoxCollection Klasse
Kapselt eine Sammlung von [`TextBox`](/cells/python-net/de/aspose.cells.drawing/textbox) Objekten.



Der Typ TextBoxCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells.drawing/textboxcollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/de/aspose.cells.drawing/textboxcollection/copy_to/#list) |Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/de/aspose.cells.drawing/textboxcollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [`index_of(self, item, index)`](/cells/python-net/de/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.|
| [`index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [`last_index_of(self, item)`](/cells/python-net/de/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb der gesamten Arrayliste zurück.|
| [`last_index_of(self, item, index)`](/cells/python-net/de/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom ersten Element bis zum angegebenen Index erstreckt.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.|
| [`get(self, name)`](/cells/python-net/de/aspose.cells.drawing/textboxcollection/get/#str) | Ruft das Element [`TextBox`](/cells/python-net/de/aspose.cells.drawing/textbox) anhand des Namens ab.|
| [`add(self, upper_left_row, upper_left_column, height, width)`](/cells/python-net/de/aspose.cells.drawing/textboxcollection/add/#int-int-int-int) | Fügt der Sammlung ein Textfeld hinzu.|
| [`binary_search(self, item)`](/cells/python-net/de/aspose.cells.drawing/textboxcollection/binary_search/#aspose.cells.drawing.textbox) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichers nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get collection object
textBoxCollection = workbook.worksheets[0].text_boxes
# add a textbox
textBoxCollection.add(1, 1, 50, 100)
for tbox in textBoxCollection:
    pass

```

###  Siehe auch
* Modul [`aspose.cells.drawing`](..)
* Klasse [`TextBox`](/cells/python-net/de/aspose.cells.drawing/textbox)
