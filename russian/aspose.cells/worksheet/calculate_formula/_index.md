---
title: calculate_formula метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 90
url: /ru/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula {#str}
Вычисляет формулу.


###  Возврат

Результат расчета формулы.


```python
def calculate_formula(self, formula):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула для расчета.|


##  calculate_formula {#str-aspose.cells.CalculationOptions}
Непосредственное вычисление выражения формулы.


###  Возврат

Расчетный результат по данной формуле.
Возвращаемый объект может иметь возможные типы [`Cell.value`](/cells/python-net/ru/aspose.cells/cell#value) или ReferredArea.


```python
def calculate_formula(self, formula, opts):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула для расчета.|
| opts | [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты расчета формулы|
###  Примечания

Формула будет рассчитана так же, как она была установлена в ячейке A1.
И формула будет принята как обычная формула.
Если вам нужно, чтобы формула была рассчитана как формула массива и чтобы получить массив для вычисленного результата,
вместо этого используйте [`Worksheet.calculate_array_formula`](/cells/python-net/ru/aspose.cells/worksheet/calculate_array_formula).

##  calculate_formula {#aspose.cells.CalculationOptions-bool}
Вычисляет все формулы на этом листе.



```python
def calculate_formula(self, options, recursive):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты расчета|
| recursive | bool | True означает, что ячейки рабочего листа зависят от ячеек других листов,<br/>зависимые ячейки на других листах также будут рассчитаны.<br/> Ложь означает, что все формулы на листе были рассчитаны и значения верны.|


##  calculate_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
Непосредственное вычисление выражения формулы.


###  Возврат

Расчетный результат по данной формуле.
Возвращаемый объект может иметь возможные типы [`Cell.value`](/cells/python-net/ru/aspose.cells/cell#value) или ReferredArea.


```python
def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула для расчета.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | Варианты разбора формулы.|
| c_opts | [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты расчета формулы.|
| base_cell_row | int | Индекс строки базовой ячейки.|
| base_cell_column | int | Индекс столбца базовой ячейки.|
| calculation_data | [`CalculationData`](/cells/python-net/ru/aspose.cells/calculationdata) | Данные расчета. Используется в ситуации<br/>этому пользователю необходимо вычислить некоторые статические формулы при реализации пользовательского механизма вычислений.<br/>В такой ситуации пользователю необходимо указать это с помощью предоставленных расчетных данных.<br/> по номеру [`AbstractCalculationEngine.calculate`](/cells/python-net/ru/aspose.cells/abstractcalculationengine/calculate).|
###  Примечания

Формула будет рассчитана так же, как она была установлена для указанной базовой ячейки.
И формула будет принята как обычная формула. Если вам нужно, чтобы формула была рассчитана как формула массива
и чтобы получить массив для вычисленного результата, используйте
Вместо этого [`Worksheet.calculate_array_formula`](/cells/python-net/ru/aspose.cells/worksheet/calculate_array_formula).


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet)
