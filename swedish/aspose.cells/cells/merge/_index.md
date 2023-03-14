---
title: merge metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 790
url: /sv/aspose.cells/cells/merge/
is_root: false
---
##  merge(first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Slår samman ett specificerat cellområde till en enda cell.



```python
def merge(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| first_row | int | Första raden i detta intervall (nollbaserat)|
| first_column | int | Första kolumnen i detta intervall (nollbaserat)|
| total_rows | int | Antal rader (en baserat)|
| total_columns | int | Antal kolumner (en baserat)|
###  Anmärkningar

Referera till den sammanslagna cellen via adressen till den övre vänstra cellen i intervallet.

##  merge(first_row, first_column, total_rows, total_columns, merge_conflict) {#int-int-int-int-bool}

Slår samman ett specificerat cellområde till en enda cell.



```python
def merge(self, first_row, first_column, total_rows, total_columns, merge_conflict):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| first_row | int | Första raden i detta intervall (nollbaserat)|
| first_column | int | Första kolumnen i detta intervall (nollbaserat)|
| total_rows | int | Antal rader (en baserat)|
| total_columns | int | Antal kolumner (en baserat)|
| merge_conflict | bool | Slå samman konfliktsammanslagna intervall.|
###  Anmärkningar

Referera till den sammanslagna cellen via adressen till den övre vänstra cellen i intervallet.
Om mergeConflict är sant och det sammanslagna området är i konflikt med andra sammanslagna celler,
andra sammanslagna celler kommer att tas bort automatiskt.

##  merge(first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict) {#int-int-int-int-bool-bool}
Slår samman ett specificerat cellområde till en enda cell.



```python
def merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| first_row | int | Första raden i detta intervall (nollbaserat)|
| first_column | int | Första kolumnen i detta intervall (nollbaserat)|
| total_rows | int | Antal rader (en baserat)|
| total_columns | int | Antal kolumner (en baserat)|
| check_conflict | bool | Anger om kontrollera de sammanslagna cellerna skär andra sammanslagna celler|
| merge_conflict | bool | Slå samman konfliktsammanslagna intervall.|
###  Anmärkningar

Referera till den sammanslagna cellen via adressen till den övre vänstra cellen i intervallet.
Om mergeConflict är sant och det sammanslagna området är i konflikt med andra sammanslagna celler,
andra sammanslagna celler kommer att tas bort automatiskt.


###  Se även
* modul [aspose.cells](../../)
* klass [Cells](/cells/python-net/sv/aspose.cells/cells)
