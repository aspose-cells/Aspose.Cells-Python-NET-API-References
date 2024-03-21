---
title: number_category_type mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 670
url: /tr/aspose.cells/cell/number_category_type/
is_root: false
---
##  number_category_type mülk

Bu hücrenin sayı biçimlendirmesinin kategori türünü temsil eder.

###  Notlar

Hücrenin biçimlendirme deseni koşullu biçimlendirme desenleriyle birleştirildiğinde,
bu durumda döndürülen tür, bu hücrenin geçerli değeri için kullanılan kısma karşılık gelir.
Örneğin, bu hücrenin biçimlendirme modeli "#,##0;(#,##0);"-";@" ise,
daha sonra hücrenin değeri 0 değil de sayısal olduğunda, döndürülen tür [`NumberCategoryType.NUMBER`](/cells/python-net/tr/aspose.cells/numbercategorytype#NUMBER) olur;
Hücrenin değeri 0 olduğunda veya sayısal bir değer olmadığında döndürülen tür [`NumberCategoryType.TEXT`](/cells/python-net/tr/aspose.cells/numbercategorytype#TEXT) olur.
###  Tanım:
```python
@property
def number_category_type(self):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
* sınıf [`NumberCategoryType`](/cells/python-net/tr/aspose.cells/numbercategorytype)
