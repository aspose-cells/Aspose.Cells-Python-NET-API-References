---
title: طريقة export_xml
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 150
url: /ar/aspose.cells/workbook/export_xml/
is_root: false
---
##  export_xml(self, map_name, path) {#str-str}
تصدير بيانات XML المرتبطة بخريطة XML المحددة.



```python

def export_xml(self, map_name, path):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| map_name | str | اسم خريطة XML التي تحتاج إلى تصديرها|
| path | str | مسار التصدير|

###  مثال

قام الكود التالي بتصدير البيانات المرتبطة بـ XmlMap الأول.

```python
from aspose.cells import Workbook

wb = Workbook("Book1.xlsx")
# Make sure that the source xlsx file contains a XmlMap.
xmlMap = wb.worksheets.xml_maps[0]
wb.export_xml(xmlMap.name, "output.xml")

```


##  export_xml(self, map_name, stream) {#str-io.RawIOBase}
تصدير بيانات XML.



```python

def export_xml(self, map_name, stream):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| map_name | str | اسم خريطة XML التي تحتاج إلى تصديرها|
| stream | io.RawIOBase | تيار التصدير|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
