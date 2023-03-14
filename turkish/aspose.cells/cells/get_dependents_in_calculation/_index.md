---
title: get_dependents_in_calculation yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 390
url: /tr/aspose.cells/cells/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation(row, column, recursive) {#int-int-bool}
Hesaplanan sonucu belirli bir hücreye bağlı olan tüm hücreleri alır.


###  İadeler

Tüm bağımlıları numaralandırmak için numaralandırıcı(Cell nesneler)


```python
def get_dependents_in_calculation(self, row, column, recursive):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row | int | Belirli hücrenin satır dizini|
| column | int | Belirli hücrenin sütun dizini.|
| recursive | bool | Doğrudan belirli bir hücreye başvurmayan bağımlıları döndürüp döndürmediği<br/> ancak o hücrenin diğer yapraklarına referans.|
###  Notlar

Bu yöntemi kullanmak için lütfen çalışma kitabının şu değer için doğru değere ayarlandığından emin olun:
[FormulaSettings.enable_calculation_chain](/cells/python-net/tr/aspose.cells/formulasettings#enable_calculation_chain) ve tamamen bu ayarla hesaplanmıştır.
Bu hücreye herhangi bir formül başvurusu yoksa, null döndürülür.
Daha fazla detay ve örnek için lütfen [Cell.get_dependents_in_calculation(recursive)](/cells/python-net/tr/aspose.cells/cell/get_dependents_in_calculation)'e bakınız.


###  Ayrıca bakınız
* modül [aspose.cells](../../)
* sınıf [Cells](/cells/python-net/tr/aspose.cells/cells)
