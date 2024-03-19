---
title: set_dynamic_array_formula метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 330
url: /ru/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-bool}
Устанавливает формулу динамического массива и, если это возможно, заставляет формулу распространяться на соседние ячейки.


###  Возврат

диапазон, в который должна попасть формула.


```python
def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str |выражение формулы|
| options | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | варианты анализа формулы.<br/> Опция «Разобрать» будет игнорироваться, и формула всегда будет анализироваться немедленно.|
| calculate_value | bool | следует ли вычислять эту формулу динамического массива для этих ячеек в расширенном диапазоне.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
Устанавливает формулу динамического массива и, если это возможно, заставляет формулу распространяться на соседние ячейки.


###  Возврат

диапазон, в который должна попасть формула.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str |выражение формулы|
| options | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | варианты анализа формулы.<br/> Опция «Разобрать» будет игнорироваться, и формула всегда будет анализироваться немедленно.|
| values | list | значения (расчетные результаты) для этих ячеек с заданной формулой динамического массива|
| calculate_range | bool | Можно ли рассчитать расширенный диапазон для этой формулы динамического массива.<br/>Если параметр «values» не равен нулю и этот флаг имеет значение false,<br/> тогда высота выделенного диапазона будет равна значениям. Длина и ширина будут значениями [0]. Длина.|
| calculate_value | bool | вычислять ли эту формулу динамического массива для тех ячеек в расширенном диапазоне, когда «значения» равны нулю<br/> или соответствующий элемент в «значениях» для одной ячейки имеет значение NULL.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
Устанавливает формулу динамического массива и, если это возможно, заставляет формулу распространяться на соседние ячейки.


###  Возврат

диапазон, в который должна попасть формула.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str |выражение формулы|
| options | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | варианты анализа формулы.<br/> Опция «Разобрать» будет игнорироваться, и формула всегда будет анализироваться немедленно.|
| values | list | значения (расчетные результаты) для этих ячеек с заданной формулой динамического массива|
| calculate_range | bool | Можно ли рассчитать расширенный диапазон для этой формулы динамического массива.<br/>Если параметр «values» не равен нулю и этот флаг имеет значение false,<br/> тогда высота выделенного диапазона будет равна значениям. Длина и ширина будут значениями [0]. Длина.|
| calculate_value | bool | вычислять ли эту формулу динамического массива для тех ячеек в расширенном диапазоне, когда «значения» равны нулю<br/> или соответствующий элемент в «значениях» для одной ячейки имеет значение NULL.|
| copts | [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты расчета формулы.<br/> Обычно для обеспечения производительности свойство [`CalculationOptions.recursive`](/cells/python-net/ru/aspose.cells/calculationoptions#recursive) должно быть ложным.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
