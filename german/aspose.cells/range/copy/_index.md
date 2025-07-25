---
title: copy Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 100
url: /de/aspose.cells/range/copy/
is_root: false
---
##  copy(self, range) {#aspose.cells.Range}
Kopiert Daten (einschließlich Formeln), Formatierungen, Zeichenobjekte usw. aus einem Quellbereich.



```python

def copy(self, range):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/de/aspose.cells/range) | Quellobjekt [`Range`](/cells/python-net/de/aspose.cells/range).|

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


##  copy(self, range, options) {#aspose.cells.Range-aspose.cells.PasteOptions}
Kopieren des Bereichs mit den Optionen zum Einfügen von Inhalten.



```python

def copy(self, range, options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/de/aspose.cells/range) | Der Quellbereich.|
| options | [`PasteOptions`](/cells/python-net/de/aspose.cells/pasteoptions) | Die Optionen zum Einfügen von Inhalten.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Range`](/cells/python-net/de/aspose.cells/range)
