---
title: max_row_count Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 300
url: /de/aspose.cells/txtloadoptions/max_row_count/
is_root: false
---
##  max_row_count Eigentum

Die maximale Anzahl der Zeilen, die für ein Blatt importiert werden sollen.

###  Bemerkungen

Die Zeilen, die diesen Grenzwert überschreiten, werden ignoriert
oder auf das nächste Blatt gemäß [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/de/aspose.cells/txtloadoptions#extend_to_next_sheet) verlängert.
Diese Zählung umfasst die Kopfzeilen ([`TxtLoadOptions.header_rows_count`](/cells/python-net/de/aspose.cells/txtloadoptions#header_rows_count)).
Der maximal zulässige Wert ist die Zeilenbeschränkung des entsprechenden Dateiformats, z. B. für eine XLSX-Datei 1048576.
Wenn diese Eigenschaft nicht angegeben wurde oder der angegebene Wert nicht positiv ist, wird auch die Höchstgrenze verwendet.
###  Definition:
```python
@property
def max_row_count(self):
    ...
@max_row_count.setter
def max_row_count(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`TxtLoadOptions`](/cells/python-net/de/aspose.cells/txtloadoptions)
