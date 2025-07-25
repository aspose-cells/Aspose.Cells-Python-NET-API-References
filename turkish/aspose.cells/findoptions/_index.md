---
title: FindOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 640
url: /tr/aspose.cells/findoptions/
is_root: false
---
##  FindOptions sınıfı
Bulma seçeneklerini temsil eder.



FindOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/findoptions/__init__/#) | FindOptions'ın yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [is_case_sensitive](/cells/python-net/tr/aspose.cells/findoptions/is_case_sensitive) | Aranan dizenin büyük/küçük harfe duyarlı olup olmadığını gösterir.|
| [case_sensitive](/cells/python-net/tr/aspose.cells/findoptions/case_sensitive) | Aranan dizenin büyük/küçük harfe duyarlı olup olmadığını gösterir.|
| [look_at_type](/cells/python-net/tr/aspose.cells/findoptions/look_at_type) | Tipine bak.|
| [is_range_set](/cells/python-net/tr/aspose.cells/findoptions/is_range_set) | Aranan aralığın ayarlanıp ayarlanmadığını gösterir.|
| [search_next](/cells/python-net/tr/aspose.cells/findoptions/search_next) |Arama sırası. Doğru: sonrakini ara. Yanlış: öncekini ara.|
| [search_backward](/cells/python-net/tr/aspose.cells/findoptions/search_backward) | Hücreler için geriye doğru arama yapın.|
| [seach_order_by_rows](/cells/python-net/tr/aspose.cells/findoptions/seach_order_by_rows) | Aramanın satırlara mı yoksa sütunlara mı göre sıralanacağını belirtir.|
| [search_order_by_rows](/cells/python-net/tr/aspose.cells/findoptions/search_order_by_rows) | Aramanın satırlara mı yoksa sütunlara mı göre sıralanacağını belirtir.|
| [look_in_type](/cells/python-net/tr/aspose.cells/findoptions/look_in_type) | Yazılışına bak.|
| [regex_key](/cells/python-net/tr/aspose.cells/findoptions/regex_key) | Aranan anahtarın regex olup olmadığını belirtir.<br/>Eğer doğruysa aranan anahtar regex olarak alınacak ve ayrıştırılacaktır.<br/> Aksi takdirde anahtar ms excel'deki kurallara göre ayrıştırılacaktır.|
| [value_type_sensitive](/cells/python-net/tr/aspose.cells/findoptions/value_type_sensitive) | Aranan hücre değer tipinin aranan anahtarla aynı olup olmadığını belirtir.|
| [style](/cells/python-net/tr/aspose.cells/findoptions/style) | Aranacak format.|
| [convert_numeric_data](/cells/python-net/tr/aspose.cells/findoptions/convert_numeric_data) | Aranan dize değerinin sayısal verilere dönüştürülüp dönüştürülmeyeceğini belirten bir değeri alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get_range(self)`](/cells/python-net/tr/aspose.cells/findoptions/get_range/#) | Aranan aralığı alır ve ayarlar.|
| [`set_range(self, ca)`](/cells/python-net/tr/aspose.cells/findoptions/set_range/#aspose.cells.cellarea) | Aranan aralığı ayarlar.|



###  Örnek

```python
from aspose.cells import CellArea, FindOptions, LookInType, Workbook

# Instantiate the workbook object
workbook = Workbook("book1.xls")
# Get Cells collection
cells = workbook.worksheets[0].cells
# Instantiate FindOptions Object
findOptions = FindOptions()
# Create a Cells Area
ca = CellArea()
ca.start_row = 8
ca.start_column = 2
ca.end_row = 17
ca.end_column = 13
# Set cells area for find options
findOptions.set_range(ca)
# Set searching properties
findOptions.search_backward = False
findOptions.seach_order_by_rows = True
findOptions.look_in_type = LookInType.VALUES
# Find the cell with 0 value
cell = cells.find(0, None, findOptions)

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
