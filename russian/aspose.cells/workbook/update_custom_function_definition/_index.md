---
title: update_custom_function_definition метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 410
url: /ru/aspose.cells/workbook/update_custom_function_definition/
is_root: false
---
##  update_custom_function_definition {#aspose.cells.CustomFunctionDefinition}
Обновляет определение пользовательских функций.



```python
def update_custom_function_definition(self, definition):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| definition | [`CustomFunctionDefinition`](/cells/python-net/ru/aspose.cells/customfunctiondefinition) |Специальное определение пользовательских функций для особых требований пользователя.|
###  Примечания

Этот метод можно использовать для некоторых особых сценариев. Например, если пользователю нужны некоторые параметры
некоторые пользовательские функции вычисляются в режиме массива, тогда пользователь может предоставить свое собственное определение с реализованными
[`CustomFunctionDefinition.get_array_mode_parameters`](/cells/python-net/ru/aspose.cells/customfunctiondefinition/get_array_mode_parameters) для этих функций.
После обновления данных формул указанные параметры будут автоматически рассчитаны в режиме массива.
при вычислении соответствующих пользовательских функций.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
