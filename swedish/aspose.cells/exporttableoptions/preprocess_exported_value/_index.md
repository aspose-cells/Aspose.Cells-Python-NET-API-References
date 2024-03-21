---
title: preprocess_exported_value metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/exporttableoptions/preprocess_exported_value/
is_root: false
---
##  preprocess_exported_value {#int-int-aspose.cells.CellValue}
Förbearbeta värdet för den aktuella cellen som ska exporteras.


###  Returnerar

Om nuvarande cell har ersatts med annan typ och/eller värde.


```python
def preprocess_exported_value(self, cell_row, cell_column, value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| cell_row | int | radindex för aktuell cell|
| cell_column | int | kolumnindex för cellen|
| value | [`CellValue`](/cells/python-net/sv/aspose.cells/cellvalue) | värde och typ av aktuell cell|
###  Anmärkningar

Rad- och kolumnindex är cellens absoluta index i kalkylbladet, inte index i den exporterade tabellen.
Användaren kan kontrollera värdet på aktuell cell i åsidosättningsimplementeringen av denna metod,
om nuvarande cell behöver ersättas med annan typ och värde,
här ska implementeringen ställa in den förväntade typen och värdet på CellValue-objektet och returnera true.
Som standard gör denna metod ingenting och returnerar false.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`ExportTableOptions`](/cells/python-net/sv/aspose.cells/exporttableoptions)
