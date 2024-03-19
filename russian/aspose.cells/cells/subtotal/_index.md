---
title: subtotal метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 910
url: /ru/aspose.cells/cells/subtotal/
is_root: false
---
##  subtotal {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list}
Создает промежуточные итоги для диапазона.



```python
def subtotal(self, ca, group_by, function, total_list):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea) | Диапазон|
| group_by | int | Поле для группировки, как целочисленное смещение, отсчитываемое от нуля.|
| function | [`ConsolidationFunction`](/cells/python-net/ru/aspose.cells/consolidationfunction) | Функция промежуточного итога.|
| total_list | list | Массив смещений полей, отсчитываемых от нуля, указывающий поля, к которым добавляются промежуточные итоги.|


##  subtotal {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list-bool-bool-bool}
Создает промежуточные итоги для диапазона.



```python
def subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea) | Диапазон|
| group_by | int | Поле для группировки, как целочисленное смещение, отсчитываемое от нуля.|
| function | [`ConsolidationFunction`](/cells/python-net/ru/aspose.cells/consolidationfunction) | Функция промежуточного итога.|
| total_list | list | Массив смещений полей, отсчитываемых от нуля, указывающий поля, к которым добавляются промежуточные итоги.|
| replace | bool | Указывает, заменить ли текущие промежуточные итоги|
| page_breaks | bool | Указывает, добавлять ли разрыв страницы между группами.|
| summary_below_data | bool | Указывает, добавлять ли сводку ниже данных.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
