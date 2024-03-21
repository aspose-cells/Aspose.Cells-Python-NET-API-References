---
title: max_column_count Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 290
url: /de/aspose.cells/txtloadoptions/max_column_count/
is_root: false
---
##  max_column_count Eigentum

Die maximale Anzahl der Spalten, die für ein Blatt importiert werden sollen.

###  Bemerkungen

Die Spalten, die diesen Grenzwert überschreiten, werden ignoriert
oder auf das nächste Blatt gemäß [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/de/aspose.cells/txtloadoptions#extend_to_next_sheet) verlängert.
Diese Zählung umfasst die Kopfspalten ([`TxtLoadOptions.header_columns_count`](/cells/python-net/de/aspose.cells/txtloadoptions#header_columns_count)).
Der Maximalwert ist die Spaltenbeschränkung des entsprechenden Dateiformats, z. B. für eine XLSX-Datei 16384.
Wenn diese Eigenschaft nicht angegeben wurde oder der angegebene Wert nicht positiv ist, wird auch die Höchstgrenze verwendet.
###  Definition:
```python
@property
def max_column_count(self):
    ...
@max_column_count.setter
def max_column_count(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`TxtLoadOptions`](/cells/python-net/de/aspose.cells/txtloadoptions)
