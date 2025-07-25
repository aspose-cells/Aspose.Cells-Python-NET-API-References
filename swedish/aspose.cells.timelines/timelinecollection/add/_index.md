---
title: add metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.timelines/timelinecollection/add/
is_root: false
---
##  add(self, pivot, dest_cell_name, base_field_name) {#aspose.cells.pivot.PivotTable-str-str}
Lägg till en ny tidslinje med hjälp av pivottabell som datakälla


###  Returnerar

Det nya tidslinjeindexet add


```python

def add(self, pivot, dest_cell_name, base_field_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | Pivottabellobjekt|
| dest_cell_name | str | Cellnamnet i det övre vänstra hörnet av tidslinjeområdet.|
| base_field_name | str | Namnet på PivotField i PivotTable.BaseFields|

###  Exempel

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i15", "date")

```


##  add(self, pivot, dest_cell_name, base_field_index) {#aspose.cells.pivot.PivotTable-str-int}
Lägg till en ny tidslinje med hjälp av pivottabell som datakälla


###  Returnerar

Det nya tidslinjeindexet add


```python

def add(self, pivot, dest_cell_name, base_field_index):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | Pivottabellobjekt|
| dest_cell_name | str | Cellnamnet i det övre vänstra hörnet av tidslinjeområdet.|
| base_field_index | int | Indexet för PivotField i PivotTable.BaseFields|

###  Exempel

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i5", 1)

```


##  add(self, pivot, dest_cell_name, base_field) {#aspose.cells.pivot.PivotTable-str-aspose.cells.pivot.PivotField}
Lägg till en ny tidslinje med hjälp av pivottabell som datakälla


###  Returnerar

Det nya tidslinjeindexet add


```python

def add(self, pivot, dest_cell_name, base_field):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | Pivottabellobjekt|
| dest_cell_name | str | Cellnamnet i det övre vänstra hörnet av tidslinjeområdet.|
| base_field | aspose.cells.pivot.PivotField | Pivotfältet i PivotTable.BaseFields|

###  Exempel

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i10", pivot.base_fields[1])

```


##  add(self, pivot, row, column, base_field_name) {#aspose.cells.pivot.PivotTable-int-int-str}
Lägg till en ny tidslinje med hjälp av pivottabell som datakälla


###  Returnerar

Det nya tidslinjeindexet add


```python

def add(self, pivot, row, column, base_field_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | Pivottabellobjekt|
| row | int |Radindex för cellen i det övre vänstra hörnet av tidslinjeområdet.|
| column | int | Kolumnindex för cellen i det övre vänstra hörnet av tidslinjeområdet.|
| base_field_name | str | Namnet på PivotField i PivotTable.BaseFields|

###  Exempel

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 10, 5, "date")

```


##  add(self, pivot, row, column, base_field_index) {#aspose.cells.pivot.PivotTable-int-int-int}
Lägg till en ny tidslinje med hjälp av pivottabell som datakälla


###  Returnerar

Det nya tidslinjeindexet add


```python

def add(self, pivot, row, column, base_field_index):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | Pivottabellobjekt|
| row | int |Radindex för cellen i det övre vänstra hörnet av tidslinjeområdet.|
| column | int | Kolumnindex för cellen i det övre vänstra hörnet av tidslinjeområdet.|
| base_field_index | int | Indexet för PivotField i PivotTable.BaseFields|

###  Exempel

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 15, 5, 1)

```


##  add(self, pivot, row, column, base_field) {#aspose.cells.pivot.PivotTable-int-int-aspose.cells.pivot.PivotField}
Lägg till en ny tidslinje med hjälp av pivottabell som datakälla


###  Returnerar

Det nya tidslinjeindexet add


```python

def add(self, pivot, row, column, base_field):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | Pivottabellobjekt|
| row | int |Radindex för cellen i det övre vänstra hörnet av tidslinjeområdet.|
| column | int | Kolumnindex för cellen i det övre vänstra hörnet av tidslinjeområdet.|
| base_field | aspose.cells.pivot.PivotField | Pivotfältet i PivotTable.BaseFields|

###  Exempel

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 20, 5, pivot.base_fields[1])

```



###  Se även
* modul [`aspose.cells.timelines`](../../)
* klass [`TimelineCollection`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection)
