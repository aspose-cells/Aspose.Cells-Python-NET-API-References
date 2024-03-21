---
title: group_by метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 80
url: /ru/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by {#float-bool}
Автоматически группировать поле с внутренними



```python
def group_by(self, interval, new_field):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| interval | float | Внутренняя часть группы.<br/> Автоматическое значение будет присвоено, если оно равно нулю.|
| new_field | bool | Указывает, добавляется ли новое поле в сводную таблицу.|


##  group_by {#list-bool}
Пользовательская группировка поля.



```python
def group_by(self, custom_group_items, new_field):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| custom_group_items | list | Элементы пользовательской группы.|
| new_field | bool |Указывает, добавляется ли новое поле в сводную таблицу.|


##  group_by {#float-float-float-bool}
Сгруппируйте файл по номеру.



```python
def group_by(self, start, end, interval, new_field):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| start | float | Начальное значение|
| end | float | Конец ценности|
| interval | float | Интервал|
| new_field | bool |Указывает, добавляется ли новое поле в сводную таблицу.|


##  group_by {#DateTime-DateTime-list-float-bool}
Сгруппируйте файл по типам групп дат.



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
| first_as_new_field | bool | Указывает, добавляется ли новое поле в сводную таблицу.<br/> Только для первого элемента группы.|



###  Смотрите также
* модуль [`aspose.cells.pivot`](../../)
* класс [`PivotField`](/cells/python-net/ru/aspose.cells.pivot/pivotfield)
