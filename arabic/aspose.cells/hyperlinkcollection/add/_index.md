---
title: طريقة add
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/hyperlinkcollection/add/
is_root: false
---
##  add(self, cell_name, total_rows, total_columns, address) {#str-int-int-str}
يضيف ارتباطًا تشعبيًا إلى خلية محددة أو نطاق من الخلايا.


###  عائدات

[`Hyperlink`](/cells/python-net/ar/aspose.cells/hyperlink) فهرس الكائن.


```python

def add(self, cell_name, total_rows, total_columns, address):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| cell_name | str | Cell الاسم.|
| total_rows | int | عدد الصفوف في نطاق الارتباط التشعبي هذا.|
| total_columns | int |عدد الأعمدة في نطاق الارتباط التشعبي هذا.|
| address | str | عنوان الرابط التشعبي.|


##  add(self, first_row, first_column, total_rows, total_columns, address) {#int-int-int-int-str}
يضيف ارتباطًا تشعبيًا إلى خلية محددة أو نطاق من الخلايا.


###  عائدات

[`Hyperlink`](/cells/python-net/ar/aspose.cells/hyperlink) فهرس الكائن.


```python

def add(self, first_row, first_column, total_rows, total_columns, address):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| first_row | int | الصف الأول من نطاق الارتباط التشعبي.|
| first_column | int | العمود الأول من نطاق الارتباط التشعبي.|
| total_rows | int | عدد الصفوف في نطاق الارتباط التشعبي هذا.|
| total_columns | int |عدد الأعمدة في نطاق الارتباط التشعبي هذا.|
| address | str | عنوان الرابط التشعبي.|

###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
excel = Workbook()
worksheet = excel.worksheets[0]
worksheet.hyperlinks.add("A4", 1, 1, "http://www.aspose.com")
worksheet.hyperlinks.add("A5", 1, 1, "c:\\book1.xls")

```


##  add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip) {#str-str-str-str-str}
يضيف ارتباطًا تشعبيًا إلى خلية محددة أو نطاق من الخلايا.


###  عائدات

[`Hyperlink`](/cells/python-net/ar/aspose.cells/hyperlink) فهرس الكائن.


```python

def add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| start_cell_name | str |الخلية الموجودة في أعلى يسار النطاق.|
| end_cell_name | str | الخلية الموجودة في أسفل يمين النطاق.|
| address | str | عنوان الرابط التشعبي.|
| text_to_display | str | النص الذي سيتم عرضه للرابط التشعبي المحدد.|
| screen_tip | str | نص تلميح الشاشة للرابط التشعبي المحدد.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Hyperlink`](/cells/python-net/ar/aspose.cells/hyperlink)
* فئة [`HyperlinkCollection`](/cells/python-net/ar/aspose.cells/hyperlinkcollection)
