---
title: ChartCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 60
url: /tr/aspose.cells.charts/chartcollection/
is_root: false
---
##  ChartCollection sınıfı
[`Chart`](/cells/python-net/tr/aspose.cells.charts/chart) nesneden oluşan bir koleksiyonu kapsüller.



ChartCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.charts/chartcollection/capacity) | Dizi listesinin içerebileceği öğe sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add](/cells/python-net/tr/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-int-int-int-int) | Koleksiyona bir grafik ekler.|
| [add](/cells/python-net/tr/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-str-int-int-int-int) | Koleksiyona bir grafik ekler.|
| [add](/cells/python-net/tr/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) | Önceden ayarlanmış şablona sahip bir grafik ekler.|
| [add](/cells/python-net/tr/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-str-bool-int-int-int-int) | Koleksiyona bir grafik ekler.|
| [get](/cells/python-net/tr/aspose.cells.charts/chartcollection/get/#int) | Bu[int index] desteklenmediğinden API for Python'i .Net. yoluyla ekleyin|
| [get](/cells/python-net/tr/aspose.cells.charts/chartcollection/get/#str) | Bu[string Chart] desteklenmediğinden .Net yoluyla API for Python ekleyin|
| [copy_to](/cells/python-net/tr/aspose.cells.charts/chartcollection/copy_to/#list) | Hedef dizi listesinin başından başlayarak dizi listesinin tamamını uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [copy_to](/cells/python-net/tr/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen dizininden başlayarak, dizi listesinden bir dizi öğeyi uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [index_of](/cells/python-net/tr/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.Chart-int) | Belirtilen nesneyi arar ve belirtilen dizinden son öğeye kadar uzanan dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [index_of](/cells/python-net/tr/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.Chart-int-int) |Belirtilen nesneyi arar ve belirtilen dizinde başlayan ve belirtilen sayıda öğeyi içeren dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart) | Belirtilen nesneyi arar ve dizi listesinin tamamındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart-int) | Belirtilen nesneyi arar ve ilk öğeden belirtilen dizine kadar uzanan dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart-int-int) | Belirtilen nesneyi arar ve belirtilen sayıda öğeyi içeren ve belirtilen dizinde biten dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [add_floating_chart](/cells/python-net/tr/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.ChartType-int-int-int-int) | Koleksiyona bir grafik ekler.|
| [binary_search](/cells/python-net/tr/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.Chart) | Varsayılan karşılaştırıcıyı kullanarak bir öğe için sıralanmış dizi listesinin tamamını arar ve öğenin sıfır tabanlı dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

###  Ayrıca bakınız
* modül [`aspose.cells.charts`](..)
* sınıf [`Chart`](/cells/python-net/tr/aspose.cells.charts/chart)
