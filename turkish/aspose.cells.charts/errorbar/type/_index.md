---
title: type mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 270
url: /tr/aspose.cells.charts/errorbar/type/
is_root: false
---
##  type mülk

type hata çubuğu miktarını temsil eder.

###  Örnek

```python
from aspose.cells import Workbook
from aspose.cells.charts import ErrorBarType

wb = Workbook("chart.xlsx")
chart = wb.worksheets[0].charts[0]
aseries = chart.n_series[0]
# Sets custom error bar type
aseries.y_error_bar.type = ErrorBarType.CUSTOM
aseries.y_error_bar.plus_value = "=Sheet1!A1"
aseries.y_error_bar.minus_value = "=Sheet1!A2"

```
###  Tanım:
```python
@property
def type(self):
    ...
@type.setter
def type(self, value):
    ...
```

###  Ayrıca bakınız
* modül [aspose.cells.charts](../../)
* sınıf [ErrorBar](/cells/python-net/tr/aspose.cells.charts/errorbar)
* sınıf [ErrorBarType](/cells/python-net/tr/aspose.cells.charts/errorbartype)
