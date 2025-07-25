---
title: get_dependents_in_calculation yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 400
url: /tr/aspose.cells/cells/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation(self, row, column, recursive) {#int-int-bool}
Hesaplanan sonucu belirli bir hücreye bağlı olan tüm hücreleri alır.


###  İadeler

Tüm bağımlıları (Cell nesne) numaralandıran Sayıcı


```python

def get_dependents_in_calculation(self, row, column, recursive):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row | int | Belirli hücrenin satır dizini|
| column | int |Belirli hücrenin sütun indeksi.|
| recursive | bool | Belirli hücreye doğrudan referans vermeyen bağımlıları döndürür mü?<br/> ama o hücrenin diğer yapraklarına atıf.|
###  Notlar

Bu yöntemi kullanmak için lütfen çalışma kitabının doğru değerle ayarlandığından emin olun.
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/tr/aspose.cells/formulasettings#enable_calculation_chain) ve bu ayar ile tamamen hesaplanmıştır.
Bu hücreye ait bir formül referansı yoksa null döndürülür.
Daha fazla ayrıntı ve örnek için lütfen [`Cell.get_dependents_in_calculation`](/cells/python-net/tr/aspose.cells/cell/get_dependents_in_calculation)'e bakın


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cells`](/cells/python-net/tr/aspose.cells/cells)
