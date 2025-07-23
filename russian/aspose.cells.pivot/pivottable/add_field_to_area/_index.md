---
title: add_field_to_area метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells.pivot/pivottable/add_field_to_area/
is_root: false
---
##  add_field_to_area(self, field_type, field_name) {#aspose.cells.pivot.PivotFieldType-str}
Добавляет поле в определенную область.


###  Возврат

Позиция поля среди указанных полей. Если поля с таким именем нет, вернуть -1.


```python

def add_field_to_area(self, field_type, field_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| field_type | [`PivotFieldType`](/cells/python-net/ru/aspose.cells.pivot/pivotfieldtype) | Тип области полей.|
| field_name | str |Имя в базовых полях.|


##  add_field_to_area(self, field_type, base_field_index) {#aspose.cells.pivot.PivotFieldType-int}
Добавляет поле в определенную область.


###  Возврат

Позиция поля в конкретных полях.


```python

def add_field_to_area(self, field_type, base_field_index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| field_type | [`PivotFieldType`](/cells/python-net/ru/aspose.cells.pivot/pivotfieldtype) | Тип области полей.|
| base_field_index | int | Индекс поля в базовых полях.|


##  add_field_to_area(self, field_type, pivot_field) {#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField}
Добавляет поле в определенную область.


###  Возврат

позиция поля в конкретных полях.


```python

def add_field_to_area(self, field_type, pivot_field):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| field_type | [`PivotFieldType`](/cells/python-net/ru/aspose.cells.pivot/pivotfieldtype) | тип области полей.|
| pivot_field | [`PivotField`](/cells/python-net/ru/aspose.cells.pivot/pivotfield) | поле в базовых полях.|



###  Смотрите также
* модуль [`aspose.cells.pivot`](../../)
* класс [`PivotTable`](/cells/python-net/ru/aspose.cells.pivot/pivottable)
