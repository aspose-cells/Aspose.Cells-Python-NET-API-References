---
title: is_param_array_mode_required mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 40
url: /tr/aspose.cells/abstractcalculationengine/is_param_array_mode_required/
is_root: false
---
##  is_param_array_mode_required mülk

Bu motorun dizi modunda hesaplanması için parametreye ihtiyacı olup olmadığını gösterir. Varsayılan değer false'tur.
Özel hesaplama yaparken [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/tr/aspose.cells/calculationdata/get_param_value_in_array_mode) gerekiyorsa
işlevler ve kullanıcı bunların tanımını güncellemedi
([`Workbook.update_custom_function_definition`](/cells/python-net/tr/aspose.cells/workbook/update_custom_function_definition) tarafından),
bu özelliğin true olarak ayarlanması gerekiyor.

###  Notlar

Bu özel hesaplama motorunun parametrenin dizi modunda hesaplanmasına ihtiyacı varsa,
Ağacı parametreler için önbelleğe almak için daha fazla yığın gerekli olacaktır
ve Calculate() yöntemi, parametrenin değerini hesaplamak için yinelemeli olarak çağrılabilir.
Performans değerlendirmesi için lütfen bu özelliği varsayılan değer olarak koruyun (yanlış)
özel bir gereklilik yoksa.
###  Tanım:
```python
@property
def is_param_array_mode_required(self):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`AbstractCalculationEngine`](/cells/python-net/tr/aspose.cells/abstractcalculationengine)
