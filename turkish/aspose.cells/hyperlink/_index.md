---
title: Hyperlink sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 840
url: /tr/aspose.cells/hyperlink/
is_root: false
---
##  Hyperlink sınıfı
Köprüyü temsil eden nesneyi kapsüller.



Hyperlink türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [address](/cells/python-net/tr/aspose.cells/hyperlink/address) | Bir köprünün adresini temsil eder.|
| [text_to_display](/cells/python-net/tr/aspose.cells/hyperlink/text_to_display) | Belirtilen köprü için görüntülenecek metni temsil eder. Varsayılan değer köprünün adresidir.|
| [area](/cells/python-net/tr/aspose.cells/hyperlink/area) | Köprü aralığını alır.|
| [screen_tip](/cells/python-net/tr/aspose.cells/hyperlink/screen_tip) | Belirtilen köprünün Ekran İpucu metnini döndürür veya ayarlar.|
| [link_type](/cells/python-net/tr/aspose.cells/hyperlink/link_type) | Bağlantı türünü alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [delete](/cells/python-net/tr/aspose.cells/hyperlink/delete/#) |Bu köprüyü siler|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Workbook object
workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Adding a hyperlink to a URL at "A1" cell
index = worksheet.hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Getting a Hyperlink by index.
hyperlink = worksheet.hyperlinks[index]
# Setting display text of this hyperlink.
hyperlink.text_to_display = "Aspose"
# Saving the Excel file
workbook.save("book1.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
