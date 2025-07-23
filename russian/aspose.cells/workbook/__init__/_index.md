---
title: Workbook конструктор
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 10
url: /ru/aspose.cells/workbook/__init__/
is_root: false
---
##  \_\_init\_\_(self){#}
Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook).



```python

def __init__(self):
    ...
```


###  Примечания

Формат файла по умолчанию — XLSX. Для создания файлов других типов используйте Workbook(FileFormatType).
###  Пример


В следующем коде показано, как использовать конструктор Workbook для создания и инициализации нового экземпляра класса.

```python
from aspose.cells import Workbook

workbook = Workbook()

```


##  \_\_init\_\_(self, file_format_type){#aspose.cells.FileFormatType}
Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook).



```python

def __init__(self, file_format_type):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| file_format_type | [`FileFormatType`](/cells/python-net/ru/aspose.cells/fileformattype) | Новый формат файла.|
###  Примечания

Тип формата файла по умолчанию — Excel97To2003.
###  Пример


В следующем коде показано, как использовать конструктор Workbook для создания и инициализации нового экземпляра класса с различными типами форматов файлов.

```python
from aspose.cells import FileFormatType, Workbook

workbook = Workbook(FileFormatType.XLSX)

```


##  \_\_init\_\_(сам, файл){#str}
Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook) и открывает файл.



```python

def __init__(self, file):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| file | str | Имя файла.|


##  \_\_init\_\_(self, stream){#io.RawIOBase}
Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook) и открывает поток.



```python

def __init__(self, stream):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase | Поток.|


##  \_\_init\_\_(self, file, load_options){#str-aspose.cells.LoadOptions}
Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook) и открывает файл.



```python

def __init__(self, file, load_options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| file | str | Имя файла.|
| load_options | [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions) | Варианты загрузки|


##  \_\_init\_\_(self, stream, load_options){#io.RawIOBase-aspose.cells.LoadOptions}
Инициализирует новый экземпляр класса [`Workbook`](/cells/python-net/ru/aspose.cells/workbook) и открывает поток.



```python

def __init__(self, stream, load_options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase | Поток.|
| load_options | [`LoadOptions`](/cells/python-net/ru/aspose.cells/loadoptions) | Варианты загрузки|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
