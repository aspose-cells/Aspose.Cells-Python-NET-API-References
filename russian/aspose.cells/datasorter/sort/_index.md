---
title: sort метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 50
url: /ru/aspose.cells/datasorter/sort/
is_root: false
---
##  sort(self) {#}
Отсортируйте данные в диапазоне.


###  Возврат

исходные индексы (абсолютная позиция, например, столбец A равен 0, B равен 1, ...) отсортированных строк/столбцов.
Если в ходе этой операции сортировки не требуется перемещать строки/столбцы, будет возвращено значение null.


```python

def sort(self):
    ...
```




##  sort(self, cells, area) {#aspose.cells.Cells-aspose.cells.CellArea}
Сортировать данные по области.


###  Возврат

исходные индексы (абсолютная позиция, например, столбец A равен 0, B равен 1, ...) отсортированных строк/столбцов.
Если в ходе этой операции сортировки не требуется перемещать строки/столбцы, будет возвращено значение null.


```python

def sort(self, cells, area):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| cells | [`Cells`](/cells/python-net/ru/aspose.cells/cells) | Ячейки содержат область данных.|
| area | [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea) | Площадь, необходимая для сортировки|


##  sort(self, cells, start_row, start_column, end_row, end_column) {#aspose.cells.Cells-int-int-int-int}
Сортирует данные по области.


###  Возврат

исходные индексы (абсолютная позиция, например, столбец A равен 0, B равен 1, ...) отсортированных строк/столбцов.
Если в ходе этой операции сортировки не требуется перемещать строки/столбцы, будет возвращено значение null.


```python

def sort(self, cells, start_row, start_column, end_row, end_column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| cells | [`Cells`](/cells/python-net/ru/aspose.cells/cells) | Ячейки содержат область данных.|
| start_row | int | Начальный ряд области.|
| start_column | int | Начальный столбец области.|
| end_row | int | Конечный ряд области.|
| end_column | int | Конечный столбец области.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`DataSorter`](/cells/python-net/ru/aspose.cells/datasorter)
