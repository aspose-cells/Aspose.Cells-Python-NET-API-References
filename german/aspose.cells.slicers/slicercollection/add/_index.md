---
title: add Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.slicers/slicercollection/add/
is_root: false
---
##  add(self, pivot, dest_cell_name, base_field_name) {#aspose.cells.pivot.PivotTable-str-str}
Fügen Sie einen neuen Slicer hinzu, der PivotTable als Datenquelle verwendet


###  Kehrt zurück

Der neue Slicer-Index add


```python

def add(self, pivot, dest_cell_name, base_field_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | PivotTable-Objekt|
| dest_cell_name | str | Die Zelle in der oberen linken Ecke des Slicer-Bereichs.|
| base_field_name | str | Der Name des PivotFields in PivotTable.BaseFields|

###  Beispiel

```python

slicers.add(pivot, "E3", "fruit")

```


##  add(self, pivot, dest_cell_name, base_field_index) {#aspose.cells.pivot.PivotTable-str-int}
Fügen Sie einen neuen Slicer hinzu, der PivotTable als Datenquelle verwendet


###  Kehrt zurück

Der neue Slicer-Index add


```python

def add(self, pivot, dest_cell_name, base_field_index):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | PivotTable-Objekt|
| dest_cell_name | str | Die Zelle in der oberen linken Ecke des Slicer-Bereichs.|
| base_field_index | int | Der Index von PivotField in PivotTable.BaseFields|

###  Beispiel

```python

slicers.add(pivot, "E20", 0)

```


##  add(self, pivot, dest_cell_name, base_field) {#aspose.cells.pivot.PivotTable-str-aspose.cells.pivot.PivotField}
Fügen Sie einen neuen Slicer hinzu, der PivotTable als Datenquelle verwendet


###  Kehrt zurück

Der neue Slicer-Index add


```python

def add(self, pivot, dest_cell_name, base_field):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | PivotTable-Objekt|
| dest_cell_name | str | Die Zelle in der oberen linken Ecke des Slicer-Bereichs.|
| base_field | aspose.cells.pivot.PivotField | Das PivotField in PivotTable.BaseFields|

###  Beispiel

```python

slicers.add(pivot, "I3", pivot.base_fields[0])

```


##  add(self, table, index, dest_cell_name) {#aspose.cells.tables.ListObject-int-str}
Fügen Sie einen neuen Slicer hinzu, der ListObjet als Datenquelle verwendet


###  Kehrt zurück

Der neue Slicer-Index add


```python

def add(self, table, index, dest_cell_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | ListObject-Objekt|
| index | int | Der Index von ListColumn in ListObject.ListColumns|
| dest_cell_name | str | Die Zelle in der oberen linken Ecke des Slicer-Bereichs.|

###  Beispiel

```python

slicers.add(table, 1, "E38")

```


##  add(self, table, list_column, dest_cell_name) {#aspose.cells.tables.ListObject-aspose.cells.tables.ListColumn-str}
Fügen Sie einen neuen Slicer hinzu, der ListObjet als Datenquelle verwendet


###  Kehrt zurück

Der neue Slicer-Index add


```python

def add(self, table, list_column, dest_cell_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | ListObject-Objekt|
| list_column | aspose.cells.tables.ListColumn | Die ListColumn in ListObject.ListColumns|
| dest_cell_name | str | Die Zelle in der oberen linken Ecke des Slicer-Bereichs.|

###  Beispiel

```python

slicers.add(table, table.list_columns[1], "I38")

```


##  add(self, pivot, row, column, base_field_name) {#aspose.cells.pivot.PivotTable-int-int-str}
Fügen Sie einen neuen Slicer hinzu, der PivotTable als Datenquelle verwendet


###  Kehrt zurück

Der neue Slicer-Index add


```python

def add(self, pivot, row, column, base_field_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | PivotTable-Objekt|
| row | int | Zeilenindex der Zelle in der oberen linken Ecke des Slicer-Bereichs.|
| column | int | Spaltenindex der Zelle in der oberen linken Ecke des Slicer-Bereichs.|
| base_field_name | str | Der Name des PivotFields in PivotTable.BaseFields|

###  Beispiel

```python

slicers.add(pivot, 20, 12, "fruit")

```


##  add(self, pivot, row, column, base_field_index) {#aspose.cells.pivot.PivotTable-int-int-int}
Fügen Sie einen neuen Slicer hinzu, der PivotTable als Datenquelle verwendet


###  Kehrt zurück

Der neue Slicer-Index add


```python

def add(self, pivot, row, column, base_field_index):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | PivotTable-Objekt|
| row | int | Zeilenindex der Zelle in der oberen linken Ecke des Slicer-Bereichs.|
| column | int | Spaltenindex der Zelle in der oberen linken Ecke des Slicer-Bereichs.|
| base_field_index | int | Der Index von PivotField in PivotTable.BaseFields|

###  Beispiel

```python

slicers.add(pivot, 20, 8, 0)

```


##  add(self, pivot, row, column, base_field) {#aspose.cells.pivot.PivotTable-int-int-aspose.cells.pivot.PivotField}
Fügen Sie einen neuen Slicer hinzu, der PivotTable als Datenquelle verwendet


###  Kehrt zurück

Der neue Slicer-Index add


```python

def add(self, pivot, row, column, base_field):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | PivotTable-Objekt|
| row | int | Zeilenindex der Zelle in der oberen linken Ecke des Slicer-Bereichs.|
| column | int | Spaltenindex der Zelle in der oberen linken Ecke des Slicer-Bereichs.|
| base_field | aspose.cells.pivot.PivotField | Das PivotField in PivotTable.BaseFields|

###  Beispiel

```python

slicers.add(pivot, 3, 12, pivot.base_fields[0])

```


##  add(self, table, list_column, row, column) {#aspose.cells.tables.ListObject-aspose.cells.tables.ListColumn-int-int}
Fügen Sie einen neuen Slicer hinzu, der ListObjet als Datenquelle verwendet


###  Kehrt zurück

Der neue Slicer-Index add


```python

def add(self, table, list_column, row, column):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | ListObject-Objekt|
| list_column | aspose.cells.tables.ListColumn | Die ListColumn in ListObject.ListColumns|
| row | int | Zeilenindex der Zelle in der oberen linken Ecke des Slicer-Bereichs.|
| column | int | Spaltenindex der Zelle in der oberen linken Ecke des Slicer-Bereichs.|

###  Beispiel

```python

slicers.add(table, table.list_columns[1], 38, 12)

```



###  Siehe auch
* Modul [`aspose.cells.slicers`](../../)
* Klasse [`SlicerCollection`](/cells/python-net/de/aspose.cells.slicers/slicercollection)
