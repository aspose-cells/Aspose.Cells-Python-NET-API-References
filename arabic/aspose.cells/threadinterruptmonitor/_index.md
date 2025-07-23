---
title: ThreadInterruptMonitor صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1410
url: /ar/aspose.cells/threadinterruptmonitor/
is_root: false
---
##  ThreadInterruptMonitor صف
تنفيذ بسيط لـ AbstractInterruptMonitor عن طريق بدء تشغيل مؤشر ترابط آخر لطلب المقاطعة بعد وضع حد معين للمستخدم في وضع السكون.



**الميراث:** [`ThreadInterruptMonitor`](/cells/python-net/ar/aspose.cells/threadinterruptmonitor)



يكشف النوع ThreadInterruptMonitor عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self, terminate_without_exception)`](/cells/python-net/ar/aspose.cells/threadinterruptmonitor/__init__/#bool) | إنشاء مراقب مقاطعة واحد.|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [is_interruption_requested](/cells/python-net/ar/aspose.cells/threadinterruptmonitor/is_interruption_requested) | يتحقق هذا التنفيذ فقط مما إذا كانت تكلفة الوقت (من وقت بدء تشغيل هذه الشاشة حتى الآن) أكبر من الحد الذي حدده المستخدم.|
| [terminate_without_exception](/cells/python-net/ar/aspose.cells/threadinterruptmonitor/terminate_without_exception) |انظر TerminateWithoutException.<br/> يتم تحديد هذه الخاصية بواسطة المستخدم عند إنشاء مثيل الشاشة هذا.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`start_monitor(self, ms_limit)`](/cells/python-net/ar/aspose.cells/threadinterruptmonitor/start_monitor/#int) | يبدأ تشغيل الشاشة بالحد الزمني المحدد. وقت بدء حساب تكلفة الوقت هو عند استدعاء هذه الطريقة.<br/> لذلك، يجب البدء في الإجراء الذي يحتاج إلى المراقبة بعد هذه المكالمة مباشرة.|
| [`finish_monitor(self)`](/cells/python-net/ar/aspose.cells/threadinterruptmonitor/finish_monitor/#) | ينهي المراقبة لإجراء واحد.|



###  ملاحظات

يمكن استخدام مثيل شاشة واحد بشكل متكرر، طالما قمت بمراقبة كل عملية بالتسلسل.
لا ينبغي استخدامه لمراقبة إجراءات متعددة في وقت واحد في خيوط متعددة.

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`ThreadInterruptMonitor`](/cells/python-net/ar/aspose.cells/threadinterruptmonitor)
