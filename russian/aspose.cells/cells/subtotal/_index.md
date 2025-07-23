---
title: subtotal метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 930
url: /ru/aspose.cells/cells/subtotal/
is_root: false
---
##  subtotal(self, ca, group_by, function, total_list) {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list}
Создает промежуточные итоги для диапазона.



```python

def subtotal(self, ca, group_by, function, total_list):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea) | Диапазон|
| group_by | int | Поле для группировки, как целочисленное смещение, начинающееся с нуля|
| function | [`ConsolidationFunction`](/cells/python-net/ru/aspose.cells/consolidationfunction) | Функция промежуточных итогов.|
| total_list | list |Массив смещений полей, начинающихся с нуля, указывающий поля, к которым добавляются промежуточные итоги.|


##  subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data) {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list-bool-bool-bool}
Создает промежуточные итоги для диапазона.



```python

def subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea) | Диапазон|
| group_by | int | Поле для группировки, как целочисленное смещение, начинающееся с нуля|
| function | [`ConsolidationFunction`](/cells/python-net/ru/aspose.cells/consolidationfunction) | Функция промежуточных итогов.|
| total_list | list |Массив смещений полей, начинающихся с нуля, указывающий поля, к которым добавляются промежуточные итоги.|
| replace | bool | Указывает, следует ли заменить текущие промежуточные итоги|
| page_breaks | bool | Указывает, нужно ли добавлять разрыв страницы между группами|
| summary_below_data | bool | Указывает, следует ли добавлять сводку ниже данных.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
