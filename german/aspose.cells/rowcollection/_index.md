---
title: RowCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1310
url: /de/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection Klasse
Sammelt die [Row](/cells/python-net/de/aspose.cells/row)-Objekte, die die einzelnen Zeilen in einem Arbeitsblatt darstellen.



Der Typ RowCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [count](/cells/python-net/de/aspose.cells/rowcollection/count) | Ruft die Anzahl der Zeilen in dieser Auflistung ab.|



Ruft ein [Row](/cells/python-net/de/aspose.cells/row)-Objekt nach gegebenem Zeilenindex ab. Das Zeilenobjekt des angegebenen Zeilenindex wird instanziiert, wenn es vorher nicht existiert.
###  Indexierer
| Name| Beschreibung|
| :- | :- |
| [index] |  |


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [get_row_by_index(index)](/cells/python-net/de/aspose.cells/rowcollection/get_row_by_index/#int) | Ruft das Zeilenobjekt nach der Position in der Liste ab.|
| [clear()](/cells/python-net/de/aspose.cells/rowcollection/clear/#) | Löschen Sie alle Zeilen und Zellen.|
| [remove_at(index)](/cells/python-net/de/aspose.cells/rowcollection/remove_at/#int) | Entfernt die Zeile am angegebenen Index|



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
* Modul [aspose.cells](..)
* Klasse [Row](/cells/python-net/de/aspose.cells/row)
