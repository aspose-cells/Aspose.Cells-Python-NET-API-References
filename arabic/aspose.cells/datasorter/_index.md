---
title: DataSorter الدرجة
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 420
url: /ar/aspose.cells/datasorter/
is_root: false
---
##  DataSorter الدرجة
وصف موجز لـ DataSorter.



يكشف نوع DataSorter الأعضاء التالية:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [keys](/cells/python-net/ar/aspose.cells/datasorter/keys) | يحصل على القائمة الرئيسية لفرز البيانات.|
| [has_headers](/cells/python-net/ar/aspose.cells/datasorter/has_headers) | يمثل ما إذا كان النطاق يحتوي على رؤوس.|
| [key1](/cells/python-net/ar/aspose.cells/datasorter/key1) | يمثل فهرس العمود الذي تم فرزه أولاً (الموضع المطلق ، العمود A هو 0 ، B هو 1 ، ...).|
| [order1](/cells/python-net/ar/aspose.cells/datasorter/order1) | يمثل ترتيب الفرز للمفتاح الأول.|
| [key2](/cells/python-net/ar/aspose.cells/datasorter/key2) | يمثل فهرس العمود الثاني المصنف (الموضع المطلق ، العمود A هو 0 ، B هو 1 ، ...).|
| [order2](/cells/python-net/ar/aspose.cells/datasorter/order2) | يمثل ترتيب الفرز للمفتاح الثاني.|
| [key3](/cells/python-net/ar/aspose.cells/datasorter/key3) | يمثل فهرس العمود الثالث المصنف (الموضع المطلق ، العمود A هو 0 ، B هو 1 ، ...).|
| [order3](/cells/python-net/ar/aspose.cells/datasorter/order3) | يمثل ترتيب الفرز للمفتاح الثالث.|
| [sort_left_to_right](/cells/python-net/ar/aspose.cells/datasorter/sort_left_to_right) | صحيح يعني أن اتجاه الفرز يكون من اليسار إلى اليمين.<br/>خطأ يعني أن اتجاه الفرز من أعلى إلى أسفل.<br/> القيمة الافتراضية هي كاذبة.|
| [case_sensitive](/cells/python-net/ar/aspose.cells/datasorter/case_sensitive) | الحصول على وتحديد ما إذا كانت حساسة لحالة الأحرف عند مقارنة السلسلة.|
| [sort_as_number](/cells/python-net/ar/aspose.cells/datasorter/sort_as_number) | يشير إلى ما إذا كان يتم فرز أي شيء يشبه الرقم.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [add_key(key, order)](/cells/python-net/ar/aspose.cells/datasorter/add_key/#int-SortOrder) | يضيف فهرس العمود المرتب وترتيب الفرز.|
| [add_key(key, order, custom_list)](/cells/python-net/ar/aspose.cells/datasorter/add_key/#int-SortOrder-str) | يضيف فهرس العمود المرتب وترتيب الفرز مع قائمة الفرز المخصصة.|
| [add_key(key, type, order, custom_list)](/cells/python-net/ar/aspose.cells/datasorter/add_key/#int-SortOnType-SortOrder-any) | يضيف فهرس العمود المرتب وترتيب الفرز مع قائمة الفرز المخصصة.|
| [add_key(key, order, custom_list)](/cells/python-net/ar/aspose.cells/datasorter/add_key/#int-SortOrder-list) | يضيف فهرس العمود المرتب وترتيب الفرز مع قائمة الفرز المخصصة.|
| [sort(cells, start_row, start_column, end_row, end_column)](/cells/python-net/ar/aspose.cells/datasorter/sort/#Cells-int-int-int-int) | يفرز بيانات المنطقة.|
| [sort(cells, area)](/cells/python-net/ar/aspose.cells/datasorter/sort/#Cells-CellArea) | فرز بيانات المنطقة.|
| [sort()](/cells/python-net/ar/aspose.cells/datasorter/sort/#) | فرز البيانات في النطاق.|
| [clear()](/cells/python-net/ar/aspose.cells/datasorter/clear/#) | امسح كل الإعدادات.|



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
* وحدة [aspose.cells](..)
