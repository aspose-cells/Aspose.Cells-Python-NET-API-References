---
title: ContentTypePropertyCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 30
url: /tr/aspose.cells.properties/contenttypepropertycollection/
is_root: false
---
##  ContentTypePropertyCollection sınıfı
Ek bilgileri temsil eden [ContentTypeProperty](/cells/python-net/tr/aspose.cells.properties/contenttypeproperty) nesne koleksiyonu.



ContentTypePropertyCollection türü aşağıdaki üyeleri gösterir:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.properties/contenttypepropertycollection/capacity) | Dizi listesinin içerebileceği öğe sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add(name, value)](/cells/python-net/tr/aspose.cells.properties/contenttypepropertycollection/add/#str-str) | İçerik türü özellik bilgilerini ekler.|
| [add(name, value, type)](/cells/python-net/tr/aspose.cells.properties/contenttypepropertycollection/add/#str-str-str) | İçerik türü özellik bilgilerini ekler.|
| [copy_to(array)](/cells/python-net/tr/aspose.cells.properties/contenttypepropertycollection/copy_to/#list) | Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [copy_to(index, array, array_index, count)](/cells/python-net/tr/aspose.cells.properties/contenttypepropertycollection/copy_to/#int-list-int-int) |Dizi listesindeki bir dizi öğeyi, hedef dizi listesinin belirtilen dizininden başlayarak uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [index_of(item, index)](/cells/python-net/tr/aspose.cells.properties/contenttypepropertycollection/index_of/#ContentTypeProperty-int) | Belirtilen nesneyi arar ve belirtilen dizinden son öğeye uzanan dizi listesindeki öğelerin aralığındaki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [index_of(item, index, count)](/cells/python-net/tr/aspose.cells.properties/contenttypepropertycollection/index_of/#ContentTypeProperty-int-int) | Belirtilen nesneyi arar ve belirtilen dizinde başlayan ve belirtilen sayıda öğe içeren dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of(item)](/cells/python-net/tr/aspose.cells.properties/contenttypepropertycollection/last_index_of/#ContentTypeProperty) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of(item, index)](/cells/python-net/tr/aspose.cells.properties/contenttypepropertycollection/last_index_of/#ContentTypeProperty-int) | Belirtilen nesneyi arar ve ilk öğeden belirtilen dizine kadar uzanan dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of(item, index, count)](/cells/python-net/tr/aspose.cells.properties/contenttypepropertycollection/last_index_of/#ContentTypeProperty-int-int) |Belirtilen nesneyi arar ve belirtilen sayıda öğeyi içeren ve belirtilen dizinde biten dizi listesindeki öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [binary_search(item)](/cells/python-net/tr/aspose.cells.properties/contenttypepropertycollection/binary_search/#ContentTypeProperty) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfır tabanlı dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Add a new property.
workbook.content_type_properties.add("Admin", "Aspose", "text")
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Ayrıca bakınız
* modül [aspose.cells.properties](..)
* sınıf [ContentTypeProperty](/cells/python-net/tr/aspose.cells.properties/contenttypeproperty)
