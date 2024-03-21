---
title: طريقة import_custom_objects
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 630
url: /ar/aspose.cells/cells/import_custom_objects/
is_root: false
---
##  import_custom_objects {#list-int-int-aspose.cells.ImportTableOptions}
يستورد كائنات مخصصة.


###  عائدات

إجمالي عدد الصفوف المستوردة.


```python
def import_custom_objects(self, list, first_row, first_column, options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| list | list | الكائن المخصص|
| first_row | int | رقم الصف للخلية الأولى المراد الاستيراد فيها.|
| first_column | int | رقم عمود الخلية الأولى المراد الاستيراد فيها.|
| options | [`ImportTableOptions`](/cells/python-net/ar/aspose.cells/importtableoptions) | خيارات الاستيراد.|
###  ملاحظات

يجب أن تكون الكائنات المخصصة من نفس النوع.

##  import_custom_objects {#list-list-bool-int-int-int-bool-str-bool}

يستورد كائنات مخصصة.


###  عائدات

إجمالي عدد الصفوف المستوردة.


```python
def import_custom_objects(self, list, property_names, is_property_name_shown, first_row, first_column, row_number, insert_rows, date_format_string, convert_string_to_number):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| list | list | الكائن المخصص|
| property_names | list | أسماء الخصائص. إذا كانت فارغة، فسوف نقوم باستيراد جميع خصائص الكائن.|
| is_property_name_shown | bool | يشير إلى ما إذا كان سيتم استيراد اسم الخاصية إلى الصف الأول.|
| first_row | int | رقم الصف للخلية الأولى المراد الاستيراد فيها.|
| first_column | int | رقم عمود الخلية الأولى المراد الاستيراد فيها.|
| row_number | int | عدد الصفوف التي سيتم استيرادها.|
| insert_rows | bool | يشير إلى ما إذا كان سيتم إضافة صفوف إضافية لملاءمة البيانات.|
| date_format_string | str | سلسلة تنسيق التاريخ للخلايا.|
| convert_string_to_number | bool | يشير إلى ما إذا كانت هذه الطريقة ستحاول تحويل السلسلة إلى رقم.|
###  ملاحظات

يجب أن تكون الكائنات المخصصة من نفس النوع.


###  أنظر أيضا

* الوحدة [`aspose.cells`](../../)
* فئة [`Cells`](/cells/python-net/ar/aspose.cells/cells)
