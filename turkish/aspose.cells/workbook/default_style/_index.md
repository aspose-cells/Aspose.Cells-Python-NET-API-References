---
title: default_style mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 550
url: /tr/aspose.cells/workbook/default_style/
is_root: false
---
##  default_style mülk

Çalışma kitabının varsayılan [`Style`](/cells/python-net/tr/aspose.cells/style) nesnesini alır veya ayarlar.

###  Notlar

DefaultStyle özelliği, Çalışma Kitabının tamamı için bir Stil uygulamak açısından kullanışlıdır.

###  Örnek

Aşağıdaki kod yeni bir Çalışma Kitabı oluşturup başlatır ve buna varsayılan bir [`Style`](/cells/python-net/tr/aspose.cells/style) ayarlar.

```python
from aspose.cells import Workbook

workbook = Workbook()
defaultStyle = workbook.default_style
defaultStyle.font.name = "Tahoma"
workbook.default_style = defaultStyle

```
###  Tanım:
```python
@property
def default_style(self):
    ...
@default_style.setter
def default_style(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Style`](/cells/python-net/tr/aspose.cells/style)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
