---
title: calculation_mode mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 60
url: /tr/aspose.cells/formulasettings/calculation_mode/
is_root: false
---
##  calculation_mode mülk

Ms Excel'de çalışma kitabı hesaplama modunu alır veya ayarlar.

###  Notlar

Bu özellik yalnızca ayarların sonuç elektronik tablosu dosyasına kaydedilmesi içindir
Böylece diğer uygulamalar (örneğin ms excel) ortaya çıkan dosyayı yüklerken ve düzenlerken buna göre hareket edebilir.
Çoğu kullanıcının uygulaması için performans değerlendirmesi amacıyla, çalışma kitabındaki hiçbir formülü otomatik olarak hesaplamıyoruz.
Bu özellik için hangi mod ayarlanmış olursa olsun.
Kullanıcının formülleri hesaplaması gerekiyorsa, lütfen gereksinime göre farklı nesneler üzerindeki yöntemleri her zaman çağırın:
[`Workbook.calculate_formula`](/cells/python-net/aspose.cells/workbook/calculate_formula), [`Worksheet.calculate_formula`](/cells/python-net/aspose.cells/worksheet/calculate_formula),
[`Cell.calculate`](/cells/python-net/tr/aspose.cells/cell/calculate), ...vb.
###  Tanım:
```python
@property
def calculation_mode(self):
    ...
@calculation_mode.setter
def calculation_mode(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CalcModeType`](/cells/python-net/tr/aspose.cells/calcmodetype)
* sınıf [`FormulaSettings`](/cells/python-net/tr/aspose.cells/formulasettings)
