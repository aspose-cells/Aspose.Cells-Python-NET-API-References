---
title: cell mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 70
url: /tr/aspose.cells/calculationdata/cell/
is_root: false
---
##  cell mülk

Fonksiyonun bulunduğu Cell nesnesini alır.

###  Notlar

Bir formülü cell'e ayarlamadan hesaplarken,
[`Worksheet.calculate_formula`](/cells/python-net/tr/aspose.cells/worksheet/calculate_formula) gibi,
formül tıpkı cell A1 olarak ayarlandığı gibi hesaplanacaktır,
yani hem [`CalculationData.cell_row`](/cells/python-net/tr/aspose.cells/calculationdata#cell_row) hem de [`CalculationData.cell_column`](/cells/python-net/tr/aspose.cells/calculationdata#cell_column) 0'dır.
Ancak çalışma sayfasındaki cell A1 örneği oluşturulmamış olabilir.
Yani böyle bir durum için bu özellik null olacaktır.
###  Tanım:
```python
@property
def cell(self):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CalculationData`](/cells/python-net/tr/aspose.cells/calculationdata)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
