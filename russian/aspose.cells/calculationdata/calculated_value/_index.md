---
title: calculated_value недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 60
url: /ru/aspose.cells/calculationdata/calculated_value/
is_root: false
---
##  calculated_value недвижимость

Получает или задает расчетное значение для этой функции.

###  Примечания

Пользователь должен установить это свойство в своем пользовательском механизме вычислений для тех функций, которые поддерживает механизм.
и установленное значение будет возвращено при получении этого свойства позже.
Установленное значение может иметь следующие типы: [`Cell.value`](/cells/python-net/ru/aspose.cells/cell#value),
или массив таких значений, или Диапазон, Имя, ReferredArea.
Получение этого свойства перед установкой для него значения приведет к вычислению функции.
с помощью механизма расчета по умолчанию Aspose.Cells, а затем рассчитанное значение будет
быть возвращено (обычно это должно быть #NAME? для пользовательских функций).
###  Определение:
```python
@property
def calculated_value(self):
    ...
@calculated_value.setter
def calculated_value(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CalculationData`](/cells/python-net/ru/aspose.cells/calculationdata)
