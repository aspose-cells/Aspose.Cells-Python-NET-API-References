---
title: import_xml yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 230
url: /tr/aspose.cells/workbook/import_xml/
is_root: false
---
##  import_xml(self, url, sheet_name, row, col) {#str-str-int-int}
XML veri dosyasını çalışma kitabına aktarır/günceller.



```python

def import_xml(self, url, sheet_name, row, col):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| url | str | xml dosyasının url'si/yolu.|
| sheet_name | str | hedef sayfa adı.|
| row | int | hedef satır|
| col | int | hedef sütunu|

###  Örnek

Aşağıdaki kod XML verilerini Cell A1 adresindeki 'Sayfa 1' çalışma sayfasına aktarır.

```python
from aspose.cells import Workbook

wb = Workbook("Book1.xlsx")
wb.import_xml("xml.xml", "Sheet1", 0, 0)
wb.save("output.xlsx")

```


##  import_xml(self, stream, sheet_name, row, col) {#io.RawIOBase-str-int-int}
XML veri dosyasını çalışma kitabına aktarır/günceller.



```python

def import_xml(self, stream, sheet_name, row, col):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| stream | io.RawIOBase | xml dosya akışı.|
| sheet_name | str | hedef sayfa adı.|
| row | int | hedef satırı.|
| col | int | hedef sütunu.|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
