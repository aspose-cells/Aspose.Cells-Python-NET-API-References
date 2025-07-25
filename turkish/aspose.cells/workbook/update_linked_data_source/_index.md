---
title: update_linked_data_source yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 440
url: /tr/aspose.cells/workbook/update_linked_data_source/
is_root: false
---
##  update_linked_data_source(self, external_workbooks) {#list}
Bu çalışma kitabı başka veri kaynaklarına yönelik harici bağlantılar içeriyorsa,
Aspose.Cells verilen kaynaklardan en son verileri almaya çalışacaktır.



```python

def update_linked_data_source(self, external_workbooks):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| external_workbooks | list | Bu çalışma kitabı tarafından başvurulan harici bağlantıların verilerini güncellemek için kullanılacak çalışma kitapları.<br/>Bu çalışma kitaplarının dış bağlantılarla eşleşmesi [`Workbook.file_name`](/cells/python-net/tr/aspose.cells/workbook#file_name) ile belirlenir.<br/>ve [`ExternalLink.data_source`](/cells/python-net/tr/aspose.cells/externallink#data_source). Lütfen [`Workbook.file_name`](/cells/python-net/tr/aspose.cells/workbook#file_name)'in<br/> Her çalışma kitabı için uygun değer belirtildi, böylece bunlar ilgili harici bağlantıya bağlanabilir.|
###  Notlar

Bir çalışma kitabı için ilgili dış bağlantı bulunamazsa, bu çalışma kitabı yok sayılacaktır.
Bu nedenle, daha sonra, yoksayılan çalışma kitabı yapmak istediğiniz yeni bir harici bağlantı içeren bir formül ayarladığınızda
buna bağlanılabilmesi için, bu metodu bu çalışma kitaplarıyla tekrar çağırana kadar bağlantı gerçekleştirilemez.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
