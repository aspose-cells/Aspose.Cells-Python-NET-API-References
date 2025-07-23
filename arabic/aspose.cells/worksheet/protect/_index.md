---
title: طريقة protect
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 220
url: /ar/aspose.cells/worksheet/protect/
is_root: false
---
##  protect(self, type) {#aspose.cells.ProtectionType}
يحمي ورقة العمل.



```python

def protect(self, type):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/ar/aspose.cells/protectiontype) | نوع الحماية.|
###  ملاحظات

هذه الطريقة تحمي أوراق العمل دون كلمة مرور. تتوافق مع جميع إصدارات ملفات إكسل.

##  protect(self, type, password, old_password) {#aspose.cells.ProtectionType-str-str}

يحمي ورقة العمل.



```python

def protect(self, type, password, old_password):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| type | [`ProtectionType`](/cells/python-net/ar/aspose.cells/protectiontype) | نوع الحماية.|
| password | str | كلمة المرور.|
| old_password | str | إذا كانت ورقة العمل محمية بالفعل بكلمة مرور، فيرجى تقديم كلمة المرور القديمة.<br/> يمكنك أيضًا تعيين قيمة فارغة أو سلسلة فارغة لهذه المعلمة.|
###  ملاحظات

يمكن لهذه الطريقة protect ورقة عمل في جميع إصدارات ملف Excel.
###  مثال


```python
from aspose.cells import ProtectionType, Workbook

# Instantiating a Workbook object
excel = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = excel.worksheets[0]
# Protecting the worksheet with a password
worksheet.protect(ProtectionType.ALL, "aspose", None)
# Saving the modified Excel file in default (that is Excel 20003) format
excel.save("output.xls")

```



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Worksheet`](/cells/python-net/ar/aspose.cells/worksheet)
