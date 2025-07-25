---
title: SeriesCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 250
url: /tr/aspose.cells.charts/seriescollection/
is_root: false
---
##  SeriesCollection sınıfı
[`Series`](/cells/python-net/tr/aspose.cells.charts/series) nesneden oluşan bir koleksiyonu kapsüller.



SeriesCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [category_data](/cells/python-net/tr/aspose.cells.charts/seriescollection/category_data) | Kategori Eksen değerlerinin aralığını alır veya ayarlar.<br/> Bir hücre aralığı olabilir (örneğin, "d1:e10")<br/> veya bir değer dizisi (örneğin, "{2,6,8,10}").|
| [second_category_data](/cells/python-net/tr/aspose.cells.charts/seriescollection/second_category_data) | İkinci kategori Eksen değerlerinin aralığını alır veya ayarlar.<br/> Bir hücre aralığı olabilir (örneğin, "d1:e10")<br/> veya bir değer dizisi (örneğin, "{2,6,8,10}").<br/> Sadece bazı ASeries'lerin ikinci eksende çizilmesi durumunda etkilidir.|
| [is_color_varied](/cells/python-net/tr/aspose.cells.charts/seriescollection/is_color_varied) | Noktaların renginin değişip değişmediğini gösterir.|
| [capacity](/cells/python-net/tr/aspose.cells.charts/seriescollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, area, is_vertical)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/add/#str-bool) | [`Series`](/cells/python-net/tr/aspose.cells.charts/series) koleksiyonunu bir grafiğe ekler.|
| [`add(self, area, is_vertical, check_labels)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/add/#str-bool-bool) | [`Series`](/cells/python-net/tr/aspose.cells.charts/series) koleksiyonunu bir grafiğe ekler.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.series-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.series-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`get_series_by_order(self, order)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/get_series_by_order/#int) | [`Series`](/cells/python-net/tr/aspose.cells.charts/series) elemanını sıraya göre alır.|
| [`change_series_order(self, source_index, dest_index)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/change_series_order/#int-int) | İki serinin sırasını doğrudan değiştirir.|
| [`swap_series(self, source_index, dest_index)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/swap_series/#int-int) | İki serinin sırasını doğrudan değiştirir.|
| [`set_series_names(self, start_index, area, is_vertical)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/set_series_names/#int-str-bool) | Grafikteki tüm serilerin adını ayarlar.|
| [`add_r1c1(self, area, is_vertical)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/add_r1c1/#str-bool) | [`Series`](/cells/python-net/tr/aspose.cells.charts/series) koleksiyonunu bir grafiğe ekler.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.charts/seriescollection/binary_search/#aspose.cells.charts.series) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a sample value to "A4" cell
worksheet.cells.get("A4").put_value(200)
# Adding a sample value to "B1" cell
worksheet.cells.get("B1").put_value(60)
# Adding a sample value to "B2" cell
worksheet.cells.get("B2").put_value(32)
# Adding a sample value to "B3" cell
worksheet.cells.get("B3").put_value(50)
# Adding a sample value to "B4" cell
worksheet.cells.get("B4").put_value(40)
# Adding a sample value to "C1" cell as category data
worksheet.cells.get("C1").put_value("Q1")
# Adding a sample value to "C2" cell as category data
worksheet.cells.get("C2").put_value("Q2")
# Adding a sample value to "C3" cell as category data
worksheet.cells.get("C3").put_value("Y1")
# Adding a sample value to "C4" cell as category data
worksheet.cells.get("C4").put_value("Y2")
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.COLUMN, 5, 0, 15, 5)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B4"
chart.n_series.add("A1:B4", True)
# Setting the data source for the category data of NSeries
chart.n_series.category_data = "C1:C4"
# Saving the Excel file
workbook.save("book1.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells.charts`](..)
* sınıf [`Series`](/cells/python-net/tr/aspose.cells.charts/series)
