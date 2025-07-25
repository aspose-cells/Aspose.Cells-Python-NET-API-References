---
title: طريقة import_xml
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 230
url: /ar/aspose.cells/workbook/import_xml/
is_root: false
---
##  import_xml(self, url, sheet_name, row, col) {#str-str-int-int}
استيراد/تحديث ملف بيانات XML إلى المصنف.



```python

def import_xml(self, url, sheet_name, row, col):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| url | str | عنوان URL/مسار ملف XML.|
| sheet_name | str | اسم ورقة الوجهة.|
| row | int | صف الوجهة|
| col | int | عمود الوجهة|

###  مثال

يقوم الكود التالي باستيراد بيانات XML إلى ورقة العمل 'Sheet 1' في Cell A1.

```python
from aspose.cells import Workbook

wb = Workbook("Book1.xlsx")
wb.import_xml("xml.xml", "Sheet1", 0, 0)
wb.save("output.xlsx")

```


##  import_xml(self, stream, sheet_name, row, col) {#io.RawIOBase-str-int-int}
استيراد/تحديث ملف بيانات XML إلى المصنف.



```python

def import_xml(self, stream, sheet_name, row, col):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| stream | io.RawIOBase | تدفق ملف XML.|
| sheet_name | str | اسم ورقة الوجهة.|
| row | int | صف الوجهة.|
| col | int | عمود الوجهة.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
