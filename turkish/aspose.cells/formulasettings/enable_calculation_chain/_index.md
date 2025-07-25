---
title: enable_calculation_chain mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 70
url: /tr/aspose.cells/formulasettings/enable_calculation_chain/
is_root: false
---
##  enable_calculation_chain mülk

Formüller için hesaplama zinciri etkinleştirilsin mi? Varsayılan değer false'tur.

###  Notlar

Çalışma kitabında çok sayıda formül olduğunda ve kullanıcının bunları tekrar tekrar hesaplaması gerektiğinde
Bunlardan sadece küçük bir kısmını değiştirerek hesaplama zincirini etkinleştirmek performans açısından faydalı olabilir.
Öte yandan, zincir etkinleştirilirse, zincir modelinin sürdürülmesi ekstra bellek gerektirir,
ve ayrıca hücre değerini veya formülleri değiştirmek gibi bazı diğer işlemler için biraz daha fazla CPU zamanı gerektirir.
Bu özelliği false'dan true'ya değiştirdikten sonra, hesaplama zinciri analiz edilecek ve oluşturulacaktır
çalışma kitabı için ilk hesaplama anında, yani ilk hesaplama için gereken süre
zincir olmadan normal hesaplamadan daha fazla olabilir.
###  Tanım:
```python
@property
def enable_calculation_chain(self):
    ...
@enable_calculation_chain.setter
def enable_calculation_chain(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`FormulaSettings`](/cells/python-net/tr/aspose.cells/formulasettings)
