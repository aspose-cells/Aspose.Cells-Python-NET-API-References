---
title: group_by метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 140
url: /ru/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by(self, interval, new_field) {#float-bool}
Автоматически группировать поле с внутренними



```python

def group_by(self, interval, new_field):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| interval | float | Внутреннее состояние группы.<br/> Если оно равно нулю, будет присвоено автоматическое значение,|
| new_field | bool | Указывает, следует ли добавлять новое поле в сводную таблицу.|


##  group_by(self, custom_group_items, new_field) {#list-bool}
Пользовательская группа полей.


###  Возврат

False означает, что это поле не может быть сгруппировано по дате и времени.


```python

def group_by(self, custom_group_items, new_field):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| custom_group_items | list | Пользовательские групповые элементы.|
| new_field | bool | Указывает, нужно ли добавлять новое поле в сводную таблицу|


##  group_by(self, start, end, interval, new_field) {#float-float-float-bool}
Сгруппируйте файл по номеру.


###  Возврат

False означает, что это поле не может быть сгруппировано по дате и времени.


```python

def group_by(self, start, end, interval, new_field):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| start | float | Начальное значение|
| end | float | Конец ценности|
| interval | float | Интервал|
| new_field | bool | Указывает, нужно ли добавлять новое поле в сводную таблицу|


##  group_by(self, start, end, groups, interval, first_as_new_field) {#DateTime-DateTime-list-float-bool}
Сгруппируйте файл по типу группы дат.


###  Возврат

False означает, что это поле не может быть сгруппировано по дате и времени.


```python

def group_by(self, start, end, groups, interval, first_as_new_field):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| start | DateTime | Дата и время начала|
| end | DateTime | Конец даты и времени|
| groups | list | Типы групп|
| interval | float | Интервал|
| first_as_new_field | bool | Указывает, следует ли добавлять новое поле в сводную таблицу.<br/> Только для первого группового товара.|



###  Смотрите также
* модуль [`aspose.cells.pivot`](../../)
* класс [`PivotField`](/cells/python-net/ru/aspose.cells.pivot/pivotfield)
