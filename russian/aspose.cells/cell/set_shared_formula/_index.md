---
title: set_shared_formula метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 360
url: /ru/aspose.cells/cell/set_shared_formula/
is_root: false
---
##  set_shared_formula(self, shared_formula, row_number, column_number) {#str-int-int}
Устанавливает общие формулы для диапазона ячеек.



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



##  set_shared_formula(self, shared_formula, row_number, column_number, options) {#str-int-int-aspose.cells.FormulaParseOptions}

Устанавливает общие формулы для диапазона ячеек.



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


##  set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local) {#str-int-int-bool-bool}
Устанавливает формулу для диапазона ячеек.



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
| is_local | bool | отформатирована ли формула в соответствии с региональными стандартами|
###  Примечания

ПРИМЕЧАНИЕ: Этот класс устарел. Вместо этого
пожалуйста, используйте Cell.SetSharedFormula(string,int,int,FormulaParseOptions).
Эта недвижимость будет снесена через 12 месяцев с декабря 2019 года.
Aspose приносит извинения за любые причиненные вам неудобства.

##  set_shared_formula(self, shared_formula, row_number, column_number, options, values) {#str-int-int-aspose.cells.FormulaParseOptions-list}
Устанавливает общие формулы для диапазона ячеек.



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
| values | list | значения для тех ячеек с заданной общей формулой|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
