---
title: get_precedents_in_calculation yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 190
url: /tr/aspose.cells/cell/get_precedents_in_calculation/
is_root: false
---
##  get_precedents_in_calculation(self) {#}
Bu hücrenin formülü hesaplanırken kullanılan tüm emsalleri (geçerli çalışma kitabındaki hücrelere yapılan referanslar) alır.


###  İadeler

Tüm referansları numaralandırmak için Sayım Aracı (Referans Alanı)


```python

def get_precedents_in_calculation(self):
    ...
```


###  Notlar

Bu yöntem yalnızca [`FormulaSettings.enable_calculation_chain`](/cells/python-net/tr/aspose.cells/formulasettings#enable_calculation_chain) numaralı telefonla çalışabilmektedir.
çalışma kitabı için doğrudur ve çalışma kitabı tamamen hesaplanmıştır.
Eğer bu hücre bir formül değilse veya başka herhangi bir hücreye referans vermiyorsa null döndürülür.
###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
workbook.settings.formula_settings.enable_calculation_chain = True
workbook.calculate_formula()
en = cells.get("A2").get_precedents_in_calculation()
print("A2's calculation precedents:")
for r in en:
    print(r)

```



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
