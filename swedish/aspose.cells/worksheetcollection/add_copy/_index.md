---
title: add_copy metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells/worksheetcollection/add_copy/
is_root: false
---
##  add_copy(self, sheet_name) {#str}
Lägger till ett kalkylblad i samlingen och kopierar data från ett befintligt kalkylblad.


###  Returnerar

[`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet) objektindex.


```python

def add_copy(self, sheet_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| sheet_name | str | Namn på källarbetsblad.|
###  Undantag
| Undantag| Beskrivning|
| :- | :- |
| [`CellsException`](/cells/python-net/sv/aspose.cells/cellsexception) | Anger ett ogiltigt kalkylbladsnamn.|




##  add_copy(self, sheet_index) {#int}
Lägger till ett kalkylblad i samlingen och kopierar data från ett befintligt kalkylblad.


###  Returnerar

[`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet) objektindex.


```python

def add_copy(self, sheet_index):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| sheet_index | int | Index för källarbetsblad.|


##  add_copy(self, source, dest_sheet_names) {#list-list}
Kopiera en grupp med arbetsblad.



```python

def add_copy(self, source, dest_sheet_names):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| source | list | Källarbetsbladen.|
| dest_sheet_names | list | Namnen på de kopierade arken.|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`CellsException`](/cells/python-net/sv/aspose.cells/cellsexception)
* klass [`Worksheet`](/cells/python-net/sv/aspose.cells/worksheet)
* klass [`WorksheetCollection`](/cells/python-net/sv/aspose.cells/worksheetcollection)
