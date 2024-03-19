---
title: CommentCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 300
url: /de/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection Klasse
Kapselt eine Sammlung von [`Comment`](/cells/python-net/de/aspose.cells/comment)-Objekten.



Der Typ CommentCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells/commentcollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [add_threaded_comment](/cells/python-net/de/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.ThreadedCommentAuthor) | Fügt einen Thread-Kommentar hinzu.|
| [add_threaded_comment](/cells/python-net/de/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.ThreadedCommentAuthor) | Fügt einen Thread-Kommentar hinzu.|
| [get_threaded_comments](/cells/python-net/de/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Ruft die Thread-Kommentare nach Zeilen- und Spaltenindex ab.|
| [get_threaded_comments](/cells/python-net/de/aspose.cells/commentcollection/get_threaded_comments/#str) |Ruft die Thread-Kommentare nach Zellennamen ab.|
| [add](/cells/python-net/de/aspose.cells/commentcollection/add/#int-int) | Fügt der Sammlung einen Kommentar hinzu.|
| [add](/cells/python-net/de/aspose.cells/commentcollection/add/#str) | Fügt der Sammlung einen Kommentar hinzu.|
| [remove_at](/cells/python-net/de/aspose.cells/commentcollection/remove_at/#str) | Entfernt den Kommentar der spezifischen Zelle.|
| [remove_at](/cells/python-net/de/aspose.cells/commentcollection/remove_at/#int-int) | Entfernt den Kommentar der spezifischen Zelle.|
| [copy_to](/cells/python-net/de/aspose.cells/commentcollection/copy_to/#list) | Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [copy_to](/cells/python-net/de/aspose.cells/commentcollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [index_of](/cells/python-net/de/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom angegebenen Index bis zum letzten Element reicht.|
| [index_of](/cells/python-net/de/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der beim angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [last_index_of](/cells/python-net/de/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens in der gesamten Array-Liste zurück.|
| [last_index_of](/cells/python-net/de/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der vom ersten Element bis zum angegebenen Index reicht.|
| [last_index_of](/cells/python-net/de/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und beim angegebenen Index endet.|
| [binary_search](/cells/python-net/de/aspose.cells/commentcollection/binary_search/#aspose.cells.Comment) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichs nach einem Element und gibt den nullbasierten Index des Elements zurück.|



###  Beispiel

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`Comment`](/cells/python-net/de/aspose.cells/comment)
