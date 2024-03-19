---
title: set_shared_formula метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 350
url: /ru/aspose.cells/cell/set_shared_formula/
is_root: false
---
##  set_shared_formula {#str-int-int}
Устанавливает общие формулы в диапазон ячеек.



```python
def set_shared_formula(self, shared_formula, row_number, column_number):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| shared_formula | str | Общая формула.|
| row_number | int | Количество строк для заполнения формулы.|
| column_number | int | Количество столбцов для заполнения формулы.|
###  Примечания



##  set_shared_formula {#str-int-int-aspose.cells.FormulaParseOptions}

Устанавливает общие формулы в диапазон ячеек.



```python
def set_shared_formula(self, shared_formula, row_number, column_number, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| shared_formula | str | Общая формула.|
| row_number | int | Количество строк для заполнения формулы.|
| column_number | int | Количество столбцов для заполнения формулы.|
| options | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | Варианты разбора формулы.|


##  set_shared_formula {#str-int-int-bool-bool}
Устанавливает формулу в диапазон ячеек.



```python
def set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| shared_formula | str | Общая формула.|
| row_number | int | Количество строк для заполнения формулы.|
| column_number | int | Количество столбцов для заполнения формулы.|
| is_r1c1 | bool | является ли формула формулой R1C1|
| is_local | bool | имеет ли формула языковой формат|
###  Примечания

ПРИМЕЧАНИЕ. Этот класс устарел. Вместо,
используйте Cell.SetSharedFormula(string,int,int,FormulaParseOptions).
Этот объект недвижимости будет удален через 12 месяцев, начиная с декабря 2019 года.
Aspose приносит извинения за возможные неудобства.

##  set_shared_formula {#str-int-int-aspose.cells.FormulaParseOptions-list}
Устанавливает общие формулы в диапазон ячеек.



```python
def set_shared_formula(self, shared_formula, row_number, column_number, options, values):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| shared_formula | str | Общая формула.|
| row_number | int | Количество строк для заполнения формулы.|
| column_number | int | Количество столбцов для заполнения формулы.|
| options | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | Варианты разбора формулы.|
| values | list | значения для этих ячеек с заданной общей формулой|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
