---
title: get_param_value метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value(self, index) {#int}
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

Если это простое значение, то возвращает само простое значение;


Если это ссылка, то возвращает объект ReferArea;


Если он ссылается на набор(ы) данных с несколькими значениями, то возвращает массив объектов;



Если это какое-то выражение, которое необходимо вычислить, то оно будет вычислено в режиме значения.
И, как правило, возвращается одно значение, соответствующее текущей ячейке. Например,
если один параметр формулы D2 равен A:A+B:B, то будет рассчитано и возвращено A2+B2.
Однако, если этот параметр был указан как режим массива
(по [`Workbook.update_custom_function_definition`](/cells/python-net/ru/aspose.cells/workbook/update_custom_function_definition)
или [`FormulaParseOptions.custom_function_definition`](/cells/python-net/ru/aspose.cells/formulaparseoptions#custom_function_definition)),
то будет возвращен массив (object[][]), элементами которого являются A1+B1,A2+B2,....


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CalculationData`](/cells/python-net/ru/aspose.cells/calculationdata)
