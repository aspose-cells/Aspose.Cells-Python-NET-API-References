---
title: طريقة get_param_value_in_array_mode
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells/calculationdata/get_param_value_in_array_mode/
is_root: false
---
##  get_param_value_in_array_mode(self, index, max_row_count, max_column_count) {#int-int-int}
يحصل على قيمة (قيم) المعلمة عند الفهرس المحدد.
إذا كانت المعلمة عبارة عن نوع من التعبير الذي يحتاج إلى حساب،
ثم سيتم حسابه في وضع المصفوفة.


###  عائدات

مصفوفة تحتوي على جميع العناصر التي يمثلها المعلمة المحددة.


```python

def get_param_value_in_array_mode(self, index, max_row_count, max_column_count):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| index | int | مؤشر المعلمة (على أساس 0)|
| max_row_count | int | حد عدد الصفوف للمصفوفة المرتجعة.<br/> إذا كان غير موجب أو أكبر من عدد الصفوف الفعلي، فسيتم استخدام عدد الصفوف الفعلي.|
| max_column_count | int | حد عدد الأعمدة للمصفوفة المرتجعة.<br/> إذا كان غير موجب أو أكبر من عدد الصفوف الفعلي، فسيتم استخدام عدد الأعمدة الفعلي.|
###  ملاحظات

بالنسبة للتعبير الذي يحتاج إلى حساب، خذ A:A+B:B كمثال:
في وضع القيمة، سيتم حسابها لقيمة واحدة وفقًا لقاعدة الخلية الحالية.
ولكن في وضع المصفوفة، سيتم حساب جميع قيم A1+B1،A2+B2،A3+B3،... واستخدامها لبناء المصفوفة المرتجعة.
وفي مثل هذا النوع من المواقف، من الأفضل تحديد حد لعدد الصفوف/الأعمدة
(مثل وفقًا لـ [`Cells.max_data_row`](/cells/python-net/ar/aspose.cells/cells#max_data_row) و [`Cells.max_data_column`](/cells/python-net/ar/aspose.cells/cells#max_data_column))،
وإلا فإن المصفوفة الكبيرة المرتجعة قد تزيد من تكلفة الذاكرة بسبب كمية كبيرة من البيانات غير المفيدة.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CalculationData`](/cells/python-net/ar/aspose.cells/calculationdata)
