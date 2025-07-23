---
title: import_xml метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 230
url: /ru/aspose.cells/workbook/import_xml/
is_root: false
---
##  import_xml(self, url, sheet_name, row, col) {#str-str-int-int}
Импортирует/обновляет XML-файл данных в рабочую книгу.



```python

def import_xml(self, url, sheet_name, row, col):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| url | str | URL/путь к XML-файлу.|
| sheet_name | str | имя листа назначения.|
| row | int | строка назначения|
| col | int | столбец назначения|

###  Пример

Следующий код импортирует XML-данные на рабочий лист «Лист 1» по адресу Cell A1.

```python
from aspose.cells import Workbook

wb = Workbook("Book1.xlsx")
wb.import_xml("xml.xml", "Sheet1", 0, 0)
wb.save("output.xlsx")

```


##  import_xml(self, stream, sheet_name, row, col) {#io.RawIOBase-str-int-int}
Импортирует/обновляет XML-файл данных в рабочую книгу.



```python

def import_xml(self, stream, sheet_name, row, col):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase | поток XML-файлов.|
| sheet_name | str | имя листа назначения.|
| row | int | строка назначения.|
| col | int | столбец назначения.|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
