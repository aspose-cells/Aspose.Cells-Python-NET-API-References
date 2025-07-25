---
title: CalculationData صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 90
url: /ar/aspose.cells/calculationdata/
is_root: false
---
##  CalculationData صف
يمثل البيانات المطلوبة عند حساب دالة واحدة، مثل اسم الدالة، المعلمات، ...الخ.



يكشف النوع CalculationData عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [calculated_value](/cells/python-net/ar/aspose.cells/calculationdata/calculated_value) | يحصل على القيمة المحسوبة لهذه الوظيفة أو يعينها.|
| [workbook](/cells/python-net/ar/aspose.cells/calculationdata/workbook) | يحصل على كائن المصنف الذي توجد فيه الوظيفة.|
| [worksheet](/cells/python-net/ar/aspose.cells/calculationdata/worksheet) | يحصل على كائن ورقة العمل الذي توجد فيه الوظيفة.|
| [cell_row](/cells/python-net/ar/aspose.cells/calculationdata/cell_row) | يحصل على مؤشر الصف للخلية التي تتواجد بها الوظيفة.|
| [cell_column](/cells/python-net/ar/aspose.cells/calculationdata/cell_column) | يحصل على مؤشر العمود للخلية التي تتواجد فيها الوظيفة.|
| [cell](/cells/python-net/ar/aspose.cells/calculationdata/cell) |يحصل على الكائن Cell حيث توجد الوظيفة.|
| [function_name](/cells/python-net/ar/aspose.cells/calculationdata/function_name) | يحصل على اسم الوظيفة المراد حسابها.|
| [param_count](/cells/python-net/ar/aspose.cells/calculationdata/param_count) | يحصل على عدد المعلمات|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`get_param_value(self, index)`](/cells/python-net/ar/aspose.cells/calculationdata/get_param_value/#int) |يحصل على كائن القيمة الممثلة للمعلمة في فهرس معين.|
| [`get_param_value_in_array_mode(self, index, max_row_count, max_column_count)`](/cells/python-net/ar/aspose.cells/calculationdata/get_param_value_in_array_mode/#int-int-int) | يحصل على قيمة (قيم) المعلمة عند الفهرس المحدد.<br/>إذا كانت المعلمة عبارة عن نوع من التعبير الذي يحتاج إلى حساب،<br/> ثم سيتم حسابه في وضع المصفوفة.|
| [`get_param_text(self, index)`](/cells/python-net/ar/aspose.cells/calculationdata/get_param_text/#int) | يحصل على النص الحرفي للمعلمة في الفهرس المحدد.|



###  ملاحظات

كافة الكائنات التي توفرها هذه الفئة مخصصة لغرض "القراءة" فقط.
يجب ألا يقوم المستخدم بتغيير أي بيانات في المصنف أثناء عملية حساب الصيغة،
وإلا قد يحدث نتيجة غير متوقعة أو استثناء.

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
