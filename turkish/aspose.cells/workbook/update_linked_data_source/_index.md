---
title: update_linked_data_source yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 420
url: /tr/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source {#list}
Bu çalışma kitabı başka veri kaynaklarına harici bağlantılar içeriyorsa,
Aspose.Cells, verilen kaynaklardan en son verileri almaya çalışacak.



```python
def update_linked_data_source(self, external_workbooks):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| external_workbooks | list | Bu çalışma kitabının referans verdiği dış bağlantıların verilerini güncellemek için kullanılacak çalışma kitapları.<br/>Bu çalışma kitaplarının dış bağlantılarla eşleşmesi [`Workbook.file_name`](/cells/python-net/tr/aspose.cells/workbook#file_name) ile belirlenir.<br/>ve [`ExternalLink.data_source`](/cells/python-net/tr/aspose.cells/externallink#data_source). Lütfen [`Workbook.file_name`](/cells/python-net/tr/aspose.cells/workbook#file_name)'in olduğundan emin olun.<br/> karşılık gelen harici bağlantıya bağlanabilmeleri için her çalışma kitabı için uygun değerle belirtildi.|
###  Notlar

Bir çalışma kitabı için karşılık gelen harici bağlantı bulunamazsa bu çalışma kitabı yok sayılacaktır.
Dolayısıyla, daha sonra yeni bir harici bağlantı içeren bir formül ayarladığınızda, bu formülü göz ardı edilen çalışma kitabı haline getirmeyi planlıyorsunuz
bağlanacaksa, bu çalışma kitaplarıyla bu yöntemi tekrar çağırana kadar bağlantı gerçekleştirilemez.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
