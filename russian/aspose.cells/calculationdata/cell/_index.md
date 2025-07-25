---
title: cell недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 70
url: /ru/aspose.cells/calculationdata/cell/
is_root: false
---
##  cell недвижимость

Получает объект Cell, в котором находится функция.

###  Примечания

При вычислении формулы без установки ее в значение cell,
например, по номеру [`Worksheet.calculate_formula`](/cells/python-net/ru/aspose.cells/worksheet/calculate_formula),
формула будет рассчитана так же, как если бы она была установлена в cell A1,
поэтому и [`CalculationData.cell_row`](/cells/python-net/ru/aspose.cells/calculationdata#cell_row), и [`CalculationData.cell_column`](/cells/python-net/ru/aspose.cells/calculationdata#cell_column) равны 0.
Однако, возможно, ячейка A1 на листе cell не была создана.
Поэтому для такой ситуации это свойство будет равно нулю.
###  Определение:
```python
@property
def cell(self):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CalculationData`](/cells/python-net/ru/aspose.cells/calculationdata)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
