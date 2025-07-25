---
title: add_condition метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 40
url: /ru/aspose.cells/formatconditioncollection/add_condition/
is_root: false
---
##  add_condition(self, type) {#aspose.cells.FormatConditionType}
Добавьте условие форматирования.


###  Возврат

Форматирование индекса объекта условия;


```python

def add_condition(self, type):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/ru/aspose.cells/formatconditiontype) | Тип условия форматирования.|


##  add_condition(self, type, operator_type, formula1, formula2) {#aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
Добавляет условие форматирования.


###  Возврат

Форматирование индекса объекта условия;


```python

def add_condition(self, type, operator_type, formula1, formula2):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/ru/aspose.cells/formatconditiontype) | Тип условия форматирования.|
| operator_type | [`OperatorType`](/cells/python-net/ru/aspose.cells/operatortype) | Тип оператора|
| formula1 | str | Значение или выражение, связанное с условным форматированием.<br/>Если входное значение начинается с «=», то оно будет принято как формула.<br/>В противном случае оно будет воспринято как обычное значение (текст, число, логическое значение).<br/> Для текстового значения, начинающегося с «=», пользователь может ввести его как формулу в формате: «=\"=...\"».|
| formula2 | str | Значение или выражение, связанное с условным форматированием.<br/> Формат ввода такой же, как у formula1|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`FormatConditionCollection`](/cells/python-net/ru/aspose.cells/formatconditioncollection)
