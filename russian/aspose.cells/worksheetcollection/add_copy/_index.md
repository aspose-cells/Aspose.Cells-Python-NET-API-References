---
title: add_copy метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 30
url: /ru/aspose.cells/worksheetcollection/add_copy/
is_root: false
---
##  add_copy {#str}
Добавляет лист в коллекцию и копирует данные из существующего листа.


###  Возврат

Индекс объекта [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet).


```python
def add_copy(self, sheet_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| sheet_name | str | Имя исходного листа.|
###  Исключения
| Исключение| Описание|
| :- | :- |
| [`CellsException`](/cells/python-net/ru/aspose.cells/cellsexception) | Указывает недопустимое имя листа.|




##  add_copy {#int}
Добавляет лист в коллекцию и копирует данные из существующего листа.


###  Возврат

Индекс объекта [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet).


```python
def add_copy(self, sheet_index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| sheet_index | int | Указатель исходного листа.|


##  add_copy {#list-list}
Скопируйте группу листов.



```python
def add_copy(self, source, dest_sheet_names):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| source | list | Исходные листы.|
| dest_sheet_names | list | Имена копируемых листов.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CellsException`](/cells/python-net/ru/aspose.cells/cellsexception)
* класс [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet)
* класс [`WorksheetCollection`](/cells/python-net/ru/aspose.cells/worksheetcollection)
