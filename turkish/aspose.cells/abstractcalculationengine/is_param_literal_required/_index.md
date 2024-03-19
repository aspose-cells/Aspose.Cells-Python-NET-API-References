---
title: is_param_literal_required mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 50
url: /tr/aspose.cells/abstractcalculationengine/is_param_literal_required/
is_root: false
---
##  is_param_literal_required mülk

Bu motorun hesaplama yaparken parametrenin tam metnine ihtiyacı olup olmadığını gösterir. Varsayılan değer false'tur.

###  Notlar

Bu özel hesaplama motorunun parametrenin gerçek metnine ihtiyacı varsa,
Parametrelerin gerçek metnini önbelleğe almak için daha fazla yığın gerekli olacaktır
ve Calculate() yöntemi, parametrenin değerini hesaplamak için yinelemeli olarak çağrılabilir.
Genellikle formüllerin hesaplanması için gerçek metne ihtiyaç duyulmaz
ve çoğu uygulamanın daha iyi performans elde etmesi için bu özelliğin false olarak tutulması gerekir.
###  Tanım:
```python
@property
def is_param_literal_required(self):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`AbstractCalculationEngine`](/cells/python-net/tr/aspose.cells/abstractcalculationengine)
