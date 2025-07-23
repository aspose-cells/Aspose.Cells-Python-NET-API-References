---
title: VbaProjectReference صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells.vba/vbaprojectreference/
is_root: false
---
##  VbaProjectReference صف
يمثل مرجع مشروع VBA.



يكشف النوع VbaProjectReference عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [type](/cells/python-net/ar/aspose.cells.vba/vbaprojectreference/type) |يحصل على نوع هذا المرجع.|
| [name](/cells/python-net/ar/aspose.cells.vba/vbaprojectreference/name) | يحصل على اسم المرجع ويحدده.|
| [libid](/cells/python-net/ar/aspose.cells.vba/vbaprojectreference/libid) | يحصل على Libid الخاص بالمرجع ويقوم بتعيينه.|
| [twiddledlibid](/cells/python-net/ar/aspose.cells.vba/vbaprojectreference/twiddledlibid) | يحصل على Libid المتغير للمرجع ويقوم بتعيينه.|
| [extended_libid](/cells/python-net/ar/aspose.cells.vba/vbaprojectreference/extended_libid) | يحصل على Libid الممتد للمرجع ويقوم بتعيينه.|
| [relative_libid](/cells/python-net/ar/aspose.cells.vba/vbaprojectreference/relative_libid) | يحصل على معرف مشروع VBA المشار إليه ويقوم بتعيينه باستخدام مسار نسبي.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/ar/aspose.cells.vba/vbaprojectreference/copy/#aspose.cells.vba.vbaprojectreference) |  |



###  مثال

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

###  أنظر أيضا
* الوحدة [`aspose.cells.vba`](..)
