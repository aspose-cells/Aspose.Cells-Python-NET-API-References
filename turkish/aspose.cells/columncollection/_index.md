---
title: ColumnCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 250
url: /tr/aspose.cells/columncollection/
is_root: false
---
##  ColumnCollection sınıfı
Bir çalışma sayfasındaki bireysel sütun(ayar)ları temsil eden [`Column`](/cells/python-net/tr/aspose.cells/column) nesnelerinin koleksiyonu.
Sütun nesnesi yalnızca tüm sütun için sütun genişliği, stiller vb. gibi ayarları temsil eder.
boş olmayan hücrelerin(verilerin) olması veya ilgili sütunda bulunmamasıyla hiçbir ilgisi yoktur.
Ve bu koleksiyonun "Sayısı" yalnızca bu koleksiyonda örneklenen Sütun nesnelerinin sayısını temsil eder.
Çalışma sayfasında boş hücre(veri) olmamasıyla hiçbir ilgisi yoktur.



ColumnCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/columncollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells/columncollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells/columncollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/columncollection/index_of/#aspose.cells.column-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/columncollection/index_of/#aspose.cells.column-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells/columncollection/last_index_of/#aspose.cells.column) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`get_by_index(self, index)`](/cells/python-net/tr/aspose.cells/columncollection/get_by_index/#int) | İndeks ile sütun nesnesini alır.|
| [`get_column_by_index(self, index)`](/cells/python-net/tr/aspose.cells/columncollection/get_column_by_index/#int) | Listedeki konumuna göre [`Column`](/cells/python-net/tr/aspose.cells/column) nesnesini alır.|
| [`get(self, column_index)`](/cells/python-net/tr/aspose.cells/columncollection/get/#int) | API for Python Via .Net'i ekleyin.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells/columncollection/binary_search/#aspose.cells.column) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



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
