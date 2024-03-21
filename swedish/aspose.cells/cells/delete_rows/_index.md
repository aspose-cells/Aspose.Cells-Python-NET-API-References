---
title: delete_rows metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 260
url: /sv/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows {#int-int}
Tar bort flera rader.



```python
def delete_rows(self, row_index, total_rows):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row_index | int | Det första radindexet som ska raderas.|
| total_rows | int | Antal rader som ska raderas.|
###  Anmärkningar

Om det borttagna intervallet innehåller den övre delen (inte hela) av tabellen (ListObject),
intervallet kunde inte raderas och ingenting kommer att göras.
Det fungerar på samma sätt med MS Excel.

##  delete_rows {#int-int-bool}
Tar bort flera rader i kalkylbladet.


###  Returnerar




```python
def delete_rows(self, row_index, total_rows, update_reference):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row_index | int | Index för den första raden som ska raderas.|
| total_rows | int | Antal rader som ska raderas.|
| update_reference | bool | Anger om uppdatering av referenser i andra kalkylblad.|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cells`](/cells/python-net/sv/aspose.cells/cells)
