---
title: merge metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 800
url: /sv/aspose.cells/cells/merge/
is_root: false
---
##  merge(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Sammanfogar ett angivet cellområde till en enda cell.



```python

def merge(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| first_row | int | Första raden i detta intervall (nollbaserat)|
| first_column | int | Första kolumnen i detta intervall (nollbaserat)|
| total_rows | int |Antal rader (baserat på en)|
| total_columns | int | Antal kolumner (baserat på en)|
###  Anmärkningar

Referera till den sammanslagna cellen via adressen till den övre vänstra cellen i intervallet.

##  merge(self, first_row, first_column, total_rows, total_columns, merge_conflict) {#int-int-int-int-bool}

Sammanfogar ett angivet cellområde till en enda cell.



```python

def merge(self, first_row, first_column, total_rows, total_columns, merge_conflict):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| first_row | int | Första raden i detta intervall (nollbaserat)|
| first_column | int | Första kolumnen i detta intervall (nollbaserat)|
| total_rows | int |Antal rader (baserat på en)|
| total_columns | int | Antal kolumner (baserat på en)|
| merge_conflict | bool | Sammanslagning konflikterar sammanslagna områden.|
###  Anmärkningar

Referera till den sammanslagna cellen via adressen till den övre vänstra cellen i intervallet.
Om mergeConflict är sant och det sammanslagna området står i konflikt med andra sammanslagna celler,
Andra sammanslagna celler kommer att tas bort automatiskt.

##  merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict) {#int-int-int-int-bool-bool}
Sammanfogar ett angivet cellområde till en enda cell.



```python

def merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| first_row | int | Första raden i detta intervall (nollbaserat)|
| first_column | int | Första kolumnen i detta intervall (nollbaserat)|
| total_rows | int |Antal rader (baserat på en)|
| total_columns | int | Antal kolumner (baserat på en)|
| check_conflict | bool | Anger om kontrollen av de sammanslagna cellerna skär över andra sammanslagna celler|
| merge_conflict | bool | Sammanslagning konflikterar sammanslagna områden.|
###  Anmärkningar

Referera till den sammanslagna cellen via adressen till den övre vänstra cellen i intervallet.
Om mergeConflict är sant och det sammanslagna området står i konflikt med andra sammanslagna celler,
Andra sammanslagna celler kommer att tas bort automatiskt.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cells`](/cells/python-net/sv/aspose.cells/cells)
