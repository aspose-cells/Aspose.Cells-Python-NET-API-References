---
title: max_row_count Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 280
url: /de/aspose.cells/txtloadoptions/max_row_count/
is_root: false
---
##  max_row_count Eigentum

Die maximale Anzahl der für ein Blatt zu importierenden Zeilen.

###  Bemerkungen

Die Zeilen, die dieses Limit überschreiten, werden ignoriert
oder gemäß [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/de/aspose.cells/txtloadoptions#extend_to_next_sheet) auf das nächste Blatt erweitert.
Diese Zählung umfasst die Kopfzeilen ([`TxtLoadOptions.header_rows_count`](/cells/python-net/de/aspose.cells/txtloadoptions#header_rows_count)).
Der maximal zulässige Wert ist die Zeilenbegrenzung des entsprechenden Dateiformats, z. B. 1048576 für eine XLSX-Datei.
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
