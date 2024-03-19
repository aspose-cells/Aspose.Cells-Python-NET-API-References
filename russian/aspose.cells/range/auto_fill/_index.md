---
title: auto_fill метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 40
url: /ru/aspose.cells/range/auto_fill/
is_root: false
---
##  auto_fill {#aspose.cells.Range}
Автоматическое заполнение целевого диапазона.



```python
def auto_fill(self, target):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| target | [`Range`](/cells/python-net/ru/aspose.cells/range) | целевой диапазон.|

###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
cells.get("A1").put_value(1)
cells.get("A2").put_value(2)
source = cells.create_range("A1:A2")
target = cells.create_range("A3:A10")
# fill 3,4,5....10 to the range A3:A10
source.auto_fill(target)
# Save the Excel file
workbook.save("book1.xlsm")

```


##  auto_fill {#aspose.cells.Range-aspose.cells.AutoFillType}
Автоматическое заполнение целевого диапазона.



```python
def auto_fill(self, target, auto_fill_type):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| target | [`Range`](/cells/python-net/ru/aspose.cells/range) | Целевой диапазон.|
| auto_fill_type | [`AutoFillType`](/cells/python-net/ru/aspose.cells/autofilltype) | Тип автозаполнения.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Range`](/cells/python-net/ru/aspose.cells/range)
