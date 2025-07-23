---
title: intersect метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 170
url: /ru/aspose.cells/range/intersect/
is_root: false
---
##  intersect(self, range) {#aspose.cells.Range}
Возвращает объект [`Range`](/cells/python-net/ru/aspose.cells/range), представляющий собой прямоугольное пересечение двух диапазонов.


###  Возврат

Возвращает объект [`Range`](/cells/python-net/ru/aspose.cells/range)


```python

def intersect(self, range):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/ru/aspose.cells/range) | Пересекающийся диапазон.|
###  Примечания

Если два диапазона не пересекаются, возвращает null.
###  Пример


```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
range1 = cells.create_range("A1:A5")
range2 = cells.create_range("A3:A10")
# Get intersected range of the two ranges.
intersectRange = range1.intersect(range2)
# Save the Excel file
workbook.save("book1.xlsm")

```



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Range`](/cells/python-net/ru/aspose.cells/range)
