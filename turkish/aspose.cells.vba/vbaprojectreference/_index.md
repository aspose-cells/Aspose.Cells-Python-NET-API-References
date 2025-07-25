---
title: VbaProjectReference sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 40
url: /tr/aspose.cells.vba/vbaprojectreference/
is_root: false
---
##  VbaProjectReference sınıfı
VBA projesinin referansını temsil eder.



VbaProjectReference türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [type](/cells/python-net/tr/aspose.cells.vba/vbaprojectreference/type) |Bu referansın türünü alır.|
| [name](/cells/python-net/tr/aspose.cells.vba/vbaprojectreference/name) | Referansın adını alır ve ayarlar.|
| [libid](/cells/python-net/tr/aspose.cells.vba/vbaprojectreference/libid) | Referansın Libid'ini alır ve ayarlar.|
| [twiddledlibid](/cells/python-net/tr/aspose.cells.vba/vbaprojectreference/twiddledlibid) | Referansın çevrilmiş Libid'ini alır ve ayarlar.|
| [extended_libid](/cells/python-net/tr/aspose.cells.vba/vbaprojectreference/extended_libid) | Referansın genişletilmiş Libid'ini alır ve ayarlar.|
| [relative_libid](/cells/python-net/tr/aspose.cells.vba/vbaprojectreference/relative_libid) | Başvurulan VBA projesinin tanımlayıcısını göreceli bir yol ile alır ve ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/tr/aspose.cells.vba/vbaprojectreference/copy/#aspose.cells.vba.vbaprojectreference) |  |



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add vba project reference
vbaProject.references.add_registered_reference("stdole", "*\\G{00020430-0000-0000-C000-000000000046}#2.0#0#C:\\Windows\\system32\\stdole2.tlb#OLE Automation")
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Ayrıca bakınız
* modül [`aspose.cells.vba`](..)
