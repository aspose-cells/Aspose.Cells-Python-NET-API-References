---
title: find метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 290
url: /ru/aspose.cells/cells/find/
is_root: false
---
##  find(self, what, previous_cell) {#any-aspose.cells.Cell}
Находит ячейку, содержащую входной объект.


###  Возврат

Cell объект.


```python

def find(self, what, previous_cell):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| what | any | Объект поиска.<br/> Тип должен быть int,double,DateTime,string,bool.|
| previous_cell | [`Cell`](/cells/python-net/ru/aspose.cells/cell) | Предыдущая ячейка с тем же объектом.<br/> Этот параметр можно установить равным нулю, если поиск выполняется с самого начала.|
###  Примечания

Возвращает null (ничего), если ячейка не найдена.

##  find(self, what, previous_cell, find_options) {#any-aspose.cells.Cell-aspose.cells.FindOptions}

Находит ячейку, содержащую входной объект.


###  Возврат

Cell объект.


```python

def find(self, what, previous_cell, find_options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| what | any | Объект поиска.<br/> Тип должен быть int,double,DateTime,string,bool.|
| previous_cell | [`Cell`](/cells/python-net/ru/aspose.cells/cell) | Предыдущая ячейка с тем же объектом.<br/> Этот параметр можно установить равным нулю, если поиск выполняется с самого начала.|
| find_options | [`FindOptions`](/cells/python-net/ru/aspose.cells/findoptions) | Найти варианты|
###  Примечания

Возвращает null (ничего), если ячейка не найдена.


###  Смотрите также

* модуль [`aspose.cells`](../../)
* класс [`Cells`](/cells/python-net/ru/aspose.cells/cells)
