---
title: linked_data_sources mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 60
url: /tr/aspose.cells/calculationoptions/linked_data_sources/
is_root: false
---
##  linked_data_sources mülk

Formüllerde kullanılan dış bağlantıların veri kaynaklarını belirtir.

###  Notlar

[`Workbook.update_linked_data_source`](/cells/python-net/tr/aspose.cells/workbook/update_linked_data_source) gibi burada belirtebilirsiniz
Hesaplanacak formüllerde kullanılan dış bağlantıların veri kaynakları, özellikle de
DOLAYLI işlevinde kullanılır. DOLAYLI işlevinde kullanılan harici bağlantılar için,
bunlar çalışma kitabının dış bağlantıları kapsamında ele alınmaz ve güncellenemez
[`Workbook.update_linked_data_source`](/cells/python-net/tr/aspose.cells/workbook/update_linked_data_source) tarafından.
Bu çalışma kitaplarının dış bağlantılarla eşleşmesi [`Workbook.file_name`](/cells/python-net/tr/aspose.cells/workbook#file_name) ile belirlenir.
ve [`ExternalLink.data_source`](/cells/python-net/tr/aspose.cells/externallink#data_source). Lütfen [`Workbook.file_name`](/cells/python-net/tr/aspose.cells/workbook#file_name)'in
Uygun değerle belirtilmiş olmalıdır (genellikle karşılık gelen değerle aynı olmalıdır)
Her çalışma kitabı için ([`ExternalLink.data_source`](/cells/python-net/tr/aspose.cells/externallink#data_source)) beklendiği gibi bağlanabilmeleri için.
###  Tanım:
```python
@property
def linked_data_sources(self):
    ...
@linked_data_sources.setter
def linked_data_sources(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions)
