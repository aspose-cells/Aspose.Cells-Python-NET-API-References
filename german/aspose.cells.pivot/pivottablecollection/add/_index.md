---
title: add Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.pivot/pivottablecollection/add/
is_root: false
---
##  add(self, source_data, dest_cell_name, table_name) {#str-str-str}
Fügt eine neue PivotTable hinzu.


###  Kehrt zurück

Der neu hinzugefügte Cache-Index.


```python

def add(self, source_data, dest_cell_name, table_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| source_data | str | Die Daten für den neuen PivotTable-Cache.|
| dest_cell_name | str | Die Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| table_name | str | Der Name des neuen PivotTable-Berichts.|


##  add(self, pivot_table, dest_cell_name, table_name) {#aspose.cells.pivot.PivotTable-str-str}
Fügt eine neue PivotTable basierend auf einer anderen PivotTable hinzu.


###  Kehrt zurück

Der neu hinzugefügte PivotTable-Index.


```python

def add(self, pivot_table, dest_cell_name, table_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/de/aspose.cells.pivot/pivottable) | Die Quell-PivotTable.|
| dest_cell_name | str | Die Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| table_name | str | Der Name des neuen PivotTable-Berichts.|


##  add(self, source_data, dest_cell_name, table_name, use_same_source) {#str-str-str-bool}
Fügt eine neue PivotTable hinzu.


###  Kehrt zurück

Der neu hinzugefügte Cache-Index.


```python

def add(self, source_data, dest_cell_name, table_name, use_same_source):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| source_data | str | Die Daten für den neuen PivotTable-Cache.|
| dest_cell_name | str | Die Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| table_name | str | Der Name des neuen PivotTable-Berichts.|
| use_same_source | bool | Gibt an, ob dieselbe Datenquelle verwendet wird, wenn eine andere vorhandene Pivot-Tabelle diese Datenquelle verwendet hat.<br/> Wenn die Eigenschaft wahr ist, wird Speicher gespart.|


##  add(self, source_data, row, column, table_name) {#str-int-int-str}
Fügt eine neue PivotTable hinzu.


###  Kehrt zurück

Der neu hinzugefügte Cache-Index.


```python

