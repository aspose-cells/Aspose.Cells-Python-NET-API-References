---
title: remove_duplicates метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 800
url: /ru/aspose.cells/cells/remove_duplicates/
is_root: false
---
##  remove_duplicates {#}
Удаляет повторяющиеся строки на листе.



```python
def remove_duplicates(self):
    ...
```




##  remove_duplicates {#int-int-int-int}
Удаляет повторяющиеся значения в диапазоне.



```python
def remove_duplicates(self, start_row, start_column, end_row, end_column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| start_row | int | Стартовый ряд.|
| start_column | int | Начальный столбец|
| end_row | int | Индекс конечной строки.|
| end_column | int | Индекс конечного столбца.|


##  remove_duplicates {#int-int-int-int-bool-list}
Удаляет повторяющиеся данные диапазона.



```python
def remove_duplicates(self, start_row, start_column, end_row, end_column, has_headers, column_offsets):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| start_row | int | Стартовый ряд.|
| start_column | int | Начальный столбец|
| end_row | int | Индекс конечной строки.|
| end_column | int | Индекс конечного столбца.|
| has_headers | bool | Указывает, содержит ли диапазон заголовки.|
| column_offsets | list | Столбец смещается.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
