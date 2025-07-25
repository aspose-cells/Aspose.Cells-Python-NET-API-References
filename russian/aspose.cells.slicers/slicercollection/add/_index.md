---
title: add метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.slicers/slicercollection/add/
is_root: false
---
##  add(self, pivot, dest_cell_name, base_field_name) {#aspose.cells.pivot.PivotTable-str-str}
Добавить новый срез, используя сводную таблицу в качестве источника данных


###  Возврат

Новый индекс слайсера add


```python

def add(self, pivot, dest_cell_name, base_field_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | объект сводной таблицы|
| dest_cell_name | str | Ячейка в верхнем левом углу диапазона среза.|
| base_field_name | str | Имя PivotField в PivotTable.BaseFields|

###  Пример

```python

slicers.add(pivot, "E3", "fruit")

```


##  add(self, pivot, dest_cell_name, base_field_index) {#aspose.cells.pivot.PivotTable-str-int}
Добавить новый срез, используя сводную таблицу в качестве источника данных


###  Возврат

Новый индекс слайсера add


```python

def add(self, pivot, dest_cell_name, base_field_index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | объект сводной таблицы|
| dest_cell_name | str | Ячейка в верхнем левом углу диапазона среза.|
| base_field_index | int | Индекс PivotField в PivotTable.BaseFields|

###  Пример

```python

slicers.add(pivot, "E20", 0)

```


##  add(self, pivot, dest_cell_name, base_field) {#aspose.cells.pivot.PivotTable-str-aspose.cells.pivot.PivotField}
Добавить новый срез, используя сводную таблицу в качестве источника данных


###  Возврат

Новый индекс слайсера add


```python

def add(self, pivot, dest_cell_name, base_field):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | объект сводной таблицы|
| dest_cell_name | str | Ячейка в верхнем левом углу диапазона среза.|
| base_field | aspose.cells.pivot.PivotField | PivotField в PivotTable.BaseFields|

###  Пример

```python

slicers.add(pivot, "I3", pivot.base_fields[0])

```


##  add(self, table, index, dest_cell_name) {#aspose.cells.tables.ListObject-int-str}
Добавить новый слайсер, используя ListObjet в качестве источника данных


###  Возврат

Новый индекс слайсера add


```python

def add(self, table, index, dest_cell_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | объект ListObject|
| index | int | Индекс ListColumn в ListObject.ListColumns|
| dest_cell_name | str | Ячейка в верхнем левом углу диапазона среза.|

###  Пример

```python

slicers.add(table, 1, "E38")

```


##  add(self, table, list_column, dest_cell_name) {#aspose.cells.tables.ListObject-aspose.cells.tables.ListColumn-str}
Добавить новый слайсер, используя ListObjet в качестве источника данных


###  Возврат

Новый индекс слайсера add


```python

def add(self, table, list_column, dest_cell_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | объект ListObject|
| list_column | aspose.cells.tables.ListColumn | ListColumn в ListObject.ListColumns|
| dest_cell_name | str | Ячейка в верхнем левом углу диапазона среза.|

###  Пример

```python

slicers.add(table, table.list_columns[1], "I38")

```


##  add(self, pivot, row, column, base_field_name) {#aspose.cells.pivot.PivotTable-int-int-str}
Добавить новый срез, используя сводную таблицу в качестве источника данных


###  Возврат

Новый индекс слайсера add


```python

def add(self, pivot, row, column, base_field_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | объект сводной таблицы|
| row | int | Индекс строки ячейки в верхнем левом углу диапазона среза.|
| column | int | Индекс столбца ячейки в верхнем левом углу диапазона среза.|
| base_field_name | str | Имя PivotField в PivotTable.BaseFields|

###  Пример

```python

slicers.add(pivot, 20, 12, "fruit")

```


##  add(self, pivot, row, column, base_field_index) {#aspose.cells.pivot.PivotTable-int-int-int}
Добавить новый срез, используя сводную таблицу в качестве источника данных


###  Возврат

Новый индекс слайсера add


```python

def add(self, pivot, row, column, base_field_index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | объект сводной таблицы|
| row | int | Индекс строки ячейки в верхнем левом углу диапазона среза.|
| column | int | Индекс столбца ячейки в верхнем левом углу диапазона среза.|
| base_field_index | int | Индекс PivotField в PivotTable.BaseFields|

###  Пример

```python

slicers.add(pivot, 20, 8, 0)

```


##  add(self, pivot, row, column, base_field) {#aspose.cells.pivot.PivotTable-int-int-aspose.cells.pivot.PivotField}
Добавить новый срез, используя сводную таблицу в качестве источника данных


###  Возврат

Новый индекс слайсера add


```python

def add(self, pivot, row, column, base_field):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | объект сводной таблицы|
| row | int | Индекс строки ячейки в верхнем левом углу диапазона среза.|
| column | int | Индекс столбца ячейки в верхнем левом углу диапазона среза.|
| base_field | aspose.cells.pivot.PivotField | PivotField в PivotTable.BaseFields|

###  Пример

```python

slicers.add(pivot, 3, 12, pivot.base_fields[0])

```


##  add(self, table, list_column, row, column) {#aspose.cells.tables.ListObject-aspose.cells.tables.ListColumn-int-int}
Добавить новый слайсер, используя ListObjet в качестве источника данных


###  Возврат

Новый индекс слайсера add


```python

def add(self, table, list_column, row, column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | объект ListObject|
| list_column | aspose.cells.tables.ListColumn | ListColumn в ListObject.ListColumns|
| row | int | Индекс строки ячейки в верхнем левом углу диапазона среза.|
| column | int | Индекс столбца ячейки в верхнем левом углу диапазона среза.|

###  Пример

```python

slicers.add(table, table.list_columns[1], 38, 12)

```



###  Смотрите также
* модуль [`aspose.cells.slicers`](../../)
* класс [`SlicerCollection`](/cells/python-net/ru/aspose.cells.slicers/slicercollection)
