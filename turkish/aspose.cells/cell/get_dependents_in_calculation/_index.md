---
title: get_dependents_in_calculation yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 100
url: /tr/aspose.cells/cell/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation(self, recursive) {#bool}
Hesaplanan sonucu bu hücreye bağlı olan tüm hücreleri alır.


###  İadeler

Tüm bağımlıları (Cell nesne) numaralandıran Sayıcı


```python

def get_dependents_in_calculation(self, recursive):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| recursive | bool | Bu hücreye doğrudan başvurmayan bağımlıları döndürür mü?<br/> ancak bu hücrenin diğer yapraklarına referans|
###  Notlar

Bu yöntemi kullanmak için lütfen çalışma kitabının doğru değerle ayarlandığından emin olun.
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/tr/aspose.cells/formulasettings#enable_calculation_chain) ve bu ayar ile tamamen hesaplanmıştır.
Bu hücreye ait bir formül referansı yoksa null döndürülür.
###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
workbook.settings.formula_settings.enable_calculation_chain = True
workbook.calculate_formula()
en = cells.get("B1").get_dependents_in_calculation(False)
print("B1's calculation dependents:")
for c in en:
    print(c.name)
en = cells.get("B2").get_dependents_in_calculation(False)
print("B2's calculation dependents:")
for c in en:
    print(c.name)

```



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
