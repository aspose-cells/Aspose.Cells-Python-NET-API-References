---
title: merge метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 800
url: /ru/aspose.cells/cells/merge/
is_root: false
---
##  merge(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Объединяет указанный диапазон ячеек в одну ячейку.



```python

def merge(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| first_row | int | Первая строка этого диапазона (отсчет начинается с нуля)|
| first_column | int | Первый столбец этого диапазона (отсчет начинается с нуля)|
| total_rows | int |Количество строк (на основе одной)|
| total_columns | int | Количество столбцов (на основе одного)|
###  Примечания

Ссылайтесь на объединенную ячейку через адрес верхней левой ячейки в диапазоне.

##  merge(self, first_row, first_column, total_rows, total_columns, merge_conflict) {#int-int-int-int-bool}

Объединяет указанный диапазон ячеек в одну ячейку.



```python

def merge(self, first_row, first_column, total_rows, total_columns, merge_conflict):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| first_row | int | Первая строка этого диапазона (отсчет начинается с нуля)|
| first_column | int | Первый столбец этого диапазона (отсчет начинается с нуля)|
| total_rows | int |Количество строк (на основе одной)|
| total_columns | int | Количество столбцов (на основе одного)|
| merge_conflict | bool | Объединение конфликтующих диапазонов.|
###  Примечания

Ссылайтесь на объединенную ячейку через адрес верхней левой ячейки в диапазоне.
Если mergeConflict имеет значение true и объединенный диапазон конфликтует с другими объединенными ячейками,
остальные объединенные ячейки будут автоматически удалены.

##  merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict) {#int-int-int-int-bool-bool}
Объединяет указанный диапазон ячеек в одну ячейку.



```python

def merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| first_row | int | Первая строка этого диапазона (отсчет начинается с нуля)|
| first_column | int | Первый столбец этого диапазона (отсчет начинается с нуля)|
| total_rows | int |Количество строк (на основе одной)|
| total_columns | int | Количество столбцов (на основе одного)|
| check_conflict | bool | Указывает, пересекаются ли объединенные ячейки с другими объединенными ячейками.|
| merge_conflict | bool | Объединение конфликтующих диапазонов.|
###  Примечания

Ссылайтесь на объединенную ячейку через адрес верхней левой ячейки в диапазоне.
Если mergeConflict имеет значение true и объединенный диапазон конфликтует с другими объединенными ячейками,
остальные объединенные ячейки будут автоматически удалены.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
