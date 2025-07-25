---
title: VbaModuleCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells.vba/vbamodulecollection/
is_root: false
---
##  VbaModuleCollection sınıfı
[`VbaModule`](/cells/python-net/tr/aspose.cells.vba/vbamodule) listesini temsil eder



VbaModuleCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, sheet)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.worksheet) | Çalışma sayfasına modül ekler.|
| [`add(self, type, name)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.vbamoduletype-str) | Modül ekler.|
| [`get(self, index)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/get/#int) | İndeksteki listede [`VbaModule`](/cells/python-net/tr/aspose.cells.vba/vbamodule)'i bulur.|
| [`get(self, name)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/get/#str) | Adına göre listede [`VbaModule`](/cells/python-net/tr/aspose.cells.vba/vbamodule)'i bulur.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`add_designer_storage(self, name, data)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [`get_designer_storage(self, name)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | Tasarımcının verilerini temsil eder.|
| [`add_user_form(self, name, codes, designer_storage)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) | Kullanıcı formunu VBA Projesine ekleyin.|
| [`remove_by_worksheet(self, sheet)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/remove_by_worksheet/#aspose.cells.worksheet) | Bir çalışma sayfasının modülünü kaldırır.|
| [`remove_by_name(self, name)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/remove_by_name/#str) | Modülü adına göre kaldırın|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.vbamodule) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook
from aspose.cells.vba import VbaModuleType

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add a new module.
vbaProject.modules.add(VbaModuleType.CLASS, "test")
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Ayrıca bakınız
* modül [`aspose.cells.vba`](..)
* sınıf [`VbaModule`](/cells/python-net/tr/aspose.cells.vba/vbamodule)
