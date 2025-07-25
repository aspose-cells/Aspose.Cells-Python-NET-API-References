---
title: Protection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1150
url: /ar/aspose.cells/protection/
is_root: false
---
##  Protection صف
يمثل الأنواع المختلفة من خيارات الحماية المتوفرة لورقة العمل.



يكشف النوع Protection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [allow_deleting_column](/cells/python-net/ar/aspose.cells/protection/allow_deleting_column) | يمثل ما إذا كان يُسمح بحذف الأعمدة في ورقة عمل محمية.|
| [allow_deleting_row](/cells/python-net/ar/aspose.cells/protection/allow_deleting_row) | يمثل ما إذا كان يُسمح بحذف الصفوف في ورقة عمل محمية.|
| [allow_filtering](/cells/python-net/ar/aspose.cells/protection/allow_filtering) | يمثل ما إذا كان يُسمح للمستخدم بالاستفادة من مرشح تلقائي تم إنشاؤه قبل حماية الورقة.|
| [allow_formatting_cell](/cells/python-net/ar/aspose.cells/protection/allow_formatting_cell) | يمثل ما إذا كان تنسيق الخلايا مسموحًا به في ورقة عمل محمية.|
| [allow_formatting_column](/cells/python-net/ar/aspose.cells/protection/allow_formatting_column) | يمثل ما إذا كان تنسيق الأعمدة مسموحًا به في ورقة عمل محمية|
| [allow_formatting_row](/cells/python-net/ar/aspose.cells/protection/allow_formatting_row) |يمثل ما إذا كان تنسيق الصفوف مسموحًا به في ورقة عمل محمية|
| [allow_inserting_column](/cells/python-net/ar/aspose.cells/protection/allow_inserting_column) | يمثل ما إذا كان يُسمح بإدراج الأعمدة في ورقة عمل محمية|
| [allow_inserting_hyperlink](/cells/python-net/ar/aspose.cells/protection/allow_inserting_hyperlink) | يمثل ما إذا كان يُسمح بإدراج الارتباطات التشعبية في ورقة عمل محمية|
| [allow_inserting_row](/cells/python-net/ar/aspose.cells/protection/allow_inserting_row) | يمثل ما إذا كان يُسمح بإدراج الصفوف في ورقة عمل محمية|
| [allow_sorting](/cells/python-net/ar/aspose.cells/protection/allow_sorting) | يمثل ما إذا كان خيار الفرز مسموحًا به في ورقة عمل محمية.|
| [allow_using_pivot_table](/cells/python-net/ar/aspose.cells/protection/allow_using_pivot_table) | يمثل ما إذا كان يُسمح للمستخدم بالتلاعب بجداول البيانات المحورية في ورقة عمل محمية.|
| [allow_editing_content](/cells/python-net/ar/aspose.cells/protection/allow_editing_content) | يمثل ما إذا كان يُسمح للمستخدم بتحرير محتويات الخلايا المقفلة في ورقة عمل محمية.|
| [allow_editing_object](/cells/python-net/ar/aspose.cells/protection/allow_editing_object) | يمثل ما إذا كان يُسمح للمستخدم بالتعامل مع كائنات الرسم الموجودة على ورقة عمل محمية.|
| [allow_editing_scenario](/cells/python-net/ar/aspose.cells/protection/allow_editing_scenario) | يمثل ما إذا كان يُسمح للمستخدم بتحرير السيناريوهات الموجودة في ورقة عمل محمية.|
| [allow_selecting_locked_cell](/cells/python-net/ar/aspose.cells/protection/allow_selecting_locked_cell) | يمثل ما إذا كان يُسمح للمستخدم بتحديد الخلايا المقفلة في ورقة عمل محمية.|
| [allow_selecting_unlocked_cell](/cells/python-net/ar/aspose.cells/protection/allow_selecting_unlocked_cell) | يمثل ما إذا كان يُسمح للمستخدم بتحديد الخلايا غير المؤمنة في ورقة عمل محمية.|
| [password](/cells/python-net/ar/aspose.cells/protection/password) | يمثل كلمة المرور لحماية ورقة العمل.|
| [is_protected_with_password](/cells/python-net/ar/aspose.cells/protection/is_protected_with_password) | يشير إلى ما إذا كانت أوراق العمل محمية بكلمة مرور.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/ar/aspose.cells/protection/copy/#aspose.cells.protection) |معلومات حماية النسخ.|
| [`verify_password(self, password)`](/cells/python-net/ar/aspose.cells/protection/verify_password/#str) | التحقق من كلمة المرور.|
| [`get_password_hash(self)`](/cells/python-net/ar/aspose.cells/protection/get_password_hash/#) | يحصل على تجزئة كلمة المرور الحالية.|



###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Allowing users to select locked cells of the worksheet
worksheet.protection.allow_selecting_locked_cell = True
# Allowing users to select unlocked cells of the worksheet
worksheet.protection.allow_selecting_unlocked_cell = True

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
