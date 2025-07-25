---
title: auto_fit_row метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 60
url: /ru/aspose.cells/worksheet/auto_fit_row/
is_root: false
---
##  auto_fit_row(self, row_index) {#int}
Автоматически подбирает высоту строки.



```python

def auto_fit_row(self, row_index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row_index | int | Индекс строки.|
###  Примечания

AutoFitRow — неточная функция.

##  auto_fit_row(self, row_index, first_column, last_column) {#int-int-int}

Автоматически подбирает высоту строки.



```python

def auto_fit_row(self, row_index, first_column, last_column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row_index | int | Индекс строки.|
| first_column | int | Индекс первого столбца.|
| last_column | int | Индекс последнего столбца.|
###  Примечания

Этот метод автоматически подбирает строку на основе содержимого диапазона ячеек внутри строки.

##  auto_fit_row(self, row_index, first_column, last_column, options) {#int-int-int-aspose.cells.AutoFitterOptions}

Автоматически подбирает высоту строки.



```python

def auto_fit_row(self, row_index, first_column, last_column, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row_index | int | Индекс строки.|
| first_column | int | Индекс первого столбца.|
| last_column | int | Индекс последнего столбца.|
| options | [`AutoFitterOptions`](/cells/python-net/ru/aspose.cells/autofitteroptions) | Параметры автоустановщика|
###  Примечания

Этот метод автоматически подбирает строку на основе содержимого диапазона ячеек внутри строки.

##  auto_fit_row(self, start_row, end_row, start_column, end_column) {#int-int-int-int}

Автоматически подбирает высоту строки в прямоугольном диапазоне.



```python

def auto_fit_row(self, start_row, end_row, start_column, end_column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| start_row | int | Начальный индекс строки.|
| end_row | int | Индекс конца строки.|
| start_column | int |Начальный индекс столбца.|
| end_column | int | Индекс конечного столбца.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet)
