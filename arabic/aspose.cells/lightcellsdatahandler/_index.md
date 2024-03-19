---
title: LightCellsDataHandler صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1030
url: /ar/aspose.cells/lightcellsdatahandler/
is_root: false
---
##  LightCellsDataHandler صف
يمثل معالج بيانات الخلايا لقراءة ملفات جداول البيانات الكبيرة في وضع الوزن الخفيف.



يكشف النوع LightCellsDataHandler عن الأعضاء التاليين:

###  طُرق
| طريقة| وصف|
| :- | :- |
| [start_sheet](/cells/python-net/ar/aspose.cells/lightcellsdatahandler/start_sheet/#aspose.cells.Worksheet) | يبدأ في معالجة ورقة العمل.|
| [start_row](/cells/python-net/ar/aspose.cells/lightcellsdatahandler/start_row/#int) | يستعد لمعالجة الصف.|
| [process_row](/cells/python-net/ar/aspose.cells/lightcellsdatahandler/process_row/#aspose.cells.Row) | يبدأ في معالجة صف واحد.|
| [start_cell](/cells/python-net/ar/aspose.cells/lightcellsdatahandler/start_cell/#int) | يستعد لمعالجة الخلية.|
| [process_cell](/cells/python-net/ar/aspose.cells/lightcellsdatahandler/process_cell/#aspose.cells.Cell) | يبدأ بمعالجة خلية واحدة.|



###  ملاحظات

عند قراءة مصنف بهذا الوضع، سيتم التحقق من [`LightCellsDataHandler.start_sheet`](/cells/python-net/ar/aspose.cells/lightcellsdatahandler/start_sheet) عند قراءة كل ورقة عمل في المصنف.
بالنسبة لورقة واحدة، إذا كان الرقم [`LightCellsDataHandler.start_sheet`](/cells/python-net/ar/aspose.cells/lightcellsdatahandler/start_sheet) صحيحًا، فسيتم فحص جميع بيانات وخصائص الصفوف/الخلايا في هذه الورقة
ومعالجتها من خلال تنفيذ هذه الواجهة. لكل صف، سيتم الاتصال بالرقم [`LightCellsDataHandler.start_row`](/cells/python-net/ar/aspose.cells/lightcellsdatahandler/start_row) للتحقق مما إذا كان يحتاج إلى معالجة أم لا.
إذا كان هناك حاجة إلى معالجة الصف، فستتم قراءة خصائص هذا الصف أولاً ويمكن للمستخدم الوصول إلى خصائصه بواسطة [`LightCellsDataHandler.process_row`](/cells/python-net/ar/aspose.cells/lightcellsdatahandler/process_row).
إذا كانت خلايا الصف بحاجة إلى المعالجة أيضًا، فيجب أن يُرجع [`LightCellsDataHandler.process_row`](/cells/python-net/ar/aspose.cells/lightcellsdatahandler/process_row) صحيحًا ثم سيتم إرجاع [`LightCellsDataHandler.start_cell`](/cells/python-net/ar/aspose.cells/lightcellsdatahandler/start_cell)
يتم استدعاء كل خلية موجودة في هذا الصف للتحقق مما إذا كانت خلية واحدة بحاجة إلى المعالجة. إذا كانت خلية واحدة تحتاج إلى معالجة،
ثم سيتم استدعاء [`LightCellsDataHandler.process_cell`](/cells/python-net/ar/aspose.cells/lightcellsdatahandler/process_cell) لمعالجة الخلية من خلال تنفيذ هذه الواجهة.


يرجى ملاحظة أنه يجب على المستخدم أن يعمل فقط على قيم وخصائص كائن الصف/Cell الحالي الذي توفره الطريقة المقابلة.
نظرًا لأن بيانات الخلايا تتم قراءتها من ملف القالب بطريقة متدفقة، فقد تتم إعادة تعيين/تحديث معظم الكائنات الأخرى لاحقًا
بعد أن تم تحميل بيانات الخلايا. لذلك عندما يقوم المستخدم بتشغيل كائنات أخرى في هذا التنفيذ،
قد لا تتمكن هذه العمليات من التأثير على الكائنات الموجودة في المصنف. أو ما هو أسوأ من ذلك، قد تكون تلك العمليات
يتسبب في عدم تناسق البيانات في المصنف ثم يتسبب في حدوث مشكلة أو استثناء غير متوقع لاحقًا.
لذلك، بالنسبة لجميع الكائنات الأخرى مثل الأشكال وعرض العمود والأنماط والتنسيقات الشرطية وما إلى ذلك،
يرجى عدم تشغيلها بأي طريقة من طرق هذا التنفيذ.
بدلاً من ذلك، الرجاء إدارتها بعد إنشاء المصنف.

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
