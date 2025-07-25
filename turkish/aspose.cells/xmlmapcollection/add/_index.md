---
title: add yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/xmlmapcollection/add/
is_root: false
---
##  add(self, url) {#str}
Bir xml/xsd dosyasının url/path kısmına [`XmlMap`](/cells/python-net/tr/aspose.cells/xmlmap) ekleyin.


###  İadeler

[`XmlMap`](/cells/python-net/tr/aspose.cells/xmlmap) nesne dizini.


```python

def add(self, url):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| url | str | xml/xsd dosyasının url/yolu.|

###  Örnek

Aşağıdaki kod, bir xsd dosyası ve bir xml dosyası kullanarak iki XmlMap ekler.

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



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`XmlMap`](/cells/python-net/tr/aspose.cells/xmlmap)
* sınıf [`XmlMapCollection`](/cells/python-net/tr/aspose.cells/xmlmapcollection)
