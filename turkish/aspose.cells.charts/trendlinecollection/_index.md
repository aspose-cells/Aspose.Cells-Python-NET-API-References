---
title: TrendlineCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 350
url: /tr/aspose.cells.charts/trendlinecollection/
is_root: false
---
##  TrendlineCollection sınıfı
Belirtilen veri serisi için tüm [`Trendline`](/cells/python-net/tr/aspose.cells.charts/trendline) nesnenin bir koleksiyonunu temsil eder.



TrendlineCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, type)`](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.trendlinetype) | Bu koleksiyona belirtilen türde [`Trendline`](/cells/python-net/tr/aspose.cells.charts/trendline) nesnesini ekler.|
| [`add(self, type, name)`](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.trendlinetype-str) | Bu koleksiyona belirtilen tür ve adla [`Trendline`](/cells/python-net/tr/aspose.cells.charts/trendline) nesnesini ekler.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.trendline-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.trendline-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/binary_search/#aspose.cells.charts.trendline) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType, TrendlineType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
worksheet.cells.get("A1").put_value(50)
worksheet.cells.get("A2").put_value(100)
worksheet.cells.get("A3").put_value(150)
worksheet.cells.get("A4").put_value(200)
worksheet.cells.get("B1").put_value(60)
worksheet.cells.get("B2").put_value(32)
worksheet.cells.get("B3").put_value(50)
worksheet.cells.get("B4").put_value(40)
# Adding a chart to the worksheet
chartIndex = workbook.worksheets[0].charts.add(ChartType.COLUMN, 3, 3, 15, 10)
chart = workbook.worksheets[0].charts[chartIndex]
chart.n_series.add("A1:a3", True)
chart.n_series[0].trend_lines.add(TrendlineType.LINEAR, "MyTrendLine")
line = chart.n_series[0].trend_lines[0]
line.display_equation = True
line.display_r_squared = True
line.color = Color.red

```

###  Ayrıca bakınız
* modül [`aspose.cells.charts`](..)
* sınıf [`Trendline`](/cells/python-net/tr/aspose.cells.charts/trendline)
