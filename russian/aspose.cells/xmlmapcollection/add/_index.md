---
title: add метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells/xmlmapcollection/add/
is_root: false
---
##  add(self, url) {#str}
Добавьте [`XmlMap`](/cells/python-net/ru/aspose.cells/xmlmap) к URL/пути файла xml/xsd.


###  Возврат

Индекс объекта [`XmlMap`](/cells/python-net/ru/aspose.cells/xmlmap).


```python

def add(self, url):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| url | str | URL/путь к файлу xml/xsd.|

###  Пример

Следующий код добавляет два XmlMaps с помощью файла xsd и файла xml.

```python
from aspose.cells import Workbook

wb = Workbook()
xmlMapCollection = wb.worksheets.xml_maps
# Add a XmlMap by a xsd file.
xmlMapCollection.add("schema.xsd")
# Add a XmlMap by a xml file.
xmlMapCollection.add("xml.xml")
wb.save("twoXmlMaps.xlsx")

```



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`XmlMap`](/cells/python-net/ru/aspose.cells/xmlmap)
* класс [`XmlMapCollection`](/cells/python-net/ru/aspose.cells/xmlmapcollection)
