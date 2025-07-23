---
title: Name sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1000
url: /tr/aspose.cells/name/
is_root: false
---
##  Name sınıfı
Bir hücre aralığı için tanımlanmış bir adı temsil eder.



Name türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [comment](/cells/python-net/tr/aspose.cells/name/comment) | İsmin yorumunu alır ve ayarlar.<br/> Sadece Excel 2007 ve üzeri versiyonlar için geçerlidir.|
| [text](/cells/python-net/tr/aspose.cells/name/text) | Nesnenin isim metnini alır.|
| [full_text](/cells/python-net/tr/aspose.cells/name/full_text) | Kapsam ayarıyla nesnenin adının tam metnini alır.|
| [refers_to](/cells/python-net/tr/aspose.cells/name/refers_to) | Adın tanımlandığı formülü, eşittir işaretiyle başlayarak döndürür veya ayarlar.|
| [r1c1_refers_to](/cells/python-net/tr/aspose.cells/name/r1c1_refers_to) |[`Name`](/cells/python-net/tr/aspose.cells/name)'in R1C1 referansını alır veya ayarlar.|
| [is_referred](/cells/python-net/tr/aspose.cells/name/is_referred) | Bu ismin başka formüllerde de yer alıp almadığını gösterir.|
| [is_visible](/cells/python-net/tr/aspose.cells/name/is_visible) | İsmin görünür olup olmadığını belirtir.|
| [sheet_index](/cells/python-net/tr/aspose.cells/name/sheet_index) | Bu ismin Çalışma Kitabı veya Çalışma Sayfası'na ait olduğunu gösterir.<br/> 0 = Genel ad, aksi takdirde sayfaya endekslenir (bir tabanlı)|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get_refers_to(self, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/name/get_refers_to/#bool-bool) | Bu ismin referansını al.|
| [`get_refers_to(self, is_r1c1, is_local, row, column)`](/cells/python-net/tr/aspose.cells/name/get_refers_to/#bool-bool-int-int) | Belirtilen hücreye göre bu Adın referansını al.|
| [`get_ranges(self)`](/cells/python-net/tr/aspose.cells/name/get_ranges/#) | Bu isimle anılan tüm aralıkları alır.|
| [`get_ranges(self, recalculate)`](/cells/python-net/tr/aspose.cells/name/get_ranges/#bool) | Bu isimle anılan tüm aralıkları alır.|
| [`get_range(self)`](/cells/python-net/tr/aspose.cells/name/get_range/#) | Bu isim bir aralığa atıfta bulunuyorsa aralığı alır.|
| [`get_range(self, recalculate)`](/cells/python-net/tr/aspose.cells/name/get_range/#bool) | Bu isim bir aralığa atıfta bulunuyorsa aralığı alır|
| [`get_range(self, sheet_index, row, column)`](/cells/python-net/tr/aspose.cells/name/get_range/#int-int-int) | Bu isim bir aralığa atıfta bulunuyorsa aralığı alır.<br/> Bu ismin referansı mutlak değilse, aralık farklı hücreler için farklı olabilir.|
| [`set_refers_to(self, refers_to, is_r1c1, is_local)`](/cells/python-net/tr/aspose.cells/name/set_refers_to/#str-bool-bool) | Bu İsmin referansını ayarlayın.|
| [`get_referred_areas(self, recalculate)`](/cells/python-net/tr/aspose.cells/name/get_referred_areas/#bool) | Bu isimle anılan tüm referansları alır.|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Accessing the first worksheet in the Excel file
worksheet = workbook.worksheets[0]
# Creating a named range
range = worksheet.cells.create_range("B4", "G14")
# Setting the name of the named range
range.name = "TestRange"
# Saving the modified Excel file in default (that is Excel 2000) format
workbook.save("output.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`Name`](/cells/python-net/tr/aspose.cells/name)
