---
title: add метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.pivot/pivottablecollection/add/
is_root: false
---
##  add(self, source_data, dest_cell_name, table_name) {#str-str-str}
Добавляет новую сводную таблицу.


###  Возврат

Новый добавленный индекс кэша.


```python

def add(self, source_data, dest_cell_name, table_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| source_data | str | Данные для нового кэша сводной таблицы.|
| dest_cell_name | str | Ячейка в левом верхнем углу диапазона назначения отчета сводной таблицы.|
| table_name | str | Название нового отчета сводной таблицы.|


##  add(self, pivot_table, dest_cell_name, table_name) {#aspose.cells.pivot.PivotTable-str-str}
Добавляет новую сводную таблицу на основе другой сводной таблицы.


###  Возврат

Новый добавленный индекс сводной таблицы.


```python

def add(self, pivot_table, dest_cell_name, table_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/ru/aspose.cells.pivot/pivottable) | Исходная сводная таблица.|
| dest_cell_name | str | Ячейка в левом верхнем углу диапазона назначения отчета сводной таблицы.|
| table_name | str | Название нового отчета сводной таблицы.|


##  add(self, source_data, dest_cell_name, table_name, use_same_source) {#str-str-str-bool}
Добавляет новую сводную таблицу.


###  Возврат

Новый добавленный индекс кэша.


```python

def add(self, source_data, dest_cell_name, table_name, use_same_source):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| source_data | str | Данные для нового кэша сводной таблицы.|
| dest_cell_name | str | Ячейка в левом верхнем углу диапазона назначения отчета сводной таблицы.|
| table_name | str | Название нового отчета сводной таблицы.|
| use_same_source | bool | Указывает, используется ли тот же источник данных, если другая существующая сводная таблица использует этот источник данных.<br/> Если свойство истинно, оно будет экономить память.|


##  add(self, source_data, row, column, table_name) {#str-int-int-str}
Добавляет новую сводную таблицу.


###  Возврат

Новый добавленный индекс кэша.


```python

