---
title: set_array_formula метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 320
url: /ru/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula(self, array_formula, row_number, column_number) {#str-int-int}
Устанавливает формулу массива (устаревшую формулу массива, введенную с помощью CTRL+SHIFT+ENTER в MS Excel) для диапазона ячеек.



```python

def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str | Формула массива.|
| row_number | int | Количество строк для заполнения результата формулы массива.|
| column_number | int | Количество столбцов для заполнения результатом формулы массива.|


##  set_array_formula(self, array_formula, row_number, column_number, options) {#str-int-int-aspose.cells.FormulaParseOptions}
Устанавливает формулу массива для диапазона ячеек.



```python

def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str | Формула массива.|
| row_number | int | Количество строк для заполнения результата формулы массива.|
| column_number | int | Количество столбцов для заполнения результатом формулы массива.|
| options | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | Варианты разбора формулы.|


##  set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local) {#str-int-int-bool-bool}
Устанавливает формулу массива для диапазона ячеек.



```python

def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str | Формула массива.|
| row_number | int | Количество строк для заполнения результата формулы массива.|
| column_number | int | Количество столбцов для заполнения результатом формулы массива.|
| is_r1c1 | bool | является ли формула формулой R1C1|
| is_local | bool | отформатирована ли формула в соответствии с региональными стандартами|
###  Примечания

ПРИМЕЧАНИЕ: Этот класс устарел. Вместо этого
пожалуйста, используйте Cell.SetArrayFormula(string,int,int,FormulaParseOptions).
Эта недвижимость будет снесена через 12 месяцев с декабря 2019 года.
Aspose приносит извинения за любые причиненные вам неудобства.

##  set_array_formula(self, array_formula, row_number, column_number, options, values) {#str-int-int-aspose.cells.FormulaParseOptions-list}
Устанавливает формулу массива для диапазона ячеек.



```python

def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| array_formula | str | Формула массива.|
| row_number | int | Количество строк для заполнения результата формулы массива.|
| column_number | int | Количество столбцов для заполнения результатом формулы массива.|
| options | [`FormulaParseOptions`](/cells/python-net/ru/aspose.cells/formulaparseoptions) | Варианты разбора формулы.|
| values | list | значения для тех ячеек с заданной формулой массива|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Cell`](/cells/python-net/ru/aspose.cells/cell)
