---
title: LoadFilter صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 940
url: /ar/aspose.cells/loadfilter/
is_root: false
---
##  LoadFilter صف
يمثل الفلتر الذي يوفر خيارات لتحميل البيانات عند تحميل المصنف من القالب.



يكشف النوع LoadFilter عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells/loadfilter/__init__/#) | إنشاء LoadFilter واحد باستخدام خيارات التصفية الافتراضية LoadDataFilterOptions.All.|
| [`__init__(self, opts)`](/cells/python-net/ar/aspose.cells/loadfilter/__init__/#aspose.cells.loaddatafilteroptions) | إنشاء LoadFilter واحد مع خيارات التصفية المحددة.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [load_data_filter_options](/cells/python-net/ar/aspose.cells/loadfilter/load_data_filter_options) |خيارات التصفية للإشارة إلى البيانات التي يجب تحميلها.|
| [sheets_in_loading_order](/cells/python-net/ar/aspose.cells/loadfilter/sheets_in_loading_order) | يحدد الأوراق (المؤشرات) والترتيب الذي سيتم تحميلها.<br/>الإعداد الافتراضي هو null، وهو ما يشير إلى تحميل كافة الأوراق بالترتيب الافتراضي في ملف القالب.<br/> إذا لم يكن فارغًا ولم يكن فهرس بعض الأوراق موجودًا في المصفوفة المرتجعة، فلن يتم تحميل الورقة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`start_sheet(self, sheet)`](/cells/python-net/ar/aspose.cells/loadfilter/start_sheet/#aspose.cells.worksheet) | إعداد خيارات التصفية قبل تحميل ورقة العمل المحددة.<br/>يمكن لتطبيق المستخدم LoadFilter تغيير LoadDataFilterOptions هنا<br/> للإشارة إلى كيفية تحميل البيانات لهذه ورقة العمل.|



###  ملاحظات

يمكن للمستخدم تحديد خيارات التصفية أو تنفيذ LoadFilter الخاصة به لتحديد كيفية تحميل البيانات.

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
