---
title: is_chart_data_changed yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 80
url: /tr/aspose.cells.charts/chart/is_chart_data_changed/
is_root: false
---
##  is_chart_data_changed(self) {#}
Bir grafiğin veri kaynağının değişip değişmediğini algılar.


###  İadeler

Grafik değiştiyse true, aksi takdirde false döndürür


```python

def is_chart_data_changed(self):
    ...
```


###  Notlar

Yöntem, grafiği görüntü formatına dönüştürmeden önce grafiğin veri kaynağındaki değişiklikleri algılar.
İlk Chart.toImage çağrısında, grafik kaynak verileri (örneğin XValuesParseData, ValuesParseData) kaydedilecektir.
Chart.toImage metodunu tekrar çağırmadan önce, Chart'ın yeniden işlenmesi gerekip gerekmediğini kontrol etmek için IsChartDataChanged metodunu çağırın.


###  Ayrıca bakınız
* modül [`aspose.cells.charts`](../../)
* sınıf [`Chart`](/cells/python-net/tr/aspose.cells.charts/chart)
