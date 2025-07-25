---
title: add метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.timelines/timelinecollection/add/
is_root: false
---
##  add(self, pivot, dest_cell_name, base_field_name) {#aspose.cells.pivot.PivotTable-str-str}
Добавьте новую временную шкалу, используя сводную таблицу в качестве источника данных.


###  Возврат

Новый индекс временной шкалы add


```python

def add(self, pivot, dest_cell_name, base_field_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | объект сводной таблицы|
| dest_cell_name | str | Имя ячейки в левом верхнем углу диапазона временной шкалы.|
| base_field_name | str | Имя PivotField в PivotTable.BaseFields|

###  Пример

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i15", "date")

```


##  add(self, pivot, dest_cell_name, base_field_index) {#aspose.cells.pivot.PivotTable-str-int}
Добавьте новую временную шкалу, используя сводную таблицу в качестве источника данных.


###  Возврат

Новый индекс временной шкалы add


```python

def add(self, pivot, dest_cell_name, base_field_index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | объект сводной таблицы|
| dest_cell_name | str | Имя ячейки в левом верхнем углу диапазона временной шкалы.|
| base_field_index | int | Индекс PivotField в PivotTable.BaseFields|

###  Пример

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i5", 1)

```


##  add(self, pivot, dest_cell_name, base_field) {#aspose.cells.pivot.PivotTable-str-aspose.cells.pivot.PivotField}
Добавьте новую временную шкалу, используя сводную таблицу в качестве источника данных.


###  Возврат

Новый индекс временной шкалы add


```python

def add(self, pivot, dest_cell_name, base_field):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | объект сводной таблицы|
| dest_cell_name | str | Имя ячейки в левом верхнем углу диапазона временной шкалы.|
| base_field | aspose.cells.pivot.PivotField | PivotField в PivotTable.BaseFields|

###  Пример

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i10", pivot.base_fields[1])

```


##  add(self, pivot, row, column, base_field_name) {#aspose.cells.pivot.PivotTable-int-int-str}
Добавьте новую временную шкалу, используя сводную таблицу в качестве источника данных.


###  Возврат

Новый индекс временной шкалы add


```python

def add(self, pivot, row, column, base_field_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | объект сводной таблицы|
| row | int |Индекс строки ячейки в верхнем левом углу диапазона временной шкалы.|
| column | int | Индекс столбца ячейки в верхнем левом углу диапазона временной шкалы.|
| base_field_name | str | Имя PivotField в PivotTable.BaseFields|

###  Пример

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 10, 5, "date")

```


##  add(self, pivot, row, column, base_field_index) {#aspose.cells.pivot.PivotTable-int-int-int}
Добавьте новую временную шкалу, используя сводную таблицу в качестве источника данных.


###  Возврат

Новый индекс временной шкалы add


```python

def add(self, pivot, row, column, base_field_index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | объект сводной таблицы|
| row | int |Индекс строки ячейки в верхнем левом углу диапазона временной шкалы.|
| column | int | Индекс столбца ячейки в верхнем левом углу диапазона временной шкалы.|
| base_field_index | int | Индекс PivotField в PivotTable.BaseFields|

###  Пример

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 15, 5, 1)

```


##  add(self, pivot, row, column, base_field) {#aspose.cells.pivot.PivotTable-int-int-aspose.cells.pivot.PivotField}
Добавьте новую временную шкалу, используя сводную таблицу в качестве источника данных.


###  Возврат

Новый индекс временной шкалы add


```python

def add(self, pivot, row, column, base_field):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | объект сводной таблицы|
| row | int |Индекс строки ячейки в верхнем левом углу диапазона временной шкалы.|
| column | int | Индекс столбца ячейки в верхнем левом углу диапазона временной шкалы.|
| base_field | aspose.cells.pivot.PivotField | PivotField в PivotTable.BaseFields|

###  Пример

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 20, 5, pivot.base_fields[1])

```



###  Смотрите также
* модуль [`aspose.cells.timelines`](../../)
* класс [`TimelineCollection`](/cells/python-net/ru/aspose.cells.timelines/timelinecollection)
