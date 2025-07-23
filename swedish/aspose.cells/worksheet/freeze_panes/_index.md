---
title: freeze_panes metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 140
url: /sv/aspose.cells/worksheet/freeze_panes/
is_root: false
---
##  freeze_panes(self, cell_name, freezed_rows, freezed_columns) {#str-int-int}
Fryser rutor vid den angivna cellen i kalkylbladet.



```python

def freeze_panes(self, cell_name, freezed_rows, freezed_columns):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| cell_name | str | Cell namn.|
| freezed_rows | int | Antal synliga rader i den översta rutan, högst radindex.|
| freezed_columns | int | Antal synliga kolumner i vänster ruta, högst kolumnindex.|
###  Anmärkningar

Radindex och kolumnindex kan inte alla vara noll. Antal rader och antal kolumner
kan inte heller alla vara noll.

##  freeze_panes(self, row, column, freezed_rows, freezed_columns) {#int-int-int-int}
Fryser rutor vid den angivna cellen i kalkylbladet.



```python

def freeze_panes(self, row, column, freezed_rows, freezed_columns):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row | int | Radindex.|
| column | int | Kolumnindex.|
| freezed_rows | int | Antal synliga rader i den översta rutan, högst radindex.|
| freezed_columns | int | Antal synliga kolumner i vänster ruta, högst kolumnindex.|
###  Anmärkningar

Radindex och kolumnindex kan inte alla vara noll. Antal rader och antal kolumner
kan inte heller alla vara noll.


De två första parametrarna anger den frysta positionen och de två sista parametrarna anger det frysta området i den vänstra övre rutan.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet)
