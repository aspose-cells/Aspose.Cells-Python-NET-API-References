---
title: enable_calculation_chain недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 70
url: /ru/aspose.cells/formulasettings/enable_calculation_chain/
is_root: false
---
##  enable_calculation_chain недвижимость

Включить ли цепочку вычислений для формул. Значение по умолчанию — false.

###  Примечания

Когда в рабочей книге много формул и пользователю приходится многократно их вычислять
при изменении лишь небольшой их части может оказаться полезным для производительности включить цепочку вычислений.
С другой стороны, если цепочка включена, поддержание модели цепочки требует дополнительной памяти,
и также требуется немного больше процессорного времени для некоторых других операций, таких как изменение значения ячейки или формул.
После изменения этого свойства с false на true цепочка вычислений будет проанализирована и построена.
на момент первого расчета для рабочей книги, поэтому необходимое время для первого расчета
может быть больше обычного расчета без цепочки.
###  Определение:
```python
@property
def enable_calculation_chain(self):
    ...
@enable_calculation_chain.setter
def enable_calculation_chain(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`FormulaSettings`](/cells/python-net/ru/aspose.cells/formulasettings)
