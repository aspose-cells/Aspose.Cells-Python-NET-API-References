---
title: get_dependents_in_calculation yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 370
url: /tr/aspose.cells/cells/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation {#int-int-bool}
Hesaplanan sonucu belirli bir hücreye bağlı olan tüm hücreleri alır.


###  İadeler

Tüm bağımlıları numaralandırmak için Numaralandırıcı (Cell nesneler)


```python
def get_dependents_in_calculation(self, row, column, recursive):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row | int | Belirli bir hücrenin satır dizini|
| column | int | Belirli bir hücrenin sütun dizini.|
| recursive | bool | Belirli bir hücreye doğrudan başvuruda bulunmayan bağımlıları döndürüp döndürmediği<br/> ancak o hücrenin diğer yapraklarına atıfta bulunulmaktadır.|
###  Notlar

Bu yöntemi kullanmak için lütfen çalışma kitabının gerçek değere ayarlandığından emin olun.
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/tr/aspose.cells/formulasettings#enable_calculation_chain) ve tamamen bu ayarla hesaplanmıştır.
Bu hücreye formül referansı yoksa null değeri döndürülür.
Daha fazla ayrıntı ve örnek için lütfen [`Cell.get_dependents_in_calculation`](/cells/python-net/tr/aspose.cells/cell/get_dependents_in_calculation)'e bakın.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cells`](/cells/python-net/tr/aspose.cells/cells)
