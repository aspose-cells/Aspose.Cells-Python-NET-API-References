---
title: Hyperlink صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 840
url: /ar/aspose.cells/hyperlink/
is_root: false
---
##  Hyperlink صف
يقوم بتغليف الكائن الذي يمثل ارتباطًا تشعبيًا.



يكشف النوع Hyperlink عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [address](/cells/python-net/ar/aspose.cells/hyperlink/address) | يمثل عنوان الارتباط التشعبي.|
| [text_to_display](/cells/python-net/ar/aspose.cells/hyperlink/text_to_display) | يمثل النص الذي سيتم عرضه للارتباط التشعبي المحدد. القيمة الافتراضية هي عنوان الارتباط التشعبي.|
| [area](/cells/python-net/ar/aspose.cells/hyperlink/area) | يحصل على نطاق الارتباط التشعبي.|
| [screen_tip](/cells/python-net/ar/aspose.cells/hyperlink/screen_tip) | إرجاع أو تعيين نص تلميح الشاشة للارتباط التشعبي المحدد.|
| [link_type](/cells/python-net/ar/aspose.cells/hyperlink/link_type) | يحصل على نوع الارتباط.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [delete](/cells/python-net/ar/aspose.cells/hyperlink/delete/#) |يحذف هذا الارتباط التشعبي|



###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Workbook object
workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Adding a hyperlink to a URL at "A1" cell
index = worksheet.hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Getting a Hyperlink by index.
hyperlink = worksheet.hyperlinks[index]
# Setting display text of this hyperlink.
hyperlink.text_to_display = "Aspose"
# Saving the Excel file
workbook.save("book1.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
