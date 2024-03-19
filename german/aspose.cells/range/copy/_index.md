---
title: copy Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 50
url: /de/aspose.cells/range/copy/
is_root: false
---
##  copy {#aspose.cells.Range}
Kopiert Daten (einschließlich Formeln), Formatierungen, Zeichnungsobjekte usw. aus einem Quellbereich.



```python
def copy(self, range):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/de/aspose.cells/range) |Quelle [`Range`](/cells/python-net/de/aspose.cells/range) Objekt.|

###  Beispiel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
range1 = cells.create_range("A1:A5")
range2 = cells.create_range("A6:A10")
# Copy the range.
range1.copy(range2)
# Save the Excel file
workbook.save("book1.xlsm")

```


##  copy {#aspose.cells.Range-aspose.cells.PasteOptions}
Kopieren des Bereichs mit Sonderoptionen zum Einfügen.



```python
def copy(self, range, options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/de/aspose.cells/range) | Der Quellbereich.|
| options | [`PasteOptions`](/cells/python-net/de/aspose.cells/pasteoptions) | Die speziellen Optionen zum Einfügen.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Range`](/cells/python-net/de/aspose.cells/range)
