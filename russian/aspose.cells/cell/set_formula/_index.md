---
title: set_formula метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 340
url: /ru/aspose.cells/cell/set_formula/
is_root: false
---
##  set_formula {#str-any}
Установите формулу и значение (расчетный результат) формулы.



```python
def set_formula(self, formula, value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула.|
| value | any |Значение (расчетный результат) формулы.|


##  set_formula {#str-aspose.cells.FormulaParseOptions-any}
Установите формулу и значение (расчетный результат) формулы.



```python
def set_formula(self, formula, options, value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула.|
| options | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | Варианты разбора формулы.|
| value | any |Значение (расчетный результат) формулы.|


##  set_formula {#str-bool-bool-any}
Установите формулу и значение формулы.



```python
def set_formula(self, formula, is_r1c1, is_local, value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула.|
| is_r1c1 | bool | Является ли формула формулой R1C1.|
| is_local | bool | Отформатирована ли формула в локали.|
| value | any | Значение формулы.|
###  Примечания

ПРИМЕЧАНИЕ. Этот класс устарел. Вместо,
используйте Cell.SetFormula(строка,FormulaParseOptions,объект).
Этот объект недвижимости будет удален через 12 месяцев, начиная с декабря 2019 года.
Aspose приносит извинения за возможные неудобства.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