def add(self, source_data, row, column, table_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| source_data | str | Der Datenzellenbereich für die neue PivotTable.Beispiel: Sheet1!A1:C8|
| row | int |Zeilenindex der Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| column | int | Spaltenindex der Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| table_name | str | Der Name des neuen PivotTable-Berichts.|


##  add(self, pivot_table, row, column, table_name) {#aspose.cells.pivot.PivotTable-int-int-str}
Fügt eine neue PivotTable basierend auf einer anderen PivotTable hinzu.


###  Kehrt zurück

Der neu hinzugefügte PivotTable-Index.


```python

def add(self, pivot_table, row, column, table_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/de/aspose.cells.pivot/pivottable) | Die Quell-PivotTable.|
| row | int |Zeilenindex der Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| column | int | Spaltenindex der Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| table_name | str | Der Name des neuen PivotTable-Berichts.|


##  add(self, source_data, row, column, table_name, use_same_source) {#str-int-int-str-bool}
Fügt eine neue PivotTable hinzu.


###  Kehrt zurück

Der neu hinzugefügte Cache-Index.


```python

def add(self, source_data, row, column, table_name, use_same_source):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| source_data | str | Der Datenzellenbereich für die neue PivotTable.Beispiel: Sheet1!A1:C8|
| row | int |Zeilenindex der Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| column | int | Spaltenindex der Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| table_name | str | Der Name des neuen PivotTable-Berichts.|
| use_same_source | bool | Gibt an, ob dieselbe Datenquelle verwendet wird, wenn eine andere vorhandene Pivot-Tabelle diese Datenquelle verwendet hat.<br/> Wenn die Eigenschaft wahr ist, wird Speicher gespart.|


##  add(self, source_data, cell, table_name, use_same_source, is_xls_classic) {#str-str-str-bool-bool}
Fügt eine neue PivotTable hinzu.


###  Kehrt zurück

Der neu hinzugefügte Cache-Index.


```python

def add(self, source_data, cell, table_name, use_same_source, is_xls_classic):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| source_data | str | Der Datenzellenbereich für die neue PivotTable.Beispiel: Sheet1!A1:C8|
| cell | str | Die Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| table_name | str | Der Name des neuen PivotTable-Berichts.|
| use_same_source | bool | Gibt an, ob dieselbe Datenquelle verwendet wird, wenn eine andere vorhandene Pivot-Tabelle diese Datenquelle verwendet hat.<br/> Wenn die Eigenschaft wahr ist, wird Speicher gespart.|
| is_xls_classic | bool | Gibt an, ob die klassische Pivot-Tabelle von Excel 97-2003 hinzugefügt werden soll.|


##  add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-str-str}
Fügt der Sammlung ein neues PivotTable-Objekt mit mehreren Konsolidierungsbereichen als Datenquelle hinzu.


###  Kehrt zurück

Der neu hinzugefügte PivotTable-Index.


```python

def add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| source_data | list | Die mehreren Konsolidierungsbereiche, wie z. B. {"Sheet1!A1:C8","Sheet2!A1:B8"} |
| is_auto_page | bool | Ob automatisch ein einzelnes Seitenfeld erstellt wird.<br/> Wenn wahr, wird der folgende Parameter „pageFields“ ignoriert.|
| page_fields | [`PivotPageFields`](/cells/python-net/de/aspose.cells.pivot/pivotpagefields) | Die Feldelemente der Pivot-Seite.|
| dest_cell_name | str | destCellName Der Name des neuen PivotTable-Berichts.|
| table_name | str | der Name des neuen PivotTable-Berichts.|


##  add(self, source_data, row, column, table_name, use_same_source, is_xls_classic) {#str-int-int-str-bool-bool}
Fügt eine neue PivotTable hinzu.


###  Kehrt zurück

Der neu hinzugefügte Cache-Index.


```python

def add(self, source_data, row, column, table_name, use_same_source, is_xls_classic):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| source_data | str | Der Datenzellenbereich für die neue PivotTable.Beispiel: Sheet1!A1:C8|
| row | int |Zeilenindex der Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| column | int | Spaltenindex der Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| table_name | str | Der Name des neuen PivotTable-Berichts.|
| use_same_source | bool | Gibt an, ob dieselbe Datenquelle verwendet wird, wenn eine andere vorhandene Pivot-Tabelle diese Datenquelle verwendet hat.<br/> Wenn die Eigenschaft wahr ist, wird Speicher gespart.|
| is_xls_classic | bool | Gibt an, ob die klassische Pivot-Tabelle von Excel 97-2003 hinzugefügt werden soll.|


##  add(self, source_data, is_auto_page, page_fields, row, column, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-int-int-str}
Fügt der Sammlung ein neues PivotTable-Objekt mit mehreren Konsolidierungsbereichen als Datenquelle hinzu.


###  Kehrt zurück

Der neu hinzugefügte PivotTable-Index.


```python

def add(self, source_data, is_auto_page, page_fields, row, column, table_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| source_data | list | Die mehreren Konsolidierungsbereiche, wie z. B. {"Sheet1!A1:C8","Sheet2!A1:B8"} |
| is_auto_page | bool | Ob automatisch ein einzelnes Seitenfeld erstellt wird.<br/> Wenn wahr, wird der folgende Parameter pageFields ignoriert|
| page_fields | [`PivotPageFields`](/cells/python-net/de/aspose.cells.pivot/pivotpagefields) | Die Feldelemente der Pivot-Seite.|
| row | int |Zeilenindex der Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| column | int | Spaltenindex der Zelle in der oberen linken Ecke des Zielbereichs des PivotTable-Berichts.|
| table_name | str | Der Name des neuen PivotTable-Berichts.|



###  Siehe auch
* Modul [`aspose.cells.pivot`](../../)
* Klasse [`PivotTableCollection`](/cells/python-net/de/aspose.cells.pivot/pivottablecollection)
