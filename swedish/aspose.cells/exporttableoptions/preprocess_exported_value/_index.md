---
title: preprocess_exported_value metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/exporttableoptions/preprocess_exported_value/
is_root: false
---
##  preprocess_exported_value(self, cell_row, cell_column, value) {#int-int-aspose.cells.CellValue}
Förbearbeta värdet för den aktuella cellen som ska exporteras.


###  Returnerar

Om den aktuella cellen har ersatts med en annan typ och/eller ett annat värde.


```python

def preprocess_exported_value(self, cell_row, cell_column, value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| cell_row | int | radindexet för den aktuella cellen|
| cell_column | int | cellens kolumnindex|
| value | [`CellValue`](/cells/python-net/sv/aspose.cells/cellvalue) | värde och typ av aktuell cell|
###  Anmärkningar

Rad- och kolumnindexet är cellens absoluta index i kalkylbladet, inte indexet i den exporterade tabellen.
Användaren kan kontrollera värdet på den aktuella cellen i override-implementeringen av den här metoden,
om den aktuella cellen behöver ersättas med en annan typ och ett annat värde,
här bör implementeringen ställa in den förväntade typen och värdet för CellValue-objektet och returnera sant.
Som standard gör den här metoden ingenting och returnerar falskt.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`ExportTableOptions`](/cells/python-net/sv/aspose.cells/exporttableoptions)
