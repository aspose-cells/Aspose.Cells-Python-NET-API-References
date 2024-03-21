---
title: cell недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 70
url: /ru/aspose.cells/calculationdata/cell/
is_root: false
---
##  cell недвижимость

Получает объект Cell, в котором находится функция.

###  Примечания

При вычислении формулы без установки для нее значения cell,
например, по номеру [`Worksheet.calculate_formula`](/cells/python-net/ru/aspose.cells/worksheet/calculate_formula),
формула будет рассчитана так же, как и для cell A1,
поэтому и [`CalculationData.cell_row`](/cells/python-net/ru/aspose.cells/calculationdata#cell_row), и [`CalculationData.cell_column`](/cells/python-net/ru/aspose.cells/calculationdata#cell_column) равны 0.
Однако экземпляр cell A1 на листе может не быть создан.
Таким образом, для такой ситуации это свойство будет нулевым.
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
