---
title: ValidationCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1620
url: /tr/aspose.cells/validationcollection/
is_root: false
---
##  ValidationCollection sınıfı
Veri doğrulama koleksiyonunu temsil eder.



ValidationCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/validationcollection/capacity) | Dizi listesinin içerebileceği öğe sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add](/cells/python-net/tr/aspose.cells/validationcollection/add/#) | Koleksiyona bir veri doğrulaması ekler.|
| [add](/cells/python-net/tr/aspose.cells/validationcollection/add/#aspose.cells.CellArea) | Koleksiyona bir veri doğrulaması ekler.|
| [copy_to](/cells/python-net/tr/aspose.cells/validationcollection/copy_to/#list) | Hedef dizi listesinin başından başlayarak dizi listesinin tamamını uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [copy_to](/cells/python-net/tr/aspose.cells/validationcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen dizininden başlayarak, dizi listesinden bir dizi öğeyi uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [index_of](/cells/python-net/tr/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int) | Belirtilen nesneyi arar ve belirtilen dizinden son öğeye kadar uzanan dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [index_of](/cells/python-net/tr/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int-int) |Belirtilen nesneyi arar ve belirtilen dizinde başlayan ve belirtilen sayıda öğeyi içeren dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation) | Belirtilen nesneyi arar ve dizi listesinin tamamındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int) | Belirtilen nesneyi arar ve ilk öğeden belirtilen dizine kadar uzanan dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int-int) | Belirtilen nesneyi arar ve belirtilen sayıda öğeyi içeren ve belirtilen dizinde biten dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [remove_a_cell](/cells/python-net/tr/aspose.cells/validationcollection/remove_a_cell/#int-int) | Hücredeki tüm doğrulama ayarlarını kaldırır.|
| [remove_area](/cells/python-net/tr/aspose.cells/validationcollection/remove_area/#aspose.cells.CellArea) | Aralıktaki tüm doğrulama ayarlarını kaldırır.|
| [get_validation_in_cell](/cells/python-net/tr/aspose.cells/validationcollection/get_validation_in_cell/#int-int) | Verilen hücreye uygulanan doğrulamayı alır.|
| [binary_search](/cells/python-net/tr/aspose.cells/validationcollection/binary_search/#aspose.cells.Validation) | Varsayılan karşılaştırıcıyı kullanarak bir öğe için sıralanmış dizi listesinin tamamını arar ve öğenin sıfır tabanlı dizinini döndürür.|



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
