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
Belirtilen veri serisi için tüm [`Trendline`](/cells/python-net/tr/aspose.cells.charts/trendline) nesnelerinin bir koleksiyonunu temsil eder.



TrendlineCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/capacity) | Dizi listesinin içerebileceği öğe sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.TrendlineType) | Bu koleksiyona belirtilen türde bir [`Trendline`](/cells/python-net/tr/aspose.cells.charts/trendline) nesnesi ekler.|
| [add](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.TrendlineType-str) | Bu koleksiyona belirtilen tür ve adla bir [`Trendline`](/cells/python-net/tr/aspose.cells.charts/trendline) nesnesi ekler.|
| [copy_to](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/copy_to/#list) | Hedef dizi listesinin başından başlayarak dizi listesinin tamamını uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [copy_to](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen dizininden başlayarak, dizi listesinden bir dizi öğeyi uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [index_of](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.Trendline-int) | Belirtilen nesneyi arar ve belirtilen dizinden son öğeye kadar uzanan dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [index_of](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.Trendline-int-int) |Belirtilen nesneyi arar ve belirtilen dizinde başlayan ve belirtilen sayıda öğeyi içeren dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline) | Belirtilen nesneyi arar ve dizi listesinin tamamındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline-int) | Belirtilen nesneyi arar ve ilk öğeden belirtilen dizine kadar uzanan dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline-int-int) | Belirtilen nesneyi arar ve belirtilen sayıda öğeyi içeren ve belirtilen dizinde biten dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [binary_search](/cells/python-net/tr/aspose.cells.charts/trendlinecollection/binary_search/#aspose.cells.charts.Trendline) | Varsayılan karşılaştırıcıyı kullanarak bir öğe için sıralanmış dizi listesinin tamamını arar ve öğenin sıfır tabanlı dizinini döndürür.|



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