def add(self, source_data, row, column, table_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| source_data | str | Диапазон ячеек данных для новой сводной таблицы. Пример: Лист1!A1:C8|
| row | int |Индекс строки ячейки в левом верхнем углу диапазона назначения отчета сводной таблицы.|
| column | int | Индекс столбца ячейки в верхнем левом углу диапазона назначения отчета сводной таблицы.|
| table_name | str | Название нового отчета сводной таблицы.|


##  add(self, pivot_table, row, column, table_name) {#aspose.cells.pivot.PivotTable-int-int-str}
Добавляет новую сводную таблицу на основе другой сводной таблицы.


###  Возврат

Новый добавленный индекс сводной таблицы.


```python

def add(self, pivot_table, row, column, table_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| pivot_table | [`PivotTable`](/cells/python-net/ru/aspose.cells.pivot/pivottable) | Исходная сводная таблица.|
| row | int |Индекс строки ячейки в левом верхнем углу диапазона назначения отчета сводной таблицы.|
| column | int | Индекс столбца ячейки в верхнем левом углу диапазона назначения отчета сводной таблицы.|
| table_name | str | Название нового отчета сводной таблицы.|


##  add(self, source_data, row, column, table_name, use_same_source) {#str-int-int-str-bool}
Добавляет новую сводную таблицу.


###  Возврат

Новый добавленный индекс кэша.


```python

def add(self, source_data, row, column, table_name, use_same_source):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| source_data | str | Диапазон ячеек данных для новой сводной таблицы. Пример: Лист1!A1:C8|
| row | int |Индекс строки ячейки в левом верхнем углу диапазона назначения отчета сводной таблицы.|
| column | int | Индекс столбца ячейки в верхнем левом углу диапазона назначения отчета сводной таблицы.|
| table_name | str | Название нового отчета сводной таблицы.|
| use_same_source | bool | Указывает, используется ли тот же источник данных, если другая существующая сводная таблица использует этот источник данных.<br/> Если свойство истинно, оно будет экономить память.|


##  add(self, source_data, cell, table_name, use_same_source, is_xls_classic) {#str-str-str-bool-bool}
Добавляет новую сводную таблицу.


###  Возврат

Новый добавленный индекс кэша.


```python

def add(self, source_data, cell, table_name, use_same_source, is_xls_classic):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| source_data | str | Диапазон ячеек данных для новой сводной таблицы. Пример: Лист1!A1:C8|
| cell | str | Ячейка в левом верхнем углу диапазона назначения отчета сводной таблицы.|
| table_name | str | Название нового отчета сводной таблицы.|
| use_same_source | bool | Указывает, используется ли тот же источник данных, если другая существующая сводная таблица использует этот источник данных.<br/> Если свойство истинно, оно будет экономить память.|
| is_xls_classic | bool | Указывает, следует ли добавлять классическую сводную таблицу Excel 97-2003.|


##  add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-str-str}
Добавляет новый объект сводной таблицы в коллекцию с несколькими диапазонами консолидации в качестве источника данных.


###  Возврат

Новый добавленный индекс сводной таблицы.


```python

def add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| source_data | list | Несколько диапазонов консолидации, например {"Лист1!A1:C8","Лист2!A1:B8"} |
| is_auto_page | bool | Создавать ли автоматически одностраничное поле.<br/> Если true, то следующий параметр pageFields будет проигнорирован.|
| page_fields | [`PivotPageFields`](/cells/python-net/ru/aspose.cells.pivot/pivotpagefields) | Элементы полей сводной страницы.|
| dest_cell_name | str | destCellName Имя нового отчета сводной таблицы.|
| table_name | str | имя нового отчета сводной таблицы.|


##  add(self, source_data, row, column, table_name, use_same_source, is_xls_classic) {#str-int-int-str-bool-bool}
Добавляет новую сводную таблицу.


###  Возврат

Новый добавленный индекс кэша.


```python

def add(self, source_data, row, column, table_name, use_same_source, is_xls_classic):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| source_data | str | Диапазон ячеек данных для новой сводной таблицы. Пример: Лист1!A1:C8|
| row | int |Индекс строки ячейки в левом верхнем углу диапазона назначения отчета сводной таблицы.|
| column | int | Индекс столбца ячейки в верхнем левом углу диапазона назначения отчета сводной таблицы.|
| table_name | str | Название нового отчета сводной таблицы.|
| use_same_source | bool | Указывает, используется ли тот же источник данных, если другая существующая сводная таблица использует этот источник данных.<br/> Если свойство истинно, оно будет экономить память.|
| is_xls_classic | bool | Указывает, следует ли добавлять классическую сводную таблицу Excel 97-2003.|


##  add(self, source_data, is_auto_page, page_fields, row, column, table_name) {#list-bool-aspose.cells.pivot.PivotPageFields-int-int-str}
Добавляет новый объект сводной таблицы в коллекцию с несколькими диапазонами консолидации в качестве источника данных.


###  Возврат

Новый добавленный индекс сводной таблицы.


```python

def add(self, source_data, is_auto_page, page_fields, row, column, table_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| source_data | list | Несколько диапазонов консолидации, например {"Лист1!A1:C8","Лист2!A1:B8"} |
| is_auto_page | bool | Создавать ли автоматически одностраничное поле.<br/> Если true, следующий параметр pageFields будет проигнорирован.|
| page_fields | [`PivotPageFields`](/cells/python-net/ru/aspose.cells.pivot/pivotpagefields) | Элементы полей сводной страницы.|
| row | int |Индекс строки ячейки в левом верхнем углу диапазона назначения отчета сводной таблицы.|
| column | int | Индекс столбца ячейки в верхнем левом углу диапазона назначения отчета сводной таблицы.|
| table_name | str | Название нового отчета сводной таблицы.|



###  Смотрите также
* модуль [`aspose.cells.pivot`](../../)
* класс [`PivotTableCollection`](/cells/python-net/ru/aspose.cells.pivot/pivottablecollection)
