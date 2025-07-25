---
title: detect_file_format метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells/fileformatutil/detect_file_format/
is_root: false
---
##  detect_file_format(, поток){#io.RawIOBase}
Обнаруживает и возвращает информацию о формате Excel, сохраненном в потоке.


###  Возврат

Объект [`FileFormatInfo`](/cells/python-net/ru/aspose.cells/fileformatinfo), содержащий обнаруженную информацию.


```python

@staticmethod
def detect_file_format(stream):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase |  |


##  detect_file_format(, путь_к_файлу){#str}
Обнаруживает и возвращает информацию о формате Excel, сохраненном в файле.


###  Возврат

Объект [`FileFormatInfo`](/cells/python-net/ru/aspose.cells/fileformatinfo), содержащий обнаруженную информацию.


```python

@staticmethod
def detect_file_format(file_path):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| file_path | str | Путь к файлу.|


##  detect_file_format(, поток, пароль){#io.RawIOBase-str}
Обнаруживает и возвращает информацию о формате Excel, сохраненном в потоке.


###  Возврат

Объект [`FileFormatInfo`](/cells/python-net/ru/aspose.cells/fileformatinfo), содержащий обнаруженную информацию.


```python

@staticmethod
def detect_file_format(stream, password):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| password | str | Пароль для зашифрованных файлов OOXML.|


##  detect_file_format(, путь_к_файлу, пароль){#str-str}
Обнаруживает и возвращает информацию о формате Excel, сохраненном в файле.


###  Возврат

Объект [`FileFormatInfo`](/cells/python-net/ru/aspose.cells/fileformatinfo), содержащий обнаруженную информацию.


```python

@staticmethod
def detect_file_format(file_path, password):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| file_path | str | Путь к файлу.|
| password | str | Пароль для зашифрованных файлов OOXML.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`FileFormatInfo`](/cells/python-net/ru/aspose.cells/fileformatinfo)
* класс [`FileFormatUtil`](/cells/python-net/ru/aspose.cells/fileformatutil)
