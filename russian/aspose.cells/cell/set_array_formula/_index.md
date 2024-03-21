---
title: set_array_formula метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 310
url: /ru/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula {#str-int-int}
Устанавливает формулу массива (устаревшая формула массива, введенная с помощью CTRL+SHIFT+ENTER в MS Excel) в диапазон ячеек.



```python
def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str | Формула массива.|
| row_number | int | Количество строк для заполнения результата формулы массива.|
| column_number | int | Количество столбцов для заполнения результата формулы массива.|


##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions}
Устанавливает формулу массива в диапазон ячеек.



```python
def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str | Формула массива.|
| row_number | int | Количество строк для заполнения результата формулы массива.|
| column_number | int | Количество столбцов для заполнения результата формулы массива.|
| options | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | Варианты разбора формулы.|


##  set_array_formula {#str-int-int-bool-bool}
Устанавливает формулу массива в диапазон ячеек.



```python
def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str | Формула массива.|
| row_number | int | Количество строк для заполнения результата формулы массива.|
| column_number | int | Количество столбцов для заполнения результата формулы массива.|
| is_r1c1 | bool | является ли формула формулой R1C1|
| is_local | bool | имеет ли формула языковой формат|
###  Примечания

ПРИМЕЧАНИЕ. Этот класс устарел. Вместо,
используйте Cell.SetArrayFormula(string,int,int,FormulaParseOptions).
Этот объект недвижимости будет удален через 12 месяцев, начиная с декабря 2019 года.
Aspose приносит извинения за возможные неудобства.

##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions-list}
Устанавливает формулу массива в диапазон ячеек.



```python
def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str | Формула массива.|
| row_number | int | Количество строк для заполнения результата формулы массива.|
| column_number | int | Количество столбцов для заполнения результата формулы массива.|
| options | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | Варианты разбора формулы.|
| values | list | значения для этих ячеек с заданной формулой массива|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
