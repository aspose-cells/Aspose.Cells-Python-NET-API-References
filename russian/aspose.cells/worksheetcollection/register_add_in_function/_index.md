---
title: register_add_in_function метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 180
url: /ru/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function(self, id, function_name) {#int-str}
Добавляет функцию надстройки в рабочую книгу


###  Возврат

URL-адрес файла надстройки, содержащего функции надстройки


```python

def register_add_in_function(self, id, function_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| id | int |Идентификатор данных, содержащих дополнительные функции,<br/> можно получить первым вызовом [`WorksheetCollection.register_add_in_function`](/cells/python-net/ru/aspose.cells/worksheetcollection/register_add_in_function) для того же файла надстройки.|
| function_name | str | имя функции надстройки|


##  register_add_in_function(self, add_in_file, function_name, lib) {#str-str-bool}
Добавляет функцию надстройки в рабочую книгу


###  Возврат

Идентификатор данных, содержащих заданную функцию надстройки


```python

def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| add_in_file | str | файл содержит дополнительные функции|
| function_name | str | имя функции надстройки|
| lib | bool | находится ли данный файл надстройки в каталоге или подкаталоге библиотеки надстроек Workbook.<br/>Этот флаг вступает в силу и имеет значение, когда addInFile имеет относительный путь:<br/> true означает, что путь указан относительно библиотеки надстроек, а false означает, что путь указан относительно данной рабочей книги.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`WorksheetCollection`](/cells/python-net/ru/aspose.cells/worksheetcollection)
