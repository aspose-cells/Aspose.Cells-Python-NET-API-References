---
title: Name sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1110
url: /tr/aspose.cells/name/
is_root: false
---
##  Name sınıfı
Bir hücre aralığı için tanımlanmış bir adı temsil eder.



Name türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [comment](/cells/python-net/tr/aspose.cells/name/comment) | İsmin yorumunu alır ve ayarlar.<br/> Yalnızca Excel 2007 veya üzeri sürümler için geçerlidir.|
| [text](/cells/python-net/tr/aspose.cells/name/text) | Nesnenin ad metnini alır.|
| [full_text](/cells/python-net/tr/aspose.cells/name/full_text) | Kapsam ayarıyla nesnenin adının tam metnini alır.|
| [refers_to](/cells/python-net/tr/aspose.cells/name/refers_to) | Adın başvuruda bulunmak üzere tanımlandığı formülü eşittir işaretiyle başlayarak döndürür veya ayarlar.|
| [r1c1_refers_to](/cells/python-net/tr/aspose.cells/name/r1c1_refers_to) | [`Name`](/cells/python-net/tr/aspose.cells/name)'in R1C1 referansını alır veya ayarlar.|
| [is_referred](/cells/python-net/tr/aspose.cells/name/is_referred) | Bu ismin başka formüllerle anılıp anılmadığını belirtir.|
| [is_visible](/cells/python-net/tr/aspose.cells/name/is_visible) | Adın görünür olup olmadığını belirtir.|
| [sheet_index](/cells/python-net/tr/aspose.cells/name/sheet_index) | Bu adın Çalışma Kitabı veya Çalışma Sayfasına ait olduğunu belirtir.<br/> 0 = Genel ad, aksi takdirde sayfaya dizin (tek tabanlı)|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [get_refers_to](/cells/python-net/tr/aspose.cells/name/get_refers_to/#bool-bool) | Bu İsmin referansını alın.|
| [get_refers_to](/cells/python-net/tr/aspose.cells/name/get_refers_to/#bool-bool-int-int) | Belirtilen hücreye göre bu Adın referansını alın.|
| [get_ranges](/cells/python-net/tr/aspose.cells/name/get_ranges/#) | Bu isimle anılan tüm aralıkları alır.|
| [get_ranges](/cells/python-net/tr/aspose.cells/name/get_ranges/#bool) | Bu isimle anılan tüm aralıkları alır.|
| [get_range](/cells/python-net/tr/aspose.cells/name/get_range/#) |Bu ad bir aralığa başvuruyorsa aralığı alır.|
| [get_range](/cells/python-net/tr/aspose.cells/name/get_range/#bool) | Bu ad bir aralığa başvuruyorsa aralığı alır|
| [get_range](/cells/python-net/tr/aspose.cells/name/get_range/#int-int-int) | Bu ad bir aralığa başvuruyorsa aralığı alır.<br/> Bu ismin referansı mutlak değilse aralık farklı hücreler için farklı olabilir.|
| [set_refers_to](/cells/python-net/tr/aspose.cells/name/set_refers_to/#str-bool-bool) | Bu Adın referansını ayarlayın.|
| [get_referred_areas](/cells/python-net/tr/aspose.cells/name/get_referred_areas/#bool) | Bu isimle anılan tüm referansları alır.|



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
