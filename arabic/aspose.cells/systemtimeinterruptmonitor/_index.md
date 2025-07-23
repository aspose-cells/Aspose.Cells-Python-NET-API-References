---
title: SystemTimeInterruptMonitor صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1390
url: /ar/aspose.cells/systemtimeinterruptmonitor/
is_root: false
---
##  SystemTimeInterruptMonitor صف
تنفيذ بسيط لـ AbstractInterruptMonitor عن طريق التحقق من وقت النظام الحالي ومقارنته مع الحد الذي يحدده المستخدم.



**الميراث:** [`SystemTimeInterruptMonitor`](/cells/python-net/ar/aspose.cells/systemtimeinterruptmonitor)



يكشف النوع SystemTimeInterruptMonitor عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/ar/aspose.cells/systemtimeinterruptmonitor/__init__/#bool) | إنشاء مراقب مقاطعة واحد.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [is_interruption_requested](/cells/python-net/ar/aspose.cells/systemtimeinterruptmonitor/is_interruption_requested) | يتحقق هذا التنفيذ فقط مما إذا كانت تكلفة الوقت (من وقت بدء تشغيل هذه الشاشة حتى الآن) أكبر من الحد الذي حدده المستخدم.|
| [terminate_without_exception](/cells/python-net/ar/aspose.cells/systemtimeinterruptmonitor/terminate_without_exception) |انظر TerminateWithoutException.<br/> يتم تحديد هذه الخاصية بواسطة المستخدم عند إنشاء مثيل الشاشة هذا.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/ar/aspose.cells/systemtimeinterruptmonitor/start_monitor/#int) | يبدأ تشغيل الشاشة بالحد الزمني المحدد. وقت بدء حساب تكلفة الوقت هو عند استدعاء هذه الطريقة.<br/> لذلك، يجب البدء في الإجراء الذي يحتاج إلى المراقبة بعد هذه المكالمة مباشرة.|



###  ملاحظات

يعد هذا التنفيذ مجرد حل بسيط لسيناريوهات بسيطة.
يحتاج إلى استرجاع وقت النظام والتحقق منه بشكل متكرر، لذا فقد يكون له تأثير سلبي على الأداء إلى حد ما.

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`SystemTimeInterruptMonitor`](/cells/python-net/ar/aspose.cells/systemtimeinterruptmonitor)
