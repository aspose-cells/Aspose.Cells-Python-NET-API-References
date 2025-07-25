---
title: process метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.lowcode/spreadsheetsplitter/process/
is_root: false
---
##  process(, опции){#aspose.cells.lowcode.LowCodeSplitOptions}
Разделяет файл электронной таблицы на несколько частей.



```python

@staticmethod
def process(options):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| options | [`LowCodeSplitOptions`](/cells/python-net/ru/aspose.cells.lowcode/lowcodesplitoptions) | Варианты разделения электронной таблицы|


##  process(, файл_шаблона, файл_результата){#str-str}
Разбивает заданный файл шаблона на несколько частей.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| template_file | str | Файл шаблона, который нужно разделить|
| result_file | str | Результирующий файл (шаблон имени)|
###  Примечания

Выходные файлы будут созданы из указанного результирующего файла
добавление порядкового номера листа и разделенной части.
Например, если указанный выходной файл — Split.xlsx, то сгенерированный
файлы будут Split_0_0.xlsx, Split_0_1.xlsx, ..., Split_1_0.xlsx, ...


###  Смотрите также
* модуль [`aspose.cells.lowcode`](../../)
* класс [`SpreadsheetSplitter`](/cells/python-net/ru/aspose.cells.lowcode/spreadsheetsplitter)
