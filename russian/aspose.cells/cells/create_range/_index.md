---
title: create_range метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 190
url: /ru/aspose.cells/cells/create_range/
is_root: false
---
##  create_range(self, address) {#str}
Создает объект [`Range`](/cells/python-net/ru/aspose.cells/range) из адреса диапазона.


###  Возврат

Объект [`Range`](/cells/python-net/ru/aspose.cells/range)


```python

def create_range(self, address):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| address | str | Адрес диапазона.|


##  create_range(self, upper_left_cell, lower_right_cell) {#str-str}
Создает объект [`Range`](/cells/python-net/ru/aspose.cells/range) из диапазона ячеек.


###  Возврат

Объект [`Range`](/cells/python-net/ru/aspose.cells/range)


```python

def create_range(self, upper_left_cell, lower_right_cell):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_cell | str | Имя ячейки в левом верхнем углу.|
| lower_right_cell | str | Имя ячейки в правом нижнем углу.|


##  create_range(self, first_index, number, is_vertical) {#int-int-bool}
Создает объект [`Range`](/cells/python-net/ru/aspose.cells/range) из строк ячеек или столбцов ячеек.


###  Возврат

Объект [`Range`](/cells/python-net/ru/aspose.cells/range).


```python

def create_range(self, first_index, number, is_vertical):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| first_index | int | Индекс первой строки или индекс первого столбца, отсчитываемый от нуля.|
| number | int | Общее количество строк или столбцов, начиная с единицы.|
| is_vertical | bool | True — диапазон создан из столбцов ячеек. False — диапазон создан из строк ячеек.|


##  create_range(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Создает объект [`Range`](/cells/python-net/ru/aspose.cells/range) из диапазона ячеек.


###  Возврат

Объект [`Range`](/cells/python-net/ru/aspose.cells/range)


```python

def create_range(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| first_row | int |Первый ряд этого диапазона|
| first_column | int | Первый столбец этого диапазона|
| total_rows | int | Количество рядов|
| total_columns | int | Количество столбцов|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
* класс [`Range`](/cells/python-net/ru/aspose.cells/range)
