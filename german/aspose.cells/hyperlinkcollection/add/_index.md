---
title: add Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells/hyperlinkcollection/add/
is_root: false
---
##  add(self, cell_name, total_rows, total_columns, address) {#str-int-int-str}
Fügt einer angegebenen Zelle oder einem Zellbereich einen Hyperlink hinzu.


###  Kehrt zurück

[`Hyperlink`](/cells/python-net/de/aspose.cells/hyperlink) Objektindex.


```python

def add(self, cell_name, total_rows, total_columns, address):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| cell_name | str | Cell Name.|
| total_rows | int | Anzahl der Zeilen in diesem Hyperlinkbereich.|
| total_columns | int |Anzahl der Spalten dieses Hyperlinkbereichs.|
| address | str | Adresse des Hyperlinks.|


##  add(self, first_row, first_column, total_rows, total_columns, address) {#int-int-int-int-str}
Fügt einer angegebenen Zelle oder einem Zellbereich einen Hyperlink hinzu.


###  Kehrt zurück

[`Hyperlink`](/cells/python-net/de/aspose.cells/hyperlink) Objektindex.


```python

def add(self, first_row, first_column, total_rows, total_columns, address):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| first_row | int | Erste Zeile des Hyperlinkbereichs.|
| first_column | int | Erste Spalte des Hyperlinkbereichs.|
| total_rows | int | Anzahl der Zeilen in diesem Hyperlinkbereich.|
| total_columns | int |Anzahl der Spalten dieses Hyperlinkbereichs.|
| address | str | Adresse des Hyperlinks.|

###  Beispiel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
excel = Workbook()
worksheet = excel.worksheets[0]
worksheet.hyperlinks.add("A4", 1, 1, "http://www.aspose.com")
worksheet.hyperlinks.add("A5", 1, 1, "c:\\book1.xls")

```


##  add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip) {#str-str-str-str-str}
Fügt einer angegebenen Zelle oder einem Zellbereich einen Hyperlink hinzu.


###  Kehrt zurück

[`Hyperlink`](/cells/python-net/de/aspose.cells/hyperlink) Objektindex.


```python

def add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| start_cell_name | str |Die oberste linke Zelle des Bereichs.|
| end_cell_name | str | Die untere rechte Zelle des Bereichs.|
| address | str | Adresse des Hyperlinks.|
| text_to_display | str | Der für den angegebenen Hyperlink anzuzeigende Text.|
| screen_tip | str | Der QuickInfo-Text für den angegebenen Hyperlink.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Hyperlink`](/cells/python-net/de/aspose.cells/hyperlink)
* Klasse [`HyperlinkCollection`](/cells/python-net/de/aspose.cells/hyperlinkcollection)
