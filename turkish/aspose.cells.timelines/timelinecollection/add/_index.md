---
title: add yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells.timelines/timelinecollection/add/
is_root: false
---
##  add(self, pivot, dest_cell_name, base_field_name) {#aspose.cells.pivot.PivotTable-str-str}
PivotTable'ı veri kaynağı olarak kullanarak yeni bir Zaman Çizelgesi ekleyin


###  İadeler

Yeni add Zaman Çizelgesi dizini


```python

def add(self, pivot, dest_cell_name, base_field_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | PivotTable nesnesi|
| dest_cell_name | str | Zaman Çizelgesi aralığının sol üst köşesindeki hücre adı.|
| base_field_name | str | PivotTable.BaseFields'daki PivotField'ın adı|

###  Örnek

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i15", "date")

```


##  add(self, pivot, dest_cell_name, base_field_index) {#aspose.cells.pivot.PivotTable-str-int}
PivotTable'ı veri kaynağı olarak kullanarak yeni bir Zaman Çizelgesi ekleyin


###  İadeler

Yeni add Zaman Çizelgesi dizini


```python

def add(self, pivot, dest_cell_name, base_field_index):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | PivotTable nesnesi|
| dest_cell_name | str | Zaman Çizelgesi aralığının sol üst köşesindeki hücre adı.|
| base_field_index | int | PivotTable.BaseFields'daki PivotField dizini|

###  Örnek

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i5", 1)

```


##  add(self, pivot, dest_cell_name, base_field) {#aspose.cells.pivot.PivotTable-str-aspose.cells.pivot.PivotField}
PivotTable'ı veri kaynağı olarak kullanarak yeni bir Zaman Çizelgesi ekleyin


###  İadeler

Yeni add Zaman Çizelgesi dizini


```python

def add(self, pivot, dest_cell_name, base_field):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | PivotTable nesnesi|
| dest_cell_name | str | Zaman Çizelgesi aralığının sol üst köşesindeki hücre adı.|
| base_field | aspose.cells.pivot.PivotField | PivotTable.BaseFields'daki PivotField|

###  Örnek

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i10", pivot.base_fields[1])

```


##  add(self, pivot, row, column, base_field_name) {#aspose.cells.pivot.PivotTable-int-int-str}
PivotTable'ı veri kaynağı olarak kullanarak yeni bir Zaman Çizelgesi ekleyin


###  İadeler

Yeni add Zaman Çizelgesi dizini


```python

def add(self, pivot, row, column, base_field_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | PivotTable nesnesi|
| row | int |Zaman Çizelgesi aralığının sol üst köşesindeki hücrenin satır dizini.|
| column | int | Zaman Çizelgesi aralığının sol üst köşesindeki hücrenin sütun dizini.|
| base_field_name | str | PivotTable.BaseFields'daki PivotField'ın adı|

###  Örnek

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 10, 5, "date")

```


##  add(self, pivot, row, column, base_field_index) {#aspose.cells.pivot.PivotTable-int-int-int}
PivotTable'ı veri kaynağı olarak kullanarak yeni bir Zaman Çizelgesi ekleyin


###  İadeler

Yeni add Zaman Çizelgesi dizini


```python

def add(self, pivot, row, column, base_field_index):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | PivotTable nesnesi|
| row | int |Zaman Çizelgesi aralığının sol üst köşesindeki hücrenin satır dizini.|
| column | int | Zaman Çizelgesi aralığının sol üst köşesindeki hücrenin sütun dizini.|
| base_field_index | int | PivotTable.BaseFields'daki PivotField dizini|

###  Örnek

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 15, 5, 1)

```


##  add(self, pivot, row, column, base_field) {#aspose.cells.pivot.PivotTable-int-int-aspose.cells.pivot.PivotField}
PivotTable'ı veri kaynağı olarak kullanarak yeni bir Zaman Çizelgesi ekleyin


###  İadeler

Yeni add Zaman Çizelgesi dizini


```python

def add(self, pivot, row, column, base_field):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | PivotTable nesnesi|
| row | int |Zaman Çizelgesi aralığının sol üst köşesindeki hücrenin satır dizini.|
| column | int | Zaman Çizelgesi aralığının sol üst köşesindeki hücrenin sütun dizini.|
| base_field | aspose.cells.pivot.PivotField | PivotTable.BaseFields'daki PivotField|

###  Örnek

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 20, 5, pivot.base_fields[1])

```



###  Ayrıca bakınız
* modül [`aspose.cells.timelines`](../../)
* sınıf [`TimelineCollection`](/cells/python-net/tr/aspose.cells.timelines/timelinecollection)
