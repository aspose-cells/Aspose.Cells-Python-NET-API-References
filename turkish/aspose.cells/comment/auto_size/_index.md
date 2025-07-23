---
title: auto_size mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 80
url: /tr/aspose.cells/comment/auto_size/
is_root: false
---
##  auto_size mülk

Yorumun boyutunun içeriğine göre otomatik olarak ayarlanıp ayarlanmadığını belirtir.
Not: Bazı özel durumlarda (Mac ortamı gibi) bu ayar etkili olmayabilir. Bu ayar etkili olmazsa, lütfen FitToTextSize() ile değiştirin.

###  Örnek

```python

if notcomment1.auto_size:
    # The size of the comment varies with the content
    comment1.auto_size = True

```
###  Tanım:
```python
@property
def auto_size(self):
    ...
@auto_size.setter
def auto_size(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Comment`](/cells/python-net/tr/aspose.cells/comment)
