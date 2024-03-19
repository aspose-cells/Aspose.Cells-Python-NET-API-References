---
title: HyperlinkCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 850
url: /de/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection Klasse
Kapselt eine Sammlung von [`Hyperlink`](/cells/python-net/de/aspose.cells/hyperlink)-Objekten.



Der Typ HyperlinkCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells/hyperlinkcollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [add](/cells/python-net/de/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | Fügt einen Hyperlink zu einer angegebenen Zelle oder einem Zellbereich hinzu.|
| [add](/cells/python-net/de/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | Fügt einen Hyperlink zu einer angegebenen Zelle oder einem Zellbereich hinzu.|
| [add](/cells/python-net/de/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | Fügt einen Hyperlink zu einer angegebenen Zelle oder einem Zellbereich hinzu.|
| [copy_to](/cells/python-net/de/aspose.cells/hyperlinkcollection/copy_to/#list) | Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [copy_to](/cells/python-net/de/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [index_of](/cells/python-net/de/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom angegebenen Index bis zum letzten Element reicht.|
| [index_of](/cells/python-net/de/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der beim angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [last_index_of](/cells/python-net/de/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens in der gesamten Array-Liste zurück.|
| [last_index_of](/cells/python-net/de/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom ersten Element bis zum angegebenen Index reicht.|
| [last_index_of](/cells/python-net/de/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und beim angegebenen Index endet.|
| [binary_search](/cells/python-net/de/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.Hyperlink) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichs nach einem Element und gibt den nullbasierten Index des Elements zurück.|



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
