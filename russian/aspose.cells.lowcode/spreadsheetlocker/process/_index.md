---
title: process метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.lowcode/spreadsheetlocker/process/
is_root: false
---
##  process(, load_options, save_options, provider){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-aspose.cells.lowcode.AbstractLowCodeProtectionProvider}
Блокирует файл электронной таблицы с указанными настройками.



```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/ru/aspose.cells.lowcode/lowcodeloadoptions) | Варианты ввода и загрузки|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptions) | Варианты вывода и сохранения|
| provider | [`AbstractLowCodeProtectionProvider`](/cells/python-net/ru/aspose.cells.lowcode/abstractlowcodeprotectionprovider) | Реализация для предоставления настроек защиты|


##  process(, файл_шаблона, файл_результата, пароль_открытия, пароль_записи){#str-str-str-str}
Блокирует файл электронной таблицы с указанными настройками.



```python

@staticmethod
def process(template_file, result_file, open_password, write_password):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| template_file | str | Файл шаблона, который будет заблокирован|
| result_file | str | Полученный файл|
| open_password | str | Пароль для шифрования файла|
| write_password | str |Пароль для защиты от изменения электронной таблицы|


##  process(, load_options, save_options, open_password, write_password){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str}
Блокирует файл электронной таблицы с указанными настройками.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/ru/aspose.cells.lowcode/lowcodeloadoptions) | Варианты ввода и загрузки|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptions) | Варианты вывода и сохранения|
| open_password | str | Пароль для шифрования файла|
| write_password | str |Пароль для защиты от изменения электронной таблицы|


##  process(, load_options, save_options, open_password, write_password, workbook_password, workbook_type){#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str-str-aspose.cells.ProtectionType}
Блокирует файл электронной таблицы с указанными настройками.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password, workbook_password, workbook_type):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/ru/aspose.cells.lowcode/lowcodeloadoptions) | Варианты ввода и загрузки|
| save_options | [`LowCodeSaveOptions`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesaveoptions) | Варианты вывода и сохранения|
| open_password | str | Пароль для шифрования файла|
| write_password | str |Пароль для защиты от изменения электронной таблицы|
| workbook_password | str | Пароль для защиты рабочей книги|
| workbook_type | [`ProtectionType`](/cells/python-net/ru/aspose.cells/protectiontype) | Тип защиты для защиты рабочей книги|



###  Смотрите также
* модуль [`aspose.cells.lowcode`](../../)
* класс [`SpreadsheetLocker`](/cells/python-net/ru/aspose.cells.lowcode/spreadsheetlocker)
