---
title: set_dynamic_array_formula метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 340
url: /ru/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula(self, array_formula, options, calculate_value) {#str-aspose.cells.FormulaParseOptions-bool}
Задает динамическую формулу массива и заставляет формулу распространяться на соседние ячейки, если это возможно.


###  Возврат

диапазон, в который должна распространяться формула.


```python

def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str | формула выражения|
| options | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | параметры для разбора формулы.<br/> Параметр «Анализ» будет проигнорирован, и формула всегда будет проанализирована немедленно.|
| calculate_value | bool | вычислять ли эту динамическую формулу массива для ячеек в пролитом диапазоне.|
###  Примечания

возвращаемый диапазон может не совпадать с фактическим, в который переходит эта динамическая формула массива.
Если в диапазоне есть непустые ячейки, формула будет установлена только для текущей ячейки и помечена как «#SPILL!».
Но для такой ситуации мы все равно возвращаем весь диапазон, в который должна выходить эта формула.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value) {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
Задает динамическую формулу массива и заставляет формулу распространяться на соседние ячейки, если это возможно.


###  Возврат

диапазон, в который должна распространяться формула.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str | формула выражения|
| options | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | параметры для разбора формулы.<br/> Параметр «Анализ» будет проигнорирован, и формула всегда будет проанализирована немедленно.|
| values | list |значения (вычисленные результаты) для ячеек с заданной формулой динамического массива|
| calculate_range | bool | Рассчитать ли пролитый диапазон для этой формулы динамического массива.<br/>Если параметр «values» не равен null и этот флаг имеет значение false,<br/> тогда высота разлитого диапазона будет равна значениям.Длина, а ширина будет равна значениям[0].Длина.|
| calculate_value | bool | вычислять ли эту динамическую формулу массива для тех ячеек в пропущенном диапазоне, когда «значения» равны нулю<br/> или соответствующий элемент в «значениях» для одной ячейки равен нулю.|
###  Примечания

возвращаемый диапазон может не совпадать с фактическим, в который переходит эта динамическая формула массива.
Если в диапазоне есть непустые ячейки, формула будет установлена только для текущей ячейки и помечена как «#SPILL!».
Но для такой ситуации мы все равно возвращаем весь диапазон, в который должна выходить эта формула.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts) {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
Задает динамическую формулу массива и заставляет формулу распространяться на соседние ячейки, если это возможно.


###  Возврат

диапазон, в который должна распространяться формула.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str | формула выражения|
| options | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | параметры для разбора формулы.<br/> Параметр «Анализ» будет проигнорирован, и формула всегда будет проанализирована немедленно.|
| values | list |значения (вычисленные результаты) для ячеек с заданной формулой динамического массива|
| calculate_range | bool | Рассчитать ли пролитый диапазон для этой формулы динамического массива.<br/>Если параметр «values» не равен null и этот флаг имеет значение false,<br/> тогда высота разлитого диапазона будет равна значениям.Длина, а ширина будет равна значениям[0].Длина.|
| calculate_value | bool | вычислять ли эту динамическую формулу массива для тех ячеек в пропущенном диапазоне, когда «значения» равны нулю<br/> или соответствующий элемент в «значениях» для одной ячейки равен нулю.|
| copts | [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты формулы расчета.<br/> Обычно из соображений производительности свойство [`CalculationOptions.recursive`](/cells/python-net/ru/aspose.cells/calculationoptions#recursive) должно быть false.|
###  Примечания

возвращаемый диапазон может не совпадать с фактическим, в который переходит эта динамическая формула массива.
Если в диапазоне есть непустые ячейки, формула будет установлена только для текущей ячейки и помечена как «#SPILL!».
Но для такой ситуации мы все равно возвращаем весь диапазон, в который должна выходить эта формула.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
