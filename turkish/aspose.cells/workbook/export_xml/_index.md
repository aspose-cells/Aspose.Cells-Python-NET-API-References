---
title: export_xml yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 150
url: /tr/aspose.cells/workbook/export_xml/
is_root: false
---
##  export_xml(self, map_name, path) {#str-str}
Belirtilen XML haritasıyla bağlantılı XML verilerini dışa aktarın.



```python

def export_xml(self, map_name, path):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| map_name | str | dışa aktarılması gereken XML haritasının adı|
| path | str | ihracat yolu|

###  Örnek

Aşağıdaki kod, ilk XmlMap ile bağlantılı verileri dışa aktarır.

```python
from aspose.cells import Workbook

wb = Workbook("Book1.xlsx")
# Make sure that the source xlsx file contains a XmlMap.
xmlMap = wb.worksheets.xml_maps[0]
wb.export_xml(xmlMap.name, "output.xml")

```


##  export_xml(self, map_name, stream) {#str-io.RawIOBase}
XML verilerini dışa aktar.



```python

def export_xml(self, map_name, stream):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| map_name | str | dışa aktarılması gereken XML haritasının adı|
| stream | io.RawIOBase | ihracat akışı|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
