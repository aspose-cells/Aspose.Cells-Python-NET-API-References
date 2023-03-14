---
title: calculate метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 20
url: /ru/aspose.cells/cell/calculate/
is_root: false
---
##  calculate(options) {#CalculationOptions}
Вычисляет формулу ячейки.



```python
def calculate(self, options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| options | [CalculationOptions](/cells/python-net/ru/aspose.cells/calculationoptions) | Варианты расчета|


##  calculate(ignore_error, custom_function) {#bool-ICustomFunction}
Вычисляет формулу ячейки.



```python
def calculate(self, ignore_error, custom_function):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| ignore_error | bool | Указывает, если скрыть ошибку при вычислении формул.<br/> Ошибка может быть в неподдерживаемой функции, внешних ссылках и т.п.|
| custom_function | [ICustomFunction](/cells/python-net/ru/aspose.cells/icustomfunction) | Функции вычисления пользовательских формул для расширения механизма вычислений.|
###  Примечания

ПРИМЕЧАНИЕ. Этот элемент устарел. Вместо,
пожалуйста, используйте метод Calculate(CalculationOptions).
 Этот метод будет удален через 12 месяцев, начиная с августа 2020 года.
Aspose приносит извинения за возможные неудобства.


###  Смотрите также
* модуль [aspose.cells](../../)
* класс [Cell](/cells/python-net/ru/aspose.cells/cell)
