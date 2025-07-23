---
title: calculated_value недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
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
и заданное значение будет возвращено при последующем получении этого свойства.
Установленное значение может иметь один из возможных типов: [`Cell.value`](/cells/python-net/ru/aspose.cells/cell#value),
или массив таких значений, или Диапазон, Имя, Референсная область.
Получение этого свойства до присвоения ему значения приведет к вычислению функции.
по умолчанию вычислительным механизмом Aspose.Cells, и тогда вычисленное значение будет
быть возвращено (обычно это #NAME? для пользовательских функций).
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
