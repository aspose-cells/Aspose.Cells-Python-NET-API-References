---
title: delete_rows metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 260
url: /sv/aspose.cells/cells/delete_rows/
is_root: false
---
##  delete_rows(self, row_index, total_rows) {#int-int}
Tar bort flera rader.



```python

def delete_rows(self, row_index, total_rows):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row_index | int | Det första radindexet som ska tas bort.|
| total_rows | int | Antal rader som ska raderas.|
###  Anmärkningar

Om det borttagna området innehåller den övre delen (inte hela) av tabellen (ListObject),
Avståndet kunde inte raderas och ingenting kommer att göras.
Det fungerar på samma sätt med MS Excel.

##  delete_rows(self, row_index, total_rows, update_reference) {#int-int-bool}
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
| update_reference | bool | Anger om referenser i andra kalkylblad ska uppdateras.|


##  delete_rows(self, row_index, total_rows, options) {#int-int-aspose.cells.DeleteOptions}
Tar bort flera rader i kalkylbladet.


###  Returnerar




```python

def delete_rows(self, row_index, total_rows, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row_index | int | Index för den första raden som ska raderas.|
| total_rows | int | Antal rader som ska raderas.|
| options | [`DeleteOptions`](/cells/python-net/sv/aspose.cells/deleteoptions) | Alternativ för borttagningsåtgärden|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cells`](/cells/python-net/sv/aspose.cells/cells)
