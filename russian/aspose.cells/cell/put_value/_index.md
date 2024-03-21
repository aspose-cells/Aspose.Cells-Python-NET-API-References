---
title: put_value метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 280
url: /ru/aspose.cells/cell/put_value/
is_root: false
---
##  put_value {#bool}
Помещает логическое значение в ячейку.



```python
def put_value(self, bool_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| bool_value | bool |  |


##  put_value {#int}
Помещает в ячейку целочисленное значение.



```python
def put_value(self, int_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| int_value | int | Входное значение|


##  put_value {#float}
Помещает в ячейку двойное значение.



```python
def put_value(self, double_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| double_value | float | Входное значение|


##  put_value {#str}
Помещает строковое значение в ячейку.



```python
def put_value(self, string_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| string_value | str | Входное значение|


##  put_value {#DateTime}
Помещает в ячейку значение DateTime.



```python
def put_value(self, date_time):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| date_time | DateTime | Входное значение|
###  Примечания

Установка значения DateTime для дозы ячейки не означает, что ячейка будет автоматически отформатирована как дата и время.
Значение DateTime сохранялось как числовое значение в модели данных MS Excel и Aspose.Cells.
Будет ли числовое значение восприниматься как само числовое значение или дата и время.
зависит от числового формата, примененного к этой ячейке. Если эта ячейка не была отформатирована как дата и время,
оно будет отображаться как числовое значение, даже если вы вводите DateTime.
###  Пример

В этом примере показано, как установить значение DateTime для ячейки и отобразить его как дату и время.

```python
from aspose.cells import Workbook
from datetime import datetime

excel = Workbook()
cells = excel.worksheets[0].cells
# Put date time into a cell
cell = cells.get(0, 0)
cell.put_value(datetime(2023, 5, 15))
style = cell.get_style(False)
style.number = 14
cell.set_style(style)

```


##  put_value {#any}
Помещает значение объекта в ячейку.



```python
def put_value(self, object_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| object_value | any | входное значение|


##  put_value {#str-bool}
Помещает строковое значение в ячейку и при необходимости преобразует значение в другой тип данных.



```python
def put_value(self, string_value, is_converted):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| string_value | str | Входное значение|
| is_converted | bool | True: преобразуется в другой тип данных, если это необходимо.|


##  put_value {#str-bool-bool}
Помещает значение в ячейку. При необходимости значение будет преобразовано в другой тип данных, а числовой формат ячейки будет сброшен.



```python
def put_value(self, string_value, is_converted, set_style):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| string_value | str | Входное значение|
| is_converted | bool | True: преобразуется в другой тип данных, если это необходимо.|
| set_style | bool | True: установите числовой формат в соответствии со стилем ячейки при преобразовании в другой тип данных.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
