---
title: CommentCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 270
url: /de/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection Klasse
Kapselt eine Sammlung von [`Comment`](/cells/python-net/de/aspose.cells/comment) Objekten.



Der Typ CommentCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells/commentcollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`add_threaded_comment(self, row, column, text, author)`](/cells/python-net/de/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.threadedcommentauthor) | Fügt einen Threadkommentar hinzu.|
| [`add_threaded_comment(self, cell_name, text, author)`](/cells/python-net/de/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.threadedcommentauthor) | Fügt einen Threadkommentar hinzu.|
| [`get_threaded_comments(self, row, column)`](/cells/python-net/de/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Ruft die Thread-Kommentare nach Zeilen- und Spaltenindex ab.|
| [`get_threaded_comments(self, cell_name)`](/cells/python-net/de/aspose.cells/commentcollection/get_threaded_comments/#str) | Ruft die Thread-Kommentare nach Zellennamen ab.|
| [`add(self, row, column)`](/cells/python-net/de/aspose.cells/commentcollection/add/#int-int) | Fügt der Sammlung einen Kommentar hinzu.|
| [`add(self, cell_name)`](/cells/python-net/de/aspose.cells/commentcollection/add/#str) | Fügt der Sammlung einen Kommentar hinzu.|
| [`get(self, row, column)`](/cells/python-net/de/aspose.cells/commentcollection/get/#int-int) | Add API for Python Via .Net.since this[int, int] wird nicht unterstützt|
| [`get(self, index)`](/cells/python-net/de/aspose.cells/commentcollection/get/#int) | Ruft das Element [`Comment`](/cells/python-net/de/aspose.cells/comment) am angegebenen Index ab.|
| [`get(self, cell_name)`](/cells/python-net/de/aspose.cells/commentcollection/get/#str) | Ruft das Element [`Comment`](/cells/python-net/de/aspose.cells/comment) in der angegebenen Zelle ab.|
| [`remove_at(self, cell_name)`](/cells/python-net/de/aspose.cells/commentcollection/remove_at/#str) | Entfernt den Kommentar der jeweiligen Zelle.|
| [`remove_at(self, row, column)`](/cells/python-net/de/aspose.cells/commentcollection/remove_at/#int-int) | Entfernt den Kommentar der jeweiligen Zelle.|
| [`copy_to(self, array)`](/cells/python-net/de/aspose.cells/commentcollection/copy_to/#list) |Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/de/aspose.cells/commentcollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [`index_of(self, item, index)`](/cells/python-net/de/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.|
| [`index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [`last_index_of(self, item)`](/cells/python-net/de/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb der gesamten Arrayliste zurück.|
| [`last_index_of(self, item, index)`](/cells/python-net/de/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom ersten Element bis zum angegebenen Index erstreckt.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.|
| [`binary_search(self, item)`](/cells/python-net/de/aspose.cells/commentcollection/binary_search/#aspose.cells.comment) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichers nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`Comment`](/cells/python-net/de/aspose.cells/comment)
