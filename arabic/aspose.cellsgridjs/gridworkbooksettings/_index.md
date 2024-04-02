---
title: GridWorkbookSettings صف
second_title: Aspose.Cells.GridJs for Python via .NET API المراجع
description:
type: docs
weight: 80
url: /ar/aspose.cellsgridjs/gridworkbooksettings/
is_root: false
---
##  GridWorkbookSettings صف

يمثل إعدادات المصنف.



يكشف النوع GridWorkbookSettings عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cellsgridjs/gridworkbooksettings/__init__/#) | إنشاء مثيل جديد لـ GridWorkbookSettings|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [max_iteration](/cells/python-net/ar/aspose.cellsgridjs/gridworkbooksettings/max_iteration) | إرجاع أو تعيين الحد الأقصى لعدد التكرارات لحل مرجع دائري، القيمة الافتراضية هي 100.|
| [iteration](/cells/python-net/ar/aspose.cellsgridjs/gridworkbooksettings/iteration) | يشير إلى ما إذا كان سيتم استخدام التكرار لحل المراجع الدائرية.|
| [force_full_calculate](/cells/python-net/ar/aspose.cellsgridjs/gridworkbooksettings/force_full_calculate) | يشير إلى ما إذا كان سيتم الحساب بالكامل في كل مرة يتم فيها تشغيل عملية حسابية.|
| [create_calc_chain](/cells/python-net/ar/aspose.cellsgridjs/gridworkbooksettings/create_calc_chain) |يشير إلى ما إذا كان سيتم إنشاء سلسلة صيغ محسوبة. الافتراضي خطأ.|
| [re_calculate_on_open](/cells/python-net/ar/aspose.cellsgridjs/gridworkbooksettings/re_calculate_on_open) | يشير إلى ما إذا كان سيتم إعادة حساب جميع الصيغ عند فتح الملف.|
| [precision_as_displayed](/cells/python-net/ar/aspose.cellsgridjs/gridworkbooksettings/precision_as_displayed) | صحيح إذا كانت العمليات الحسابية في هذا المصنف ستتم باستخدام دقة الأرقام كما يتم عرضها فقط|
| [date1904](/cells/python-net/ar/aspose.cellsgridjs/gridworkbooksettings/date1904) | الحصول على قيمة تمثل ما إذا كان المصنف يستخدم نظام التاريخ 1904 أو تعيينه.|
| [enable_macros](/cells/python-net/ar/aspose.cellsgridjs/gridworkbooksettings/enable_macros) | تمكين وحدات الماكرو. الآن يعمل فقط عند نسخ ورقة عمل إلى ورقة عمل أخرى في مصنف.|
| [check_custom_number_format](/cells/python-net/ar/aspose.cellsgridjs/gridworkbooksettings/check_custom_number_format) | يشير إلى ما إذا كان سيتم التحقق من تنسيق الأرقام المخصص عند ضبط Style.Custom.|
| [author](/cells/python-net/ar/aspose.cellsgridjs/gridworkbooksettings/author) | يحصل على/يحدد مؤلف الملف.|



###  مثال


```python
from aspose.cellsgridjs import GridJsWorkbook, GridWorkbookSettings

g = GridJsWorkbook()
gsettings = GridWorkbookSettings()
g.settings = gsettings

```

###  أنظر أيضا
* الوحدة [`aspose.cellsgridjs`](..)
