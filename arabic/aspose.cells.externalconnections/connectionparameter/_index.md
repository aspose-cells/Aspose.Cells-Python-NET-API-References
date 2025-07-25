---
title: ConnectionParameter صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 10
url: /ar/aspose.cells.externalconnections/connectionparameter/
is_root: false
---
##  ConnectionParameter صف
يحدد خصائص حول أي معلمات مستخدمة مع اتصالات البيانات الخارجية
المعلمات صالحة لاستعلامات ODBC والويب.



يكشف النوع ConnectionParameter عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [sql_type](/cells/python-net/ar/aspose.cells.externalconnections/connectionparameter/sql_type) | نوع بيانات SQL للمعلمة. صالح فقط لمصادر ODBC.|
| [refresh_on_change](/cells/python-net/ar/aspose.cells.externalconnections/connectionparameter/refresh_on_change) | علم يشير إلى ما إذا كان يجب تحديث الاستعلام تلقائيًا عند ظهور محتويات<br/> الخلية التي تُوفر قيمة المعلمة تتغير. إذا كانت صحيحة، فسيتم تحديث البيانات الخارجية.<br/> باستخدام قيمة المعلمة الجديدة في كل مرة يحدث فيها تغيير. إذا كانت القيمة خاطئة، فسيتم استخدام البيانات الخارجية<br/> يتم تحديثه فقط عندما يطلبه المستخدم، أو عندما يؤدي حدث آخر إلى التحديث (على سبيل المثال، فتح مصنف).|
| [prompt](/cells/python-net/ar/aspose.cells.externalconnections/connectionparameter/prompt) | سلسلة مطالبات للمعلمة. تُعرض على مستخدم جدول البيانات مع واجهة المستخدم المُدخلة.<br/> لجمع قيمة المعلمة قبل تحديث البيانات الخارجية. يُستخدم فقط عند<br/>parameterType = موجه.|
| [type](/cells/python-net/ar/aspose.cells.externalconnections/connectionparameter/type) | نوع المعلمة المستخدمة.<br/> إذا كان نوع المعلمة = القيمة، فإن القيمة من منطقية، مزدوجة، عددية،<br/> سيتم استخدام سلسلة أو سلسلة. في هذه الحالة، من المتوقع استخدام واحد فقط من<br/> سيتم تحديد {boolean، double، integer، أو string}.|
| [name](/cells/python-net/ar/aspose.cells.externalconnections/connectionparameter/name) | اسم المعلمة.|
| [cell_reference](/cells/python-net/ar/aspose.cells.externalconnections/connectionparameter/cell_reference) | Cell مرجع يُشير إلى قيمة الخلية المُراد استخدامها لمعلمة الاستعلام. يُستخدم فقط عندما يكون نوع المعلمة خلية.|
| [value](/cells/python-net/ar/aspose.cells.externalconnections/connectionparameter/value) | قيمة رقمية غير صحيحة، أو قيمة صحيحة، أو قيمة سلسلة، أو قيمة منطقية<br/> لاستخدامه كمعامل استعلام. يُستخدم فقط عندما يكون "نوع المعلمة" قيمة.|



###  أنظر أيضا
* الوحدة [`aspose.cells.externalconnections`](..)
