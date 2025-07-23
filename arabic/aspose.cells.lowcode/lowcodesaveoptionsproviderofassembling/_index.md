---
title: LowCodeSaveOptionsProviderOfAssembling صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 110
url: /ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/
is_root: false
---
##  LowCodeSaveOptionsProviderOfAssembling صف
التنفيذ لتوفير خيارات الحفظ التي تحفظ الأجزاء المنقسمة في الملفات
ويتم تسمية مسار الملف الناتج على النحو التالي (قد يحتوي على أدلة):
[`LowCodeSaveOptionsProviderOfAssembling.path_header`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_header)+[`LowCodeSaveOptionsProviderOfAssembling.sheet_prefix`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#sheet_prefix)+SheetIndex(أو SheetName)
+[`LowCodeSaveOptionsProviderOfAssembling.split_part_prefix`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#split_part_prefix)+SplitPartIndex+[`LowCodeSaveOptionsProviderOfAssembling.path_tail`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling#path_tail).



**الميراث:** [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)



يكشف النوع LowCodeSaveOptionsProviderOfAssembling عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/__init__/#) | إنشاء مثيل جديد لـ LowCodeSaveOptionsProviderOfAssembling|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [path_header](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_header) | جزء الرأس (قبل إضافة محتوى الورقة والجزء المنقسم) من مسار الملف.|
| [path_tail](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/path_tail) | الجزء الأخير (بعد أرقام التسلسل) من مسار الملف.<br/> ينبغي أن يتضمن امتداد اسم الملف.|
| [use_sheet_name](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/use_sheet_name) | هل يُبنى مسار الملف باسم الورقة بدلاً من فهرسها؟ القيمة الافتراضية هي خطأ.|
| [sheet_prefix](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_prefix) |بادئة لمؤشر ورقة العمل.|
| [split_part_prefix](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_prefix) | بادئة لمؤشر الجزء المنقسم.|
| [sheet_index_offset](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/sheet_index_offset) | إزاحة فهرس الورقة بين ما تم استخدامه في مسار الملف<br/> وقيمتها الحقيقية([`SplitPartInfo.sheet_index`](/cells/python-net/ar/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/split_part_index_offset) | إزاحة مؤشر الجزء المنقسم بين ما تم استخدامه في مسار الملف<br/> وقيمتها الحقيقية([`SplitPartInfo.part_index`](/cells/python-net/ar/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_sheet_always) | سواء قمت بإضافة فهرس الورقة أو الاسم إلى مسار الملف دائمًا.<br/>القيمة الافتراضية هي false، أي عندما تكون هناك ورقة واحدة فقط،<br/> لن يتم إضافة فهرس الورقة (أو الاسم) والبادئة المقابلة إلى مسار الملف.|
| [build_path_with_split_part_always](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/build_path_with_split_part_always) | ما إذا كان سيتم إضافة فهرس الجزء المنقسم إلى مسار الملف دائمًا.<br/>القيمة الافتراضية هي false، أي عندما يكون هناك جزء مقسم واحد فقط،<br/> لن يتم إضافة فهرس الجزء المنقسم والبادئة المقابلة له إلى مسار الملف.|
| [save_options_template](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/save_options_template) | القالب لإنشاء مثيل لخيارات الحفظ في [`LowCodeSaveOptionsProviderOfAssembling.get_save_options`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options).|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/get_save_options/#aspose.cells.lowcode.splitpartinfo) | يحصل على خيارات الحفظ التي يمكن من خلالها الحصول على إعدادات الإخراج للجزء المقسم حاليًا.|
| [`finish(self, part)`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  أنظر أيضا
* الوحدة [`aspose.cells.lowcode`](..)
* فئة [`LowCodeSaveOptionsProviderOfAssembling`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofassembling)
