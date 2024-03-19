---
title: CellWatchCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 180
url: /de/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection Klasse
Stellt die Sammlung von Zellen in diesem Arbeitsblatt dar, die im „Überwachungsfenster“ überwacht werden.



Der Typ CellWatchCollection macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/cellwatchcollection/__init__/#) | Konstruiert eine neue Instanz von CellWatchCollection|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells/cellwatchcollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [add](/cells/python-net/de/aspose.cells/cellwatchcollection/add/#int-int) | Fügt [`CellWatch`](/cells/python-net/de/aspose.cells/cellwatch) mit Zeile und Spalte hinzu.|
| [add](/cells/python-net/de/aspose.cells/cellwatchcollection/add/#str) | Fügt [`CellWatch`](/cells/python-net/de/aspose.cells/cellwatch) mit dem Namen der Zelle hinzu.|
| [copy_to](/cells/python-net/de/aspose.cells/cellwatchcollection/copy_to/#list) | Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [copy_to](/cells/python-net/de/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [index_of](/cells/python-net/de/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom angegebenen Index bis zum letzten Element reicht.|
| [index_of](/cells/python-net/de/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der beim angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [last_index_of](/cells/python-net/de/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens in der gesamten Array-Liste zurück.|
| [last_index_of](/cells/python-net/de/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom ersten Element bis zum angegebenen Index reicht.|
| [last_index_of](/cells/python-net/de/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und beim angegebenen Index endet.|
| [binary_search](/cells/python-net/de/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.CellWatch) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichs nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet.
sheet = workbook.worksheets[0]
#  Add Cell Watch Item into the watch window
sheet.cell_watches.add("B2")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`CellWatch`](/cells/python-net/de/aspose.cells/cellwatch)
