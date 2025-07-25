---
title: DataSorter صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 410
url: /ar/aspose.cells/datasorter/
is_root: false
---
##  DataSorter صف
وصف موجز لـ DataSorter.



يكشف النوع DataSorter عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [keys](/cells/python-net/ar/aspose.cells/datasorter/keys) | يحصل على قائمة المفاتيح لفرز البيانات.|
| [has_headers](/cells/python-net/ar/aspose.cells/datasorter/has_headers) | يمثل ما إذا كان النطاق يحتوي على رؤوس.|
| [key1](/cells/python-net/ar/aspose.cells/datasorter/key1) | يمثل أول مؤشر للعمود المفرز (الموضع المطلق، العمود A هو 0، B هو 1، ...).|
| [order1](/cells/python-net/ar/aspose.cells/datasorter/order1) | يمثل ترتيب المفتاح الأول.|
| [key2](/cells/python-net/ar/aspose.cells/datasorter/key2) | يمثل مؤشر العمود المرتب الثاني (الموضع المطلق، العمود A هو 0، B هو 1، ...).|
| [order2](/cells/python-net/ar/aspose.cells/datasorter/order2) | يمثل ترتيب المفتاح الثاني.|
| [key3](/cells/python-net/ar/aspose.cells/datasorter/key3) | يمثل مؤشر العمود الثالث المرتب (الموضع المطلق، العمود A هو 0، B هو 1، ...).|
| [order3](/cells/python-net/ar/aspose.cells/datasorter/order3) | يمثل ترتيب المفتاح الثالث.|
| [sort_left_to_right](/cells/python-net/ar/aspose.cells/datasorter/sort_left_to_right) |صحيح يعني أن اتجاه الفرز من اليسار إلى اليمين.<br/>خطأ يعني أن اتجاه الفرز من الأعلى إلى الأسفل.<br/> القيمة الافتراضية هي false.|
| [case_sensitive](/cells/python-net/ar/aspose.cells/datasorter/case_sensitive) | يحصل على ويحدد ما إذا كان حساسًا لحالة الأحرف عند مقارنة السلسلة.|
| [sort_as_number](/cells/python-net/ar/aspose.cells/datasorter/sort_as_number) | يشير إلى ما إذا كان يتم فرز أي شيء يبدو وكأنه رقم.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add_key(self, key, order)`](/cells/python-net/ar/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder) | إضافة فهرس العمود المفرز وترتيب الفرز.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/ar/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-str) | إضافة فهرس العمود المفرز وترتيب الفرز باستخدام قائمة الفرز المخصصة.|
| [`add_key(self, key, type, order, custom_list)`](/cells/python-net/ar/aspose.cells/datasorter/add_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-any) | إضافة فهرس العمود المفرز وترتيب الفرز باستخدام قائمة الفرز المخصصة.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/ar/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-list) | إضافة فهرس العمود المفرز وترتيب الفرز باستخدام قائمة الفرز المخصصة.|
| [`sort(self, cells, start_row, start_column, end_row, end_column)`](/cells/python-net/ar/aspose.cells/datasorter/sort/#aspose.cells.cells-int-int-int-int) | فرز بيانات المنطقة.|
| [`sort(self, cells, area)`](/cells/python-net/ar/aspose.cells/datasorter/sort/#aspose.cells.cells-aspose.cells.cellarea) | فرز بيانات المنطقة.|
| [`sort(self)`](/cells/python-net/ar/aspose.cells/datasorter/sort/#) | فرز البيانات في النطاق.|
| [`clear(self)`](/cells/python-net/ar/aspose.cells/datasorter/clear/#) | مسح كافة الإعدادات.|
| [`add_color_key(self, key, type, order, color)`](/cells/python-net/ar/aspose.cells/datasorter/add_color_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-aspose.pydrawing.color) | إضافة مفتاح فرز الألوان.|



###  مثال

```python
from aspose.cells import CellArea, SortOrder, Workbook

# Instantiate a new Workbook object.
workbook = Workbook("Book1.xls")
# Get the workbook datasorter object.
sorter = workbook.data_sorter
# Set the first order for datasorter object.
sorter.order1 = SortOrder.DESCENDING
# Define the first key.
sorter.key1 = 0
# Set the second order for datasorter object.
sorter.order2 = SortOrder.ASCENDING
# Define the second key.
sorter.key2 = 1
# Create a cells area (range).
ca = CellArea()
# Specify the start row index.
ca.start_row = 0
# Specify the start column index.
ca.start_column = 0
# Specify the last row index.
ca.end_row = 13
# Specify the last column index.
ca.end_column = 1
# Sort data in the specified data range (A1:B14)
sorter.sort(workbook.worksheets[0].cells, ca)
# Save the excel file.
workbook.save("outBook.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
