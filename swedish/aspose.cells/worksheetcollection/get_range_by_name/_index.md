---
title: get_range_by_name metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 120
url: /sv/aspose.cells/worksheetcollection/get_range_by_name/
is_root: false
---
##  get_range_by_name(range_name) {#str}
Hämtar Range-objekt med fördefinierat namn.


###  Returnerar

Räckviddsobjekt.


Returnerar null om det namngivna intervallet inte finns.


```python
def get_range_by_name(self, range_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| range_name | str | Namn på intervall.|


##  get_range_by_name(range_name, current_sheet_index, include_table) {#str-int-bool}
Får [Range](/cells/python-net/sv/aspose.cells/range) efter fördefinierat namn eller tabellnamn


###  Returnerar




```python
def get_range_by_name(self, range_name, current_sheet_index, include_table):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| range_name | str | Namn på området eller tabellens namn.|
| current_sheet_index | int | Arkindex. -1 representerar global .|
| include_table | bool | Anger om alla tabeller kontrolleras.|



###  Se även
* modul [aspose.cells](../../)
* klass [Range](/cells/python-net/sv/aspose.cells/range)
* klass [WorksheetCollection](/cells/python-net/sv/aspose.cells/worksheetcollection)
