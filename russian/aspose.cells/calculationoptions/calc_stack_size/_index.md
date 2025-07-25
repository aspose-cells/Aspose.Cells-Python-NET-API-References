---
title: calc_stack_size недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells/calculationoptions/calc_stack_size/
is_root: false
---
##  calc_stack_size недвижимость

Размер стека для рекурсивного вычисления ячеек. Значение по умолчанию — 200.

###  Примечания

Когда в дереве зависимостей требуется рекурсивный расчет большого количества ячеек,
В процессе вычислений может возникнуть исключение StackOverflowException.
Если это так, пользователю следует указать меньшее значение для этого свойства.
В такой ситуации пользователь должен определить правильное значение этого свойства в соответствии с фактическими формулами и данными.
Однако слишком маленькое значение может привести к снижению производительности расчета формулы, а значение меньше 2
сделает невозможным вычисление формулы, зависящей от другой. Поэтому, если указанное значение меньше 2,
он будет сброшен до 2.
###  Определение:
```python
@property
def calc_stack_size(self):
    ...
@calc_stack_size.setter
def calc_stack_size(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions)
