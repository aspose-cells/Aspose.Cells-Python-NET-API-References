---
title: export_xml метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 150
url: /ru/aspose.cells/workbook/export_xml/
is_root: false
---
##  export_xml(self, map_name, path) {#str-str}
Экспорт XML-данных, связанных с указанной XML-картой.



```python

def export_xml(self, map_name, path):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| map_name | str | имя XML-карты, которую необходимо экспортировать|
| path | str | экспортный путь|

###  Пример

Следующий код экспортирует данные, связанные первым XmlMap.

```python
from aspose.cells import Workbook

wb = Workbook("Book1.xlsx")
# Make sure that the source xlsx file contains a XmlMap.
xmlMap = wb.worksheets.xml_maps[0]
wb.export_xml(xmlMap.name, "output.xml")

```


##  export_xml(self, map_name, stream) {#str-io.RawIOBase}
Экспорт XML-данных.



```python

def export_xml(self, map_name, stream):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| map_name | str | имя XML-карты, которую необходимо экспортировать|
| stream | io.RawIOBase | экспортный поток|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`Workbook`](/cells/python-net/ru/aspose.cells/workbook)
