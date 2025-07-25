---
title: calculate_array_formula метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 80
url: /ru/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
Вычисляет формулу как формулу массива.



```python

def calculate_array_formula(self, formula, opts):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула для расчета.|
| opts | [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты формулы расчета|


##  calculate_array_formula(self, formula, opts, max_row_count, max_column_count) {#str-aspose.cells.CalculationOptions-int-int}
Вычисляет формулу как формулу массива.


###  Возврат

Результат расчетной формулы.


```python

def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула для расчета.|
| opts | [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты формулы расчета|
| max_row_count | int | максимальное количество строк результирующих данных.<br/> Если оно неположительное или больше фактического количества строк, то будет использовано фактическое количество строк.|
| max_column_count | int | максимальное количество столбцов результирующих данных.<br/> Если оно неположительное или больше фактического количества строк, то будет использовано фактическое количество столбцов.|
###  Примечания

Формула будет принята как динамическая формула массива для вычисления измерения и результата.
Указанный пользователем максимальный размер используется в случаях, когда вычисленный результат представляет собой большой набор данных.
(например, вычисленный результат может соответствовать данным всей строки или столбца)
но пользователю не нужен такой большой массив по соображениям бизнеса или производительности.

##  calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
Вычисляет формулу как формулу массива.


###  Возврат

Результат расчетной формулы.


```python

def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула для расчета.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) |Варианты разбора формулы|
| c_opts | [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты формулы расчета|
| base_cell_row | int | Индекс строки базовой ячейки.|
| base_cell_column | int | Индекс столбца базовой ячейки.|
| max_row_count | int | Максимальное количество строк результирующих данных.<br/> Если оно неположительное или больше фактического количества строк, то будет использовано фактическое количество строк.|
| max_column_count | int | Максимальное количество столбцов результирующих данных.<br/> Если оно неположительное или больше фактического количества строк, то будет использовано фактическое количество столбцов.|
| calculation_data | [`CalculationData`](/cells/python-net/ru/aspose.cells/calculationdata) | Данные расчета. Они используются для данной ситуации.<br/>что пользователю необходимо рассчитать некоторые статические формулы при реализации пользовательского механизма вычислений.<br/>В такой ситуации пользователю необходимо указать предоставленные расчетные данные.<br/> для Aspose.Cells.AbstractCalculationEngine.Calculate.|
###  Примечания

Формула будет принята как динамическая формула массива для вычисления измерения и результата.
Указанный пользователем максимальный размер используется в случаях, когда вычисленный результат представляет собой большой набор данных.
(например, вычисленный результат может соответствовать данным всей строки или столбца)
но пользователю не нужен такой большой массив по соображениям бизнеса или производительности.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet)
