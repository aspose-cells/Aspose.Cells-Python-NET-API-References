---
title: import_excel_file метод
second_title: Aspose.Cells.GridJs for Python via .NET API
description:
type: docs
weight: 110
url: /ru/aspose.cellsgridjs/gridjsworkbook/import_excel_file/
is_root: false
---
##  import_excel_file {#str}

Импортирует файл Excel из пути к файлу.



```python
def import_excel_file(self, file_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| file_name | str | Полный путь к файлу.|


##  import_excel_file {#str-str}

Импортирует файл Excel из пути к файлу.



```python
def import_excel_file(self, uid, file_name):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| uid | str | Уникальный идентификатор файлового кэша, если он равен нулю, он будет сгенерирован автоматически.|
| file_name | str | Полный путь к файлу.|


##  import_excel_file {#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat}

Импортирует файл Excel из потока файлов с форматом загрузки.



```python
def import_excel_file(self, filestream, format):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| filestream | io.RawIOBase | Поток файла Excel.|
| format | [`GridLoadFormat`](/cells/python-net/ru/aspose.cellsgridjs/gridloadformat) | LoadFormat файла Excel.|


##  import_excel_file {#str-str-str}

Импортирует файл Excel из пути к файлу и открытого пароля.



```python
def import_excel_file(self, uid, file_name, password):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| uid | str | Уникальный идентификатор файлового кэша, если он равен нулю, он будет сгенерирован автоматически.|
| file_name | str | Полный путь к файлу.|
| password | str | Пароль открытия файла Excel. Значение может быть нулевым, если пароль не установлен.|


##  import_excel_file {#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat}

Импортирует файл Excel из файлового потока.



```python
def import_excel_file(self, uid, filestream, format):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| uid | str | Уникальный идентификатор файлового кэша, если он равен нулю, он будет сгенерирован автоматически.|
| filestream | io.RawIOBase | Поток файла Excel.|
| format | [`GridLoadFormat`](/cells/python-net/ru/aspose.cellsgridjs/gridloadformat) | LoadFormat файла Excel.|


##  import_excel_file {#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str}

Импортирует файл Excel из файлового потока с форматом загрузки и открытым паролем.



```python
def import_excel_file(self, filestream, format, password):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| filestream | io.RawIOBase | Поток файла Excel.|
| format | [`GridLoadFormat`](/cells/python-net/ru/aspose.cellsgridjs/gridloadformat) | LoadFormat файла Excel.|
| password | str | Пароль открытия файла Excel. Значение может быть нулевым, если пароль не установлен.|


##  import_excel_file {#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str}

Импортирует файл Excel из файлового потока с форматом загрузки и открытым паролем.



```python
def import_excel_file(self, uid, filestream, format, password):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| uid | str | Уникальный идентификатор файлового кэша, если он равен нулю, он будет сгенерирован автоматически.|
| filestream | io.RawIOBase | Поток файла Excel.|
| format | [`GridLoadFormat`](/cells/python-net/ru/aspose.cellsgridjs/gridloadformat) | LoadFormat файла Excel.|
| password | str | Пароль открытия файла Excel. Значение может быть нулевым, если пароль не установлен.|



###  Смотрите также
* модуль [`aspose.cellsgridjs`](../../)
* класс [`GridJsWorkbook`](/cells/python-net/ru/aspose.cellsgridjs/gridjsworkbook)
