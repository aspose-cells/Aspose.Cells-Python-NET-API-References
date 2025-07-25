---
title: طريقة get_enumerator
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 30
url: /ar/aspose.cells/rowcollection/get_enumerator/
is_root: false
---
##  get_enumerator(self, reversed, sync) {#bool-bool}
يحصل على مُعَدِّد يكرر الصفوف عبر هذه المجموعة


###  عائدات

عدّاد الصفوف


```python

def get_enumerator(self, reversed, sync):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| reversed | bool | ما إذا كان يتم حصر الصفوف بالترتيب العكسي|
| sync | bool | ما إذا كان يجب على المُعدّ المُعاد التحقق من تعديل مجموعة الصفوف<br/> والحفاظ على التزامن معه.|
###  ملاحظات

إذا تم تعديل مجموعة الصفوف (من خلال العمليات التي قد تتسبب في إنشاء صف جديد أو
(يجب إزالة الصف الموجود) أثناء العبور باستخدام المُعدِّد،
يجب استخدام المُعدِّد المتزامن بدلاً من المُعدِّد العادي حتى يمكن أن يستمر العبور
من الموضع الذي يليه مباشرة بعد عبوره بواسطة MoveNext() الأخير.
ومع ذلك، إلى جانب الميزة المتمثلة في عدم إمكانية تخطي أي عنصر أو عبوره بشكل متكرر،
العيب في المُعدِّد المتزامن هو أن الأداء سينخفض قليلاً
عند المقارنة مع المعدّد العادي.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`RowCollection`](/cells/python-net/ar/aspose.cells/rowcollection)
