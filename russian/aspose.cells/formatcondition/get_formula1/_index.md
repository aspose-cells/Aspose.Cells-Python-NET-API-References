---
title: get_formula1 метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells/formatcondition/get_formula1/
is_root: false
---
##  get_formula1(self, is_r1c1, is_local) {#bool-bool}
Возвращает значение или выражение, связанное с этим условием формата.


###  Возврат

Значение или выражение, связанное с этим условием формата.


```python

def get_formula1(self, is_r1c1, is_local):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| is_r1c1 | bool | Необходимо ли форматировать формулу как R1C1.|
| is_local | bool | Необходимо ли форматировать формулу в соответствии с локалью.|


##  get_formula1(self, row, column) {#int-int}
Получает формулу условного форматирования ячейки.


###  Возврат

Формула.


```python

def get_formula1(self, row, column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| row | int | Индекс строки.|
| column | int | Индекс столбца.|


##  get_formula1(self, is_r1c1, is_local, row, column) {#bool-bool-int-int}
Возвращает значение или выражение условного форматирования ячейки.


###  Возврат

Значение или выражение, связанное с условным форматированием ячейки.


```python

def get_formula1(self, is_r1c1, is_local, row, column):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| is_r1c1 | bool | Необходимо ли форматировать формулу как R1C1.|
| is_local | bool | Необходимо ли форматировать формулу в соответствии с локалью.|
| row | int | Индекс строки.|
| column | int | Индекс столбца.|
###  Примечания

Указанная ячейка должна быть ограничена этим условным форматированием, в противном случае будет возвращено значение null.


###  Смотрите также

* модуль [`aspose.cells`](../../)
* класс [`FormatCondition`](/cells/python-net/ru/aspose.cells/formatcondition)
