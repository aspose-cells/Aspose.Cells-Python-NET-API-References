---
title: HyperlinkCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 830
url: /de/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection Klasse
Kapselt eine Sammlung von [`Hyperlink`](/cells/python-net/de/aspose.cells/hyperlink) Objekten.



Der Typ HyperlinkCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells/hyperlinkcollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add(self, first_row, first_column, total_rows, total_columns, address)`](/cells/python-net/de/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | Fügt einer angegebenen Zelle oder einem Zellbereich einen Hyperlink hinzu.|
| [`add(self, cell_name, total_rows, total_columns, address)`](/cells/python-net/de/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | Fügt einer angegebenen Zelle oder einem Zellbereich einen Hyperlink hinzu.|
| [`add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip)`](/cells/python-net/de/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | Fügt einer angegebenen Zelle oder einem Zellbereich einen Hyperlink hinzu.|
| [`copy_to(self, array)`](/cells/python-net/de/aspose.cells/hyperlinkcollection/copy_to/#list) |Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/de/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [`index_of(self, item, index)`](/cells/python-net/de/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.|
| [`index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [`last_index_of(self, item)`](/cells/python-net/de/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb der gesamten Arrayliste zurück.|
| [`last_index_of(self, item, index)`](/cells/python-net/de/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom ersten Element bis zum angegebenen Index erstreckt.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.|
| [`binary_search(self, item)`](/cells/python-net/de/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.hyperlink) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichers nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`Hyperlink`](/cells/python-net/de/aspose.cells/hyperlink)
