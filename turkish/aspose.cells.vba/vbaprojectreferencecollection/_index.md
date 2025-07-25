---
title: VbaProjectReferenceCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 50
url: /tr/aspose.cells.vba/vbaprojectreferencecollection/
is_root: false
---
##  VbaProjectReferenceCollection sınıfı
VBA projesinin tüm referanslarını temsil eder.



VbaProjectReferenceCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.vba/vbaprojectreferencecollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.vba/vbaprojectreferencecollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.vba/vbaprojectreferencecollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.vba/vbaprojectreferencecollection/index_of/#aspose.cells.vba.vbaprojectreference-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.vba/vbaprojectreferencecollection/index_of/#aspose.cells.vba.vbaprojectreference-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#aspose.cells.vba.vbaprojectreference) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#aspose.cells.vba.vbaprojectreference-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#aspose.cells.vba.vbaprojectreference-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`add_registered_reference(self, name, libid)`](/cells/python-net/tr/aspose.cells.vba/vbaprojectreferencecollection/add_registered_reference/#str-str) | Otomasyon türü bir kütüphaneye referans ekleyin.|
| [`add_control_refrernce(self, name, libid, twiddledlibid, extended_libid)`](/cells/python-net/tr/aspose.cells.vba/vbaprojectreferencecollection/add_control_refrernce/#str-str-str-str) |Twiddled tip kütüphanesine ve onun genişletilmiş tip kütüphanesine bir referans ekleyin.|
| [`add_project_refrernce(self, name, absolute_libid, relative_libid)`](/cells/python-net/tr/aspose.cells.vba/vbaprojectreferencecollection/add_project_refrernce/#str-str-str) | Harici bir VBA projesine referans ekler.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.vba/vbaprojectreferencecollection/binary_search/#aspose.cells.vba.vbaprojectreference) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add vba project reference
vbaProject.references.add_registered_reference("stdole", "*\\G{00020430-0000-0000-C000-000000000046}#2.0#0#C:\\Windows\\system32\\stdole2.tlb#OLE Automation")
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Ayrıca bakınız
* modül [`aspose.cells.vba`](..)
