---
title: calculate_array_formula метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 80
url: /ru/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula {#str-aspose.cells.CalculationOptions}
Вычисляет формулу как формулу массива.



```python
def calculate_array_formula(self, formula, opts):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула для расчета.|
| opts | [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты расчета формулы|


##  calculate_array_formula {#str-aspose.cells.CalculationOptions-int-int}
Вычисляет формулу как формулу массива.


###  Возврат

Результат расчета формулы.


```python
def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула для расчета.|
| opts | [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты расчета формулы|
| max_row_count | int | максимальное количество строк результирующих данных.<br/> Если оно не положительное или превышает фактическое количество строк, будет использоваться фактическое количество строк.|
| max_column_count | int | максимальное количество столбцов результирующих данных.<br/> Если оно не положительное или превышает фактическое количество строк, будет использоваться фактическое количество столбцов.|
###  Примечания

Формула будет использована как формула динамического массива для расчета размера и результата.
Максимальный размер, указанный пользователем, используется в случаях, когда вычисленный результат представляет собой большой набор данных.
(например, вычисленный результат может соответствовать целым данным строки или столбца)
но пользователю не нужен такой большой массив в соответствии с бизнес-требованиями или из соображений производительности.

##  calculate_array_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
Вычисляет формулу как формулу массива.


###  Возврат

Результат расчета формулы.


```python
def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| formula | str | Формула для расчета.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | Варианты разбора формулы|
| c_opts | [`CalculationOptions`](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты расчета формулы|
| base_cell_row | int | Индекс строки базовой ячейки.|
| base_cell_column | int | Индекс столбца базовой ячейки.|
| max_row_count | int | Максимальное количество строк результирующих данных.<br/> Если оно не положительное или превышает фактическое количество строк, будет использоваться фактическое количество строк.|
| max_column_count | int | Максимальное количество столбцов результирующих данных.<br/> Если оно не положительное или превышает фактическое количество строк, будет использоваться фактическое количество столбцов.|
| calculation_data | [`CalculationData`](/cells/python-net/ru/aspose.cells/calculationdata) | Данные расчета. Используется в ситуации<br/>этому пользователю необходимо вычислить некоторые статические формулы при реализации пользовательского механизма вычислений.<br/>В такой ситуации пользователю необходимо указать это с помощью предоставленных расчетных данных.<br/> по номеру [`AbstractCalculationEngine.calculate`](/cells/python-net/ru/aspose.cells/abstractcalculationengine/calculate).|
###  Примечания

Формула будет использована как формула динамического массива для расчета размера и результата.
Максимальный размер, указанный пользователем, используется в случаях, когда вычисленный результат представляет собой большой набор данных.
(например, вычисленный результат может соответствовать целым данным строки или столбца)
но пользователю не нужен такой большой массив в соответствии с бизнес-требованиями или из соображений производительности.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet)
