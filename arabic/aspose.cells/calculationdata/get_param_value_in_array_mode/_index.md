---
title: طريقة get_param_value_in_array_mode
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells/calculationdata/get_param_value_in_array_mode/
is_root: false
---
##  get_param_value_in_array_mode {#int-int-int}
يحصل على قيمة (قيم) المعلمة في الفهرس المحدد.
إذا كانت المعلمة عبارة عن نوع من التعبير الذي يجب حسابه،
ثم سيتم حسابه في وضع الصفيف.


###  عائدات

مصفوفة تحتوي على كافة العناصر الممثلة بالمعلمة المحددة.


```python
def get_param_value_in_array_mode(self, index, max_row_count, max_column_count):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| index | int | فهرس المعلمة (0 على أساس)|
| max_row_count | int | الحد الأقصى لعدد الصفوف للمصفوفة التي تم إرجاعها.<br/> إذا كان غير موجب أو أكبر من عدد الصفوف الفعلي، فسيتم استخدام عدد الصفوف الفعلي.|
| max_column_count | int | الحد الأقصى لعدد الأعمدة للمصفوفة التي تم إرجاعها.<br/> إذا كان غير موجب أو أكبر من عدد الصفوف الفعلي، فسيتم استخدام عدد الأعمدة الفعلي.|
###  ملاحظات

بالنسبة للتعبير الذي يحتاج إلى حساب، مع أخذ A:A+B:B كمثال:
في وضع القيمة، سيتم حسابه إلى قيمة واحدة وفقًا لقاعدة الخلية الحالية.
ولكن في وضع المصفوفة، سيتم حساب كافة قيم A1+B1,A2+B2,A3+B3,... واستخدامها لإنشاء المصفوفة التي تم إرجاعها.
وفي مثل هذا النوع من المواقف، من الأفضل تحديد الحد الأقصى لعدد الصفوف/الأعمدة
(مثلًا وفقًا لـ [`Cells.max_data_row`](/cells/python-net/ar/aspose.cells/cells#max_data_row) و[`Cells.max_data_column`](/cells/python-net/ar/aspose.cells/cells#max_data_column))،
وإلا فإن المصفوفة الكبيرة التي تم إرجاعها قد تزيد من تكلفة الذاكرة بكمية كبيرة من البيانات غير المفيدة.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CalculationData`](/cells/python-net/ar/aspose.cells/calculationdata)
