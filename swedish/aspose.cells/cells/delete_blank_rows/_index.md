---
title: delete_blank_rows metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 210
url: /sv/aspose.cells/cells/delete_blank_rows/
is_root: false
---
##  delete_blank_rows(self) {#}
Ta bort alla tomma rader som inte innehåller data eller andra objekt.



```python

def delete_blank_rows(self):
    ...
```




##  delete_blank_rows(self, options) {#aspose.cells.DeleteOptions}
Ta bort alla tomma rader som inte innehåller data eller några specialobjekt, såsom synliga kommentarer eller pivottabeller.



```python

def delete_blank_rows(self, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| options | [`DeleteOptions`](/cells/python-net/sv/aspose.cells/deleteoptions) | Alternativen för att radera intervall.|
###  Anmärkningar

För tomma rader som ska raderas krävs det inte bara att [`Row.is_blank`](/cells/python-net/sv/aspose.cells/row#is_blank) ska vara sant,
men det ska inte heller finnas någon synlig kommentar definierad för någon cell i dessa rader,
och ingen pivottabell vars område skär dem.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cells`](/cells/python-net/sv/aspose.cells/cells)
