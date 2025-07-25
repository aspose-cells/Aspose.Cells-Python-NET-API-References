---
title: number_category_type mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 700
url: /tr/aspose.cells/cell/number_category_type/
is_root: false
---
##  number_category_type mülk

Bu hücrenin sayı biçimlendirmesinin kategori türünü temsil eder.

###  Notlar

Hücrenin biçimlendirme deseni koşullu biçimlendirme desenleriyle birleştirildiğinde,
o zaman döndürülen tip, bu hücrenin geçerli değeri için kullanılan parçaya karşılık gelir.
Örneğin, bu hücrenin biçimlendirme deseni "#,##0;(#,##0);"-";@" ise,
hücrenin değeri sayısal olduğunda ve 0 olmadığında, döndürülen tür [`NumberCategoryType.NUMBER`](/cells/python-net/tr/aspose.cells/numbercategorytype#NUMBER)'dir;
Hücrenin değeri 0 veya sayısal değer olmadığında döndürülen tür [`NumberCategoryType.TEXT`](/cells/python-net/tr/aspose.cells/numbercategorytype#TEXT)'dir.
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
