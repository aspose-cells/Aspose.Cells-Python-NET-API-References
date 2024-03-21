---
title: register_add_in_function метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 180
url: /ru/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function {#int-str}
Добавляет функцию надстройки в книгу


###  Возврат

URL-адрес файла надстройки, который содержит функции надстройки.


```python
def register_add_in_function(self, id, function_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| id | int | Идентификатор данных, содержащих дополнительные функции,<br/> можно получить первым вызовом [`WorksheetCollection.register_add_in_function`](/cells/python-net/ru/aspose.cells/worksheetcollection/register_add_in_function) для того же файла надстройки.|
| function_name | str | имя функции надстройки|


##  register_add_in_function {#str-str-bool}
Добавляет функцию надстройки в книгу


###  Возврат

Идентификатор данных, содержащих данную дополнительную функцию


```python
def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| add_in_file | str | файл содержит дополнительные функции|
| function_name | str | имя функции надстройки|
| lib | bool | находится ли данный файл надстройки в каталоге или подкаталоге библиотеки надстроек рабочей книги.<br/>Этот флаг вступает в силу и имеет значение, если заданный addInFile имеет относительный путь:<br/> true означает, что путь указан относительно библиотеки надстроек, а false означает, что путь указан относительно этой книги.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`WorksheetCollection`](/cells/python-net/ru/aspose.cells/worksheetcollection)
