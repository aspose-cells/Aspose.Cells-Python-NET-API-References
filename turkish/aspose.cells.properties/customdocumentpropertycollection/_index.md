---
title: CustomDocumentPropertyCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 40
url: /tr/aspose.cells.properties/customdocumentpropertycollection/
is_root: false
---
##  CustomDocumentPropertyCollection sınıfı
Özel belge özelliklerinin bir koleksiyonu.



**Miras:** [`CustomDocumentPropertyCollection`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection)



CustomDocumentPropertyCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get(self, name)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/get/#str) |  |
| [`get(self, index)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/get/#int) |  |
| [`index_of(self, name)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/index_of/#str) |  |
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`add(self, name, value)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/add/#str-str) | Yeni bir özel belge özelliği oluşturur**ÖzellikTürü.Dize** veri türü.|
| [`add(self, name, value)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/add/#str-int) | Yeni bir özel belge özelliği oluşturur**ÖzellikTürü.Numarası** veri türü.|
| [`add(self, name, value)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/add/#str-datetime) | Yeni bir özel belge özelliği oluşturur**ÖzellikTürü.TarihSaat** veri türü.|
| [`add(self, name, value)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/add/#str-bool) | Yeni bir özel belge özelliği oluşturur**ÖzellikTürü.Boolean** veri türü.|
| [`add(self, name, value)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/add/#str-float) | Yeni bir özel belge özelliği oluşturur**Özellik Türü.Float** veri türü.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/binary_search/#aspose.cells.properties.documentproperty) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|
| [`add_link_to_content(self, name, source)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/add_link_to_content/#str-str) |İçeriğe bağlanan yeni bir özel belge özelliği oluşturur.|
| [`update_linked_property_value(self)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/update_linked_property_value/#) | İçeriğe bağlantı veren özel belge özelliği değerini güncelleyin.|
| [`update_linked_range(self)`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection/update_linked_range/#) | Özel belge özellik değerini bağlantılı aralığa güncelle.|



###  Notlar

Her [`DocumentProperty`](/cells/python-net/tr/aspose.cells.properties/documentproperty) nesnesi bir kapsayıcı belgenin özel bir özelliğini temsil eder.

###  Örnek

```python
from aspose.cells import Workbook

# Instantiate a Workbook object
workbook = Workbook("book1.xls")
# Retrieve a list of all custom document properties of the Excel file
customProperties = workbook.worksheets.custom_document_properties

```

###  Ayrıca bakınız
* modül [`aspose.cells.properties`](..)
* sınıf [`CustomDocumentPropertyCollection`](/cells/python-net/tr/aspose.cells.properties/customdocumentpropertycollection)
* sınıf [`DocumentProperty`](/cells/python-net/tr/aspose.cells.properties/documentproperty)
