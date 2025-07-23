---
title: add_copy метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 30
url: /ru/aspose.cells/worksheetcollection/add_copy/
is_root: false
---
##  add_copy(self, sheet_name) {#str}
Добавляет рабочий лист в коллекцию и копирует данные из существующего рабочего листа.


###  Возврат

Индекс объекта [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet).


```python

def add_copy(self, sheet_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| sheet_name | str | Имя исходного рабочего листа.|
###  Исключения
| Исключение| Описание|
| :- | :- |
| [`CellsException`](/cells/python-net/ru/aspose.cells/cellsexception) | Указывает недопустимое имя рабочего листа.|




##  add_copy(self, sheet_index) {#int}
Добавляет рабочий лист в коллекцию и копирует данные из существующего рабочего листа.


###  Возврат

Индекс объекта [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet).


```python

def add_copy(self, sheet_index):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| sheet_index | int | Индекс исходного рабочего листа.|


##  add_copy(self, source, dest_sheet_names) {#list-list}
Скопируйте группу рабочих листов.



```python

def add_copy(self, source, dest_sheet_names):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| source | list | Исходные рабочие листы.|
| dest_sheet_names | list | Названия скопированных листов.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CellsException`](/cells/python-net/ru/aspose.cells/cellsexception)
* класс [`Worksheet`](/cells/python-net/ru/aspose.cells/worksheet)
* класс [`WorksheetCollection`](/cells/python-net/ru/aspose.cells/worksheetcollection)
