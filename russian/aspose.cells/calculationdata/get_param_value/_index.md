---
title: get_param_value метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 30
url: /ru/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value {#int}
Получает представленный объект значения параметра по заданному индексу.


###  Возврат

Расчетное значение параметра.


```python
def get_param_value(self, index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| index | int | Индекс параметра (на основе 0)|
###  Примечания

Для одного параметра:

Если это простое значение, то возвращается само простое значение;


Если это ссылка, то возвращает объект ReferredArea;


Если он ссылается на наборы данных с несколькими значениями, возвращается массив объектов;



Если это какое-то выражение, которое необходимо вычислить, то оно будет рассчитано в режиме значения.
и обычно возвращается одно значение в соответствии с текущей базой ячеек. Например,
если один параметр формулы D2 — A:A+B:B, то A2+B2 будет рассчитан и возвращен.
Однако, если этот параметр указан как режим массива
(по телефону [`Workbook.update_custom_function_definition`](/cells/python-net/ru/aspose.cells/workbook/update_custom_function_definition)
или [`FormulaParseOptions.custom_function_definition`](/cells/python-net/ru/aspose.cells/formulaparseoptions#custom_function_definition)),
тогда будет возвращен массив (объект[][]), элементы которого — A1+B1,A2+B2,....


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CalculationData`](/cells/python-net/ru/aspose.cells/calculationdata)
