---
title: trim_leading_blank_row_and_column Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 230
url: /de/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column/
is_root: false
---
##  trim_leading_blank_row_and_column Eigentum

Gibt an, ob führende leere Zeilen und Spalten wie in MS Excel abgeschnitten werden sollen.
Der Standardwert ist „true“.

###  Bemerkungen

Dasselbe gilt für die Regel in MS Excel. Eine Zeile/Spalte wird nicht als leer betrachtet, wenn sie einen benutzerdefinierten Stil hat.
auch wenn es keine Zelldaten enthält.
Beim Speichern im LightCells-Modus hat diese Option keine Wirkung.
Der Benutzer sollte den Ausgabebereich durch die Implementierung von [`TxtSaveOptions.LightCellsDataProvider`](/cells/python-net/de/aspose.cells/txtsaveoptions) steuern
oder unter Angabe von [`TxtSaveOptions.export_area`](/cells/python-net/de/aspose.cells/txtsaveoptions#export_area)
###  Definition:
```python
@property
def trim_leading_blank_row_and_column(self):
    ...
@trim_leading_blank_row_and_column.setter
def trim_leading_blank_row_and_column(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`TxtSaveOptions`](/cells/python-net/de/aspose.cells/txtsaveoptions)
