---
title: Slicer sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 10
url: /tr/aspose.cells.slicers/slicer/
is_root: false
---
##  Slicer sınıfı
Slicer Görünümünün özet açıklaması



Slicer türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [title](/cells/python-net/tr/aspose.cells.slicers/slicer/title) | Geçerli Slicer nesnesinin başlığını belirtir.|
| [alternative_text](/cells/python-net/tr/aspose.cells.slicers/slicer/alternative_text) | Slicer nesnesinin açıklayıcı (alternatif) metin dizesini döndürür veya ayarlar.|
| [is_printable](/cells/python-net/tr/aspose.cells.slicers/slicer/is_printable) | Dilimleyici nesnesinin yazdırılabilir olup olmadığını belirtir.|
| [is_locked](/cells/python-net/tr/aspose.cells.slicers/slicer/is_locked) | Dilimleyici şeklinin kilitli olup olmadığını gösterir.|
| [placement](/cells/python-net/tr/aspose.cells.slicers/slicer/placement) | Çizim nesnesinin altındaki hücrelere bağlanma şeklini gösterir.<br/> Özellik, bir nesnenin çalışma sayfasındaki yerleşimini kontrol eder.|
| [locked_aspect_ratio](/cells/python-net/tr/aspose.cells.slicers/slicer/locked_aspect_ratio) | En boy oranının kilitlenip kilitlenmediğini gösterir.|
| [locked_position](/cells/python-net/tr/aspose.cells.slicers/slicer/locked_position) |Belirtilen dilimleyicinin kullanıcı arayüzü kullanılarak taşınıp taşınamayacağını veya yeniden boyutlandırılıp boyutlandırılamayacağını belirtir.|
| [shape](/cells/python-net/tr/aspose.cells.slicers/slicer/shape) | Belirtilen dilimleyiciyle ilişkili Shape nesnesini döndürür. Salt okunur.|
| [slicer_cache](/cells/python-net/tr/aspose.cells.slicers/slicer/slicer_cache) | Dilimleyiciyle ilişkili SlicerCache nesnesini döndürür. Salt okunur.|
| [parent](/cells/python-net/tr/aspose.cells.slicers/slicer/parent) | Bu dilimleyiciyi içeren [`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet) nesnesini döndürür. Salt okunur.|
| [style_type](/cells/python-net/tr/aspose.cells.slicers/slicer/style_type) | Yerleşik dilimleyici stilinin türünü belirtin<br/> varsayılan tür SlicerStyleLight1'dir|
| [name](/cells/python-net/tr/aspose.cells.slicers/slicer/name) | Belirtilen dilimleyicinin adını döndürür veya ayarlar|
| [caption](/cells/python-net/tr/aspose.cells.slicers/slicer/caption) | Belirtilen dilimleyicinin başlığını döndürür veya ayarlar.|
| [caption_visible](/cells/python-net/tr/aspose.cells.slicers/slicer/caption_visible) | Dilimleyici Başlığını görüntüleyen başlığın görünür olup olmadığını döndürür veya ayarlar<br/> varsayılan değer doğrudur|
| [number_of_columns](/cells/python-net/tr/aspose.cells.slicers/slicer/number_of_columns) | Belirtilen dilimleyicideki sütun sayısını döndürür veya ayarlar.|
| [left_pixel](/cells/python-net/tr/aspose.cells.slicers/slicer/left_pixel) | Dilimleyici şeklinin sol sütunundan yatay uzaklığını piksel cinsinden döndürür veya ayarlar.|
| [top_pixel](/cells/python-net/tr/aspose.cells.slicers/slicer/top_pixel) | Dilimleyici şeklinin üst satırından dikey uzaklığını piksel cinsinden döndürür veya ayarlar.|
| [width](/cells/python-net/tr/aspose.cells.slicers/slicer/width) | Belirtilen dilimleyicinin genişliğini noktalar halinde döndürür veya ayarlar.|
| [width_pixel](/cells/python-net/tr/aspose.cells.slicers/slicer/width_pixel) |Belirtilen dilimleyicinin genişliğini piksel cinsinden döndürür veya ayarlar.|
| [height](/cells/python-net/tr/aspose.cells.slicers/slicer/height) | Belirtilen dilimleyicinin yüksekliğini nokta cinsinden döndürür veya ayarlar.|
| [height_pixel](/cells/python-net/tr/aspose.cells.slicers/slicer/height_pixel) | Belirtilen dilimleyicinin yüksekliğini piksel cinsinden döndürür veya ayarlar.|
| [column_width_pixel](/cells/python-net/tr/aspose.cells.slicers/slicer/column_width_pixel) | Dilimleyicideki her sütunun genişliğini piksel cinsinden alır veya ayarlar.|
| [column_width](/cells/python-net/tr/aspose.cells.slicers/slicer/column_width) | Dilimleyicideki her sütunun genişliğini puan olarak döndürür veya ayarlar.|
| [row_height_pixel](/cells/python-net/tr/aspose.cells.slicers/slicer/row_height_pixel) | Belirtilen dilimleyicideki her satırın yüksekliğini piksel cinsinden döndürür veya ayarlar.|
| [row_height](/cells/python-net/tr/aspose.cells.slicers/slicer/row_height) | Belirtilen dilimleyicideki her satırın yüksekliğini puan cinsinden döndürür veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add_pivot_connection(self, pivot)`](/cells/python-net/tr/aspose.cells.slicers/slicer/add_pivot_connection/#aspose.cells.pivot.pivottable) | PivotTable bağlantısı ekler.|
| [`remove_pivot_connection(self, pivot)`](/cells/python-net/tr/aspose.cells.slicers/slicer/remove_pivot_connection/#aspose.cells.pivot.pivottable) | PivotTable bağlantısını kaldırır.|
| [`refresh(self)`](/cells/python-net/tr/aspose.cells.slicers/slicer/refresh/#) | Dilimleyiciyi yeniliyoruz. Bu arada, göreceli PivotTable'ları yeniliyoruz ve hesaplıyoruz.|



###  Örnek

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from aspose.cells.slicers import SlicerStyleType

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
pivot.refresh_data()
pivot.calculate_data()
slicers = sheet.slicers
slicerIndex = slicers.add(pivot, "E12", "fruit")
slicer = slicers[slicerIndex]
slicer.style_type = SlicerStyleType.SLICER_STYLE_LIGHT2
items = slicer.slicer_cache.slicer_cache_items
item = items[0]
item.selected = False
# do your business
book.save("out.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells.slicers`](..)
* sınıf [`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet)
