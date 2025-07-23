---
title: ValidationCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1530
url: /tr/aspose.cells/validationcollection/
is_root: false
---
##  ValidationCollection sınıfı
Veri doğrulama toplanmasını temsil eder.



ValidationCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/validationcollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self)`](/cells/python-net/tr/aspose.cells/validationcollection/add/#) | Koleksiyona veri doğrulaması ekler.|
| [`add(self, ca)`](/cells/python-net/tr/aspose.cells/validationcollection/add/#aspose.cells.cellarea) | Koleksiyona veri doğrulaması ekler.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells/validationcollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells/validationcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/validationcollection/index_of/#aspose.cells.validation-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/validationcollection/index_of/#aspose.cells.validation-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`remove_a_cell(self, row, column)`](/cells/python-net/tr/aspose.cells/validationcollection/remove_a_cell/#int-int) | Hücredeki tüm doğrulama ayarlarını kaldırır.|
| [`remove_area(self, ca)`](/cells/python-net/tr/aspose.cells/validationcollection/remove_area/#aspose.cells.cellarea) | Aralıktaki tüm doğrulama ayarlarını kaldırır.|
| [`get_validation_in_cell(self, row, column)`](/cells/python-net/tr/aspose.cells/validationcollection/get_validation_in_cell/#int-int) | Verilen hücreye uygulanan doğrulamayı alır.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells/validationcollection/binary_search/#aspose.cells.validation) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import CellArea, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.LIST
validation.formula1 = "a,b,c,d"

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
