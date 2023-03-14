---
title: طريقة protect
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 180
url: /ar/aspose.cells/worksheet/protect/
is_root: false
---
##  protect(type) {#ProtectionType}
يحمي ورقة العمل.



```python
def protect(self, type):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| type | [ProtectionType](/cells/python-net/ar/aspose.cells/protectiontype) | نوع الحماية.|
###  ملاحظات

هذه الطريقة تحمي ورقة العمل بدون كلمة مرور. يمكن أن protect ورقة عمل في جميع إصدارات ملف Excel.

##  protect(type, password, old_password) {#ProtectionType-str-str}

يحمي ورقة العمل.



```python
def protect(self, type, password, old_password):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| type | [ProtectionType](/cells/python-net/ar/aspose.cells/protectiontype) | نوع الحماية.|
| password | str | كلمة المرور.|
| old_password | str | إذا كانت ورقة العمل محمية بالفعل بكلمة مرور ، فيرجى توفير كلمة المرور القديمة.<br/> خلاف ذلك ، يمكنك تعيين قيمة فارغة أو سلسلة فارغة لهذه المعلمة.|
###  ملاحظات

يمكن لهذه الطريقة أن protect ورقة عمل في كافة إصدارات ملف Excel.
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
* وحدة [aspose.cells](../../)
* فئة [Worksheet](/cells/python-net/ar/aspose.cells/worksheet)
