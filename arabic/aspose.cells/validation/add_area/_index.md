---
title: طريقة add_area
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/validation/add_area/
is_root: false
---
##  add_area(self, cell_area) {#aspose.cells.CellArea}
يتم تطبيق التحقق على المنطقة.



```python

def add_area(self, cell_area):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/ar/aspose.cells/cellarea) | المنطقة.|
###  ملاحظات

وهو يعادل استخدام [`Validation.add_area`](/cells/python-net/ar/aspose.cells/validation/add_area)
مع التحقق من التقاطع والحافة.

##  add_area(self, cell_area, check_intersection, check_edge) {#aspose.cells.CellArea-bool-bool}
يتم تطبيق التحقق على المنطقة.



```python

def add_area(self, cell_area, check_intersection, check_edge):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/ar/aspose.cells/cellarea) | المنطقة.|
| check_intersection | bool | ما إذا كان يتم التحقق من تقاطع المنطقة المحددة مع مناطق التحقق الموجودة.<br/>إذا تم تطبيق التحقق من الصحة في منطقة معينة (أو جزء منها)،<br/>ثم يجب إزالة التحقق الحالي أولاً من المنطقة المحددة.<br/>قد يؤدي عدم القيام بذلك إلى حدوث فساد لعمليات التحقق التي تم إنشاؤها.<br/>إذا كان المستخدم متأكدًا من أن المنطقة المضافة لا تتقاطع مع أي منطقة موجودة،<br/> يمكن تعيين هذه المعلمة على أنها خاطئة لأغراض تقييم الأداء.|
| check_edge | bool | ما إذا كان يتم التحقق من حافة المناطق المطبقة على هذا التحقق.<br/>تعتمد الإعدادات الداخلية للتحقق على أحد النطاقات المطبقة في الجزء العلوي الأيسر،<br/>لذا إذا أصبحت المنطقة المحددة هي المنطقة العلوية اليسرى الجديدة من النطاقات المطبقة،<br/>ينبغي تغيير الإعدادات الداخلية وإعادة بنائها، وإلا فقد يؤدي ذلك إلى نتائج غير متوقعة.<br/>إذا كان المستخدم متأكدًا من أن المنطقة المضافة ليست المنطقة العلوية اليسرى،<br/> يمكن تعيين هذه المعلمة على أنها خاطئة لأغراض تقييم الأداء.|
###  ملاحظات

في هذه الطريقة، سوف نقوم بإزالة جميع عمليات التحقق القديمة في المنطقة المحددة.
بالنسبة للنطاق المطبق في أعلى اليسار من نطاقات التحقق، أولاً يكون صف البداية الخاص به هو الأصغر،
ثانيًا، يعد عمود البدء الخاص به هو الأصغر بين تلك المناطق التي لها نفس أصغر صف بدء.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Validation`](/cells/python-net/ar/aspose.cells/validation)
