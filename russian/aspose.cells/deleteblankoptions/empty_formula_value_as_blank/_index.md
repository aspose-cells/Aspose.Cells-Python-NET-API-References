---
title: empty_formula_value_as_blank недвижимость
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 40
url: /ru/aspose.cells/deleteblankoptions/empty_formula_value_as_blank/
is_root: false
---
##  empty_formula_value_as_blank недвижимость

Будет ли одна ячейка считаться пустой, если она является формулой, а вычисленный результат — нуль или пустая строка.
Значение по умолчанию — false.

###  Примечания

Обычно пользователь должен убедиться, что формулы были рассчитаны, прежде чем удалять операцию, если это свойство имеет значение true.
В противном случае все вновь созданные формулы с помощью обычных API, такие как [`Cell.formula`](/cells/python-net/ru/aspose.cells/cell#formula), будут считаться пустыми и могут быть удалены.
потому что до расчета все их расчетные результаты равны нулю.
###  Определение:
```python
@property
def empty_formula_value_as_blank(self):
    ...
@empty_formula_value_as_blank.setter
def empty_formula_value_as_blank(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`DeleteBlankOptions`](/cells/python-net/ru/aspose.cells/deleteblankoptions)
