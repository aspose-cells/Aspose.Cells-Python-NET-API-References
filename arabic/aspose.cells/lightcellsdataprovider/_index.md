---
title: LightCellsDataProvider صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1040
url: /ar/aspose.cells/lightcellsdataprovider/
is_root: false
---
##  LightCellsDataProvider صف
يمثل مزود البيانات لحفظ ملفات جداول البيانات الكبيرة في وضع الوزن الخفيف.



يكشف النوع LightCellsDataProvider عن الأعضاء التاليين:

###  طُرق
| طريقة| وصف|
| :- | :- |
| [start_sheet](/cells/python-net/ar/aspose.cells/lightcellsdataprovider/start_sheet/#int) | يبدأ في حفظ ورقة العمل.|
| [next_row](/cells/python-net/ar/aspose.cells/lightcellsdataprovider/next_row/#) | الحصول على الصف التالي المراد حفظه.|
| [start_row](/cells/python-net/ar/aspose.cells/lightcellsdataprovider/start_row/#aspose.cells.Row) | يبدأ في حفظ بيانات صف واحد.|
| [next_cell](/cells/python-net/ar/aspose.cells/lightcellsdataprovider/next_cell/#) | يحصل على الخلية التالية ليتم حفظها.|
| [start_cell](/cells/python-net/ar/aspose.cells/lightcellsdataprovider/start_cell/#aspose.cells.Cell) | يبدأ في حفظ بيانات خلية واحدة.|
| [is_gather_string](/cells/python-net/ar/aspose.cells/lightcellsdataprovider/is_gather_string/#) |يتحقق مما إذا كانت قيمة السلسلة الحالية للخلية بحاجة إلى التجميع في تجمع عام.|



###  ملاحظات

عند حفظ مصنف بهذا الوضع، سيتم تحديد [`LightCellsDataProvider.start_sheet`](/cells/python-net/ar/aspose.cells/lightcellsdataprovider/start_sheet) عند حفظ كل ورقة عمل في المصنف.
بالنسبة لورقة واحدة، إذا كان الرقم [`LightCellsDataProvider.start_sheet`](/cells/python-net/ar/aspose.cells/lightcellsdataprovider/start_sheet) صحيحًا، فسيتم حفظ جميع البيانات والخصائص لصفوف/خلايا هذه الورقة
سيتم توفيرها من خلال تنفيذ هذه الواجهة.
في المقام الأول، سيتم استدعاء [`LightCellsDataProvider.next_row`](/cells/python-net/ar/aspose.cells/lightcellsdataprovider/next_row) للحصول على فهرس الصف التالي المراد حفظه.
إذا تم إرجاع فهرس صف صالح (يجب أن يكون فهرس الصف بترتيب تصاعدي حتى يتم حفظ الصفوف)،
ثم سيتم توفير كائن صف يمثل هذا الصف بواسطة [`LightCellsDataProvider.start_row`](/cells/python-net/ar/aspose.cells/lightcellsdataprovider/start_row) للتنفيذ لتعيين خصائصه.
لصف واحد، سيتم التحقق من [`LightCellsDataProvider.next_cell`](/cells/python-net/ar/aspose.cells/lightcellsdataprovider/next_cell) أولاً.
إذا تم إرجاع فهرس عمود صالح (يجب أن يكون فهرس العمود بترتيب تصاعدي لجميع خلايا الصف الحالي)،
ثم سيتم توفير كائن Cell يمثل هذه الخلية بواسطة [`LightCellsDataProvider.start_cell`](/cells/python-net/ar/aspose.cells/lightcellsdataprovider/start_cell) للتنفيذ لتعيين بياناتها وخصائصها.
بعد [`LightCellsDataProvider.start_cell`](/cells/python-net/ar/aspose.cells/lightcellsdataprovider/start_cell) سيتم حفظ الخلية مباشرة في ملف جدول البيانات الناتج.
ثم سيتم فحص الخلية التالية ومعالجتها.


يرجى ملاحظة أنه يجب على المستخدم فقط تحديث القيم والخصائص لكائن الصف/Cell الحالي الذي توفره الطريقة المقابلة.
نظرًا لأنه تتم كتابة بيانات الخلايا إلى الملف الناتج بطريقة التدفق، فمن المحتمل أن تكون معظم الكائنات الأخرى قد تمت كتابتها
إلى الملف الناتج، أو تم جمعها وكتابة بعض البيانات العالمية لها. لذلك عندما يقوم المستخدم بتحديث كائنات أخرى
أثناء حفظ بيانات الخلايا، قد لا تتمكن هذه العمليات من التأثير على البيانات المحفوظة. أو ما هو أسوأ من ذلك، قد تكون تلك العمليات
يؤدي إلى حفظ بيانات غير متناسقة في الملف الناتج وفي النهاية يؤدي إلى تلف الملف.
لذلك، بالنسبة لجميع الكائنات الأخرى مثل الأشكال وعرض العمود والأنماط والتنسيقات الشرطية وما إلى ذلك،
يرجى عدم تشغيلها بأي طريقة من طرق هذا التنفيذ.
بدلاً من ذلك، يرجى إدارتها وضبطها على الحالة النهائية قبل استدعاء أسلوب "حفظ" الخاص بالمصنف.

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
