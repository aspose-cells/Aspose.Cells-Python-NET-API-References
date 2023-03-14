---
title: calculate_formula метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 40
url: /ru/aspose.cells/workbook/calculate_formula/
is_root: false
---
##  calculate_formula() {#}
Вычисляет результат формул.



```python
def calculate_formula(self):
    ...
```


###  Примечания

Все поддерживаемые формулы см. в списке по адресу https://docs.aspose.com/display/cellsnet/Supported+Formula+Functions.

##  calculate_formula(ignore_error) {#bool}

Вычисляет результат формул.



```python
def calculate_formula(self, ignore_error):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| ignore_error | bool | Указывает, если скрыть ошибку при вычислении формул. Ошибка может быть в неподдерживаемой функции, внешних ссылках и т.п.|


##  calculate_formula(options) {#CalculationOptions}
Расчетные формулы в этой рабочей тетради.



```python
def calculate_formula(self, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| options | [CalculationOptions](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты расчета|


##  calculate_formula(ignore_error, custom_function) {#bool-ICustomFunction}
Вычисляет результат формул.



```python
def calculate_formula(self, ignore_error, custom_function):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| ignore_error | bool | Указывает, если скрыть ошибку при вычислении формул. Ошибка может быть в неподдерживаемой функции, внешних ссылках и т.п.|
| custom_function | [ICustomFunction](/cells/python-net/ru/aspose.cells/icustomfunction) | Функции вычисления пользовательских формул для расширения механизма вычислений.|
###  Примечания

ПРИМЕЧАНИЕ. Этот элемент устарел. Вместо,
пожалуйста, используйте метод CalculateFormula(CalculationOptions).
 Этот метод будет удален через 12 месяцев, начиная с августа 2020 года.
Aspose приносит извинения за возможные неудобства.


###  Смотрите также
* модуль [aspose.cells](../../)
* класс [Workbook](/cells/python-net/ru/aspose.cells/workbook)
