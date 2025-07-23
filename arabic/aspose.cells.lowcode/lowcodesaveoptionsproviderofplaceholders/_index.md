---
title: LowCodeSaveOptionsProviderOfPlaceHolders صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 120
url: /ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/
is_root: false
---
##  LowCodeSaveOptionsProviderOfPlaceHolders صف
التنفيذ لتوفير خيارات الحفظ التي تحفظ الأجزاء المنقسمة في الملفات
ويتم تحديد مسار الملف الناتج باستخدام عناصر نائبة.



**الميراث:** [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)



يكشف النوع LowCodeSaveOptionsProviderOfPlaceHolders عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self, path_template)`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/__init__/#str) |إنشاء مثيل لتوفير خيارات الحفظ وفقًا للقوالب المحددة.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [sheet_index_offset](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_offset) | إزاحة فهرس الورقة بين ما تم استخدامه في مسار الملف<br/> وقيمتها الحقيقية([`SplitPartInfo.sheet_index`](/cells/python-net/ar/aspose.cells.lowcode/splitpartinfo#sheet_index)).|
| [split_part_index_offset](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_index_offset) | إزاحة مؤشر الجزء المنقسم بين ما تم استخدامه في مسار الملف<br/> وقيمتها الحقيقية([`SplitPartInfo.part_index`](/cells/python-net/ar/aspose.cells.lowcode/splitpartinfo#part_index)).|
| [build_path_with_sheet_always](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_sheet_always) | سواء قمت بإضافة فهرس الورقة أو الاسم إلى مسار الملف دائمًا.<br/>القيمة الافتراضية هي false، أي عندما تكون هناك ورقة واحدة فقط،<br/>فهرس الورقة والاسم والبادئة المقابلة ([`LowCodeSaveOptionsProviderOfPlaceHolders.sheet_name_prefix`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#sheet_name_prefix))<br/> لن تتم إضافته إلى مسار الملف.|
| [build_path_with_split_part_always](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/build_path_with_split_part_always) | ما إذا كان سيتم إضافة فهرس الجزء المنقسم إلى مسار الملف دائمًا.<br/>القيمة الافتراضية هي false، أي عندما يكون هناك جزء مقسم واحد فقط،<br/>مؤشر الجزء المنقسم والبادئة المقابلة ([`LowCodeSaveOptionsProviderOfPlaceHolders.split_part_prefix`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders#split_part_prefix))<br/> لن تتم إضافته إلى مسار الملف.|
| [sheet_name_prefix](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_name_prefix) |بادئة لمؤشر ورقة العمل.|
| [sheet_index_prefix](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/sheet_index_prefix) |بادئة لمؤشر ورقة العمل.|
| [split_part_prefix](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/split_part_prefix) | بادئة لمؤشر الجزء المنقسم.|
| [save_options_template](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/save_options_template) | القالب لإنشاء مثيل لخيارات الحفظ في [`LowCodeSaveOptionsProviderOfPlaceHolders.get_save_options`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options).|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/get_save_options/#aspose.cells.lowcode.splitpartinfo) | يحصل على خيارات الحفظ التي يمكن من خلالها الحصول على إعدادات الإخراج للجزء المقسم حاليًا.|
| [`finish(self, part)`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders/finish/#aspose.cells.lowcode.lowcodesaveoptions) |  |



###  أنظر أيضا
* الوحدة [`aspose.cells.lowcode`](..)
* فئة [`LowCodeSaveOptionsProviderOfPlaceHolders`](/cells/python-net/ar/aspose.cells.lowcode/lowcodesaveoptionsproviderofplaceholders)
