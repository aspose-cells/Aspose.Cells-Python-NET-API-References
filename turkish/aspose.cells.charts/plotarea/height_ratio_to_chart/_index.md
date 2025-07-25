---
title: height_ratio_to_chart mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 200
url: /tr/aspose.cells.charts/plotarea/height_ratio_to_chart/
is_root: false
---
##  height_ratio_to_chart mülk

Grafik alanının oransal birimlerinde çizim alanı sınırlayıcı kutusunun yüksekliğini alır veya ayarlar.

###  Notlar

Çizim alanı sınırlayıcı kutusu, çizim alanını, onay işaretlerini (onay etiketleri) ve onay işaretlerinin etrafında küçük bir kenarlığı içerir.
 Eğer değer MS Excel tarafından oluşturulmamışsa lütfen bu metodu çağırmadan önce Chart.Calculate() metodunu çağırın.


**GrafikteXRakam** , **YOranıGrafik** , **GenişlikOranıGrafik** Ve**YükseklikOranıGrafik** ile ilgili**Arsa Alanı** arsa alanını temsil eder
 çizim alanını, işaret çizgilerini (işaret etiketleri) ve işaret çizgilerinin etrafında küçük bir kenarlığı içeren sınırlayıcı kutu.
 Arsa alanının gerçek boyutunu öğrenmek istiyorsanız, aramalısınız.**İçXOranıGrafik** , **İçYOranıGrafik** , **GrafikİçGenişlikOranı** Ve
**İçYükseklikOranıGrafik** özellikler.


Excel 2007 ve sonrası için varsayılan değer sıfırdır. Chart.Calculate() fonksiyonunu çağırdıktan sonra get the value fonksiyonunu çağırmalısınız.

 
YükseklikPiksel = GrafikYükseklikOranı * grafik.GrafikNesnesi.Genişlik.
###  Tanım:
```python
@property
def height_ratio_to_chart(self):
    ...
@height_ratio_to_chart.setter
def height_ratio_to_chart(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells.charts`](../../)
* sınıf [`PlotArea`](/cells/python-net/tr/aspose.cells.charts/plotarea)
