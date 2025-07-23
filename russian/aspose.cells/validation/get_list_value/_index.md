---
title: get_list_value метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 70
url: /ru/aspose.cells/validation/get_list_value/
is_root: false
---
##  get_list_value(self, row, column) {#int-int}
Получить значение для списка проверки для указанной ячейки.


###  Возврат

Значение для создания списка этой проверки для указанной ячейки.
Если список ссылается на диапазон, то возвращаемым значением будет объект [`ReferredArea`](/cells/python-net/ru/aspose.cells/referredarea);
В противном случае возвращаемое значение может быть null, object[] или простым объектом.


```python

def get_list_value(self, row, column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row | int | Индекс строки.|
| column | int | Индекс столбца.|
###  Примечания

Только для проверки типа «Список», примененной к заданной ячейке,
в противном случае будет возвращено значение null.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`ReferredArea`](/cells/python-net/ru/aspose.cells/referredarea)
* класс [`Validation`](/cells/python-net/ru/aspose.cells/validation)
