---
title: ColumnCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 280
url: /tr/aspose.cells/columncollection/
is_root: false
---
##  ColumnCollection sınıfı
Bir çalışma sayfasındaki ayrı ayrı sütunları (ayarları) temsil eden [`Column`](/cells/python-net/tr/aspose.cells/column) nesnelerinin toplanması.
Column nesnesi yalnızca sütun genişliği, stiller vb. ayarları temsil eder. tüm sütun için,
karşılık gelen sütunda boş olmayan hücrelerin (verilerin) bulunması veya olmamasıyla hiçbir ilgisi yoktur.
Ve bu koleksiyonun "Count"u yalnızca bu koleksiyonda başlatılan count Column nesnelerini temsil eder,
çalışma sayfasında boş olmayan hücrelerin (verilerin) bulunup bulunmadığıyla hiçbir ilgisi yoktur.



ColumnCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/columncollection/capacity) | Dizi listesinin içerebileceği öğe sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [copy_to](/cells/python-net/tr/aspose.cells/columncollection/copy_to/#list) | Hedef dizi listesinin başından başlayarak dizi listesinin tamamını uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [copy_to](/cells/python-net/tr/aspose.cells/columncollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen dizininden başlayarak, dizi listesinden bir dizi öğeyi uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [index_of](/cells/python-net/tr/aspose.cells/columncollection/index_of/#aspose.cells.Column-int) | Belirtilen nesneyi arar ve belirtilen dizinden son öğeye kadar uzanan dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [index_of](/cells/python-net/tr/aspose.cells/columncollection/index_of/#aspose.cells.Column-int-int) |Belirtilen nesneyi arar ve belirtilen dizinde başlayan ve belirtilen sayıda öğeyi içeren dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/columncollection/last_index_of/#aspose.cells.Column) | Belirtilen nesneyi arar ve dizi listesinin tamamındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/columncollection/last_index_of/#aspose.cells.Column-int) | Belirtilen nesneyi arar ve ilk öğeden belirtilen dizine kadar uzanan dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/columncollection/last_index_of/#aspose.cells.Column-int-int) | Belirtilen nesneyi arar ve belirtilen sayıda öğeyi içeren ve belirtilen dizinde biten dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [get_by_index](/cells/python-net/tr/aspose.cells/columncollection/get_by_index/#int) | Sütun nesnesini dizine göre alır.|
| [get_column_by_index](/cells/python-net/tr/aspose.cells/columncollection/get_column_by_index/#int) | Listedeki konuma göre [`Column`](/cells/python-net/tr/aspose.cells/column) nesnesini alır.|
| [binary_search](/cells/python-net/tr/aspose.cells/columncollection/binary_search/#aspose.cells.Column) | Varsayılan karşılaştırıcıyı kullanarak bir öğe için sıralanmış dizi listesinin tamamını arar ve öğenin sıfır tabanlı dizinini döndürür.|



###  Örnek

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Add new Style to Workbook
style = workbook.create_style()
# Setting the background color to Blue
style.foreground_color = Color.blue
# setting Background Pattern
style.pattern = BackgroundType.SOLID
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Change the default width of first ten columns
for i in range(10):
    worksheet.cells.columns[i].width = 20.0
# Get the Column with non default formatting
columns = worksheet.cells.columns
for column in columns:
    # Apply Style to first ten Columns
    column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`Column`](/cells/python-net/tr/aspose.cells/column)
