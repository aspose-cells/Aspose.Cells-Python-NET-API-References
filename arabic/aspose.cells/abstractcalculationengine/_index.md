---
title: AbstractCalculationEngine صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/abstractcalculationengine/
is_root: false
---
##  AbstractCalculationEngine صف
يمثل محرك الحساب المخصص للمستخدم لتوسيع محرك الحساب الافتراضي Aspose.Cells.



يكشف النوع AbstractCalculationEngine عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [is_param_literal_required](/cells/python-net/ar/aspose.cells/abstractcalculationengine/is_param_literal_required) |يشير إلى ما إذا كان هذا المحرك يحتاج إلى النص الحرفي للمعلمة أثناء إجراء الحساب. القيمة الافتراضية خاطئة.|
| [is_param_array_mode_required](/cells/python-net/ar/aspose.cells/abstractcalculationengine/is_param_array_mode_required) | يشير إلى ما إذا كان هذا المحرك يحتاج إلى المعلمة التي سيتم حسابها في وضع الصفيف. القيمة الافتراضية خاطئة.<br/>إذا كان [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/ar/aspose.cells/calculationdata/get_param_value_in_array_mode) مطلوبًا عند حساب العرف<br/>الوظائف ولم يقم المستخدم بتحديث التعريف الخاص بها<br/>(بواسطة [`Workbook.update_custom_function_definition`](/cells/python-net/ar/aspose.cells/workbook/update_custom_function_definition))،<br/> يجب تعيين هذه الخاصية على أنها صحيحة.|
| [process_built_in_functions](/cells/python-net/ar/aspose.cells/abstractcalculationengine/process_built_in_functions) | ما إذا كانت الوظائف المضمنة التي تم دعمها بواسطة المحرك المدمج<br/>يجب فحصها ومعالجتها بواسطة هذا التنفيذ.<br/> الافتراضي خطأ.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [calculate](/cells/python-net/ar/aspose.cells/abstractcalculationengine/calculate/#aspose.cells.CalculationData) | يحسب دالة واحدة مع البيانات المعطاة.|



###  ملاحظات

يجب ألا يقوم المستخدم بتعديل أي جزء من المصنف مباشرة في هذا التنفيذ (باستثناء
النتيجة المحسوبة للدالة المخصصة، والتي يمكن تعيينها بواسطة خاصية CalculationData.CalculatedValue).
وإلا قد يحدث نتيجة غير متوقعة أو استثناء.
إذا كان المستخدم يحتاج إلى تغيير بيانات أخرى غير النتيجة المحسوبة في تنفيذ بعض الوظائف المخصصة،
على سبيل المثال، تغيير صيغة الخلية ونمطها ... وما إلى ذلك، يجب على المستخدم جمع تلك البيانات في هذا التنفيذ
وتغييرها خارج نطاق حساب الصيغة.

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
