---
title: copy метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 100
url: /ru/aspose.cells/range/copy/
is_root: false
---
##  copy(self, range) {#aspose.cells.Range}
Копирует данные (включая формулы), форматирование, объекты чертежей и т. д. из исходного диапазона.



```python

def copy(self, range):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/ru/aspose.cells/range) | Источник [`Range`](/cells/python-net/ru/aspose.cells/range) объект.|

###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
range1 = cells.create_range("A1:A5")
range2 = cells.create_range("A6:A10")
# Copy the range.
range1.copy(range2)
# Save the Excel file
workbook.save("book1.xlsm")

```


##  copy(self, range, options) {#aspose.cells.Range-aspose.cells.PasteOptions}
Копирование диапазона с использованием опций специальной вставки.



```python

def copy(self, range, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/ru/aspose.cells/range) | Исходный диапазон.|
| options | [`PasteOptions`](/cells/python-net/ru/aspose.cells/pasteoptions) | Параметры специальной вставки.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Range`](/cells/python-net/ru/aspose.cells/range)
