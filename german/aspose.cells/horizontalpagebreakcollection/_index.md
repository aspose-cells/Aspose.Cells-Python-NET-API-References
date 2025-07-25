---
title: HorizontalPageBreakCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 770
url: /de/aspose.cells/horizontalpagebreakcollection/
is_root: false
---
##  HorizontalPageBreakCollection Klasse
Kapselt eine Sammlung von [`HorizontalPageBreak`](/cells/python-net/de/aspose.cells/horizontalpagebreak) Objekten.



Der Typ HorizontalPageBreakCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add(self, row, start_column, end_column)`](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/add/#int-int-int) | Fügt der Sammlung einen horizontalen Seitenumbruch hinzu.|
| [`add(self, row)`](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/add/#int) | Fügt der Sammlung einen horizontalen Seitenumbruch hinzu.|
| [`add(self, row, column)`](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/add/#int-int) | Fügt der Sammlung einen horizontalen Seitenumbruch hinzu.|
| [`add(self, cell_name)`](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/add/#str) | Fügt der Sammlung einen horizontalen Seitenumbruch hinzu.|
| [`copy_to(self, array)`](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/copy_to/#list) |Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [`index_of(self, item, index)`](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.horizontalpagebreak-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.|
| [`index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.horizontalpagebreak-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [`last_index_of(self, item)`](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb der gesamten Arrayliste zurück.|
| [`last_index_of(self, item, index)`](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom ersten Element bis zum angegebenen Index erstreckt.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.|
| [`get(self, cell_name)`](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/get/#str) | Ruft das Element [`HorizontalPageBreak`](/cells/python-net/de/aspose.cells/horizontalpagebreak) mit dem angegebenen Zellennamen ab.|
| [`binary_search(self, item)`](/cells/python-net/de/aspose.cells/horizontalpagebreakcollection/binary_search/#aspose.cells.horizontalpagebreak) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichers nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`HorizontalPageBreak`](/cells/python-net/de/aspose.cells/horizontalpagebreak)
