---
title: invariant_custom عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 260
url: /ar/aspose.cells/style/invariant_custom/
is_root: false
---
##  invariant_custom عقار

يحصل على سلسلة النمط المستقلة عن الثقافة لتنسيق الأرقام.
إذا لم يتم تعيين تنسيق رقم لهذا الكائن، فسيتم إرجاع القيمة null.
إذا تم تضمين تنسيق الرقم، فسيتم إرجاع سلسلة النمط المقابلة للرقم المدمج.

###  ملاحظات

بالنسبة لتنسيقات الأرقام المضمنة، لا يزال محتوى النمط المُرجع يعتمد على الثقافة،
على سبيل المثال، بالنسبة لبعض المواقع المحلية، فإنه يعود "m/d/y" وبالنسبة لبعض المواقع المحلية الأخرى فإنه يعود "d/m/y".
الفرق عن [`Style.culture_custom`](/cells/python-net/ar/aspose.cells/style#culture_custom) هو (وهذا هو أيضًا ما يعنيه الاستقلال الثقافي):
يتم الاحتفاظ بمحددات التنسيق والفواصل كمعيار، مثل '/' التي سيتم استخدامها دائمًا كفاصل بين التاريخ والوقت
وسيتم دائمًا استخدام "y" كجزء من "السنة" بغض النظر عن أي حرف خاص آخر يتم استخدامه للمكان المحدد.
###  تعريف:
```python
@property
def invariant_custom(self):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Style`](/cells/python-net/ar/aspose.cells/style)
