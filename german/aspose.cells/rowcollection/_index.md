---
title: RowCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1240
url: /de/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection Klasse
Sammelt die [`Row`](/cells/python-net/de/aspose.cells/row) Objekte, die die einzelnen Zeilen in einem Arbeitsblatt darstellen.



Der Typ RowCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [count](/cells/python-net/de/aspose.cells/rowcollection/count) | Ruft die Anzahl der Zeilen in dieser Sammlung ab.|



Ruft ein [`Row`](/cells/python-net/de/aspose.cells/row)-Objekt anhand des angegebenen Zeilenindex ab. Das Row-Objekt mit dem angegebenen Zeilenindex wird instanziiert, falls es noch nicht vorhanden ist.
###  Indexer
| Name| Beschreibung|
| :- | :- |
| [index] |  |


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get_enumerator(self, reversed, sync)`](/cells/python-net/de/aspose.cells/rowcollection/get_enumerator/#bool-bool) | Ruft einen Enumerator ab, der die Zeilen dieser Sammlung durchläuft|
| [`get_row_by_index(self, index)`](/cells/python-net/de/aspose.cells/rowcollection/get_row_by_index/#int) | Ruft das Zeilenobjekt anhand der Position in der Liste ab.|
| [`clear(self)`](/cells/python-net/de/aspose.cells/rowcollection/clear/#) | Alle Zeilen und Zellen löschen.|
| [`remove_at(self, index)`](/cells/python-net/de/aspose.cells/rowcollection/remove_at/#int) | Entfernen Sie das Zeilenelement am angegebenen Index (Position) in dieser Sammlung.|



###  Beispiel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Get first row
row = worksheet.cells.rows[0]

```

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`Row`](/cells/python-net/de/aspose.cells/row)
