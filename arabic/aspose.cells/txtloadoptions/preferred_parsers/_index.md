---
title: preferred_parsers عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 350
url: /ar/aspose.cells/txtloadoptions/preferred_parsers/
is_root: false
---
##  preferred_parsers عقار

يحصل على ويحدد موزعي القيمة المفضلة لتحميل الملف النصي.

###  ملاحظات

parsers[0] هو المحلل اللغوي الذي سيتم استخدامه للعمود الأول في ملف القالب النصي،
المحلل اللغوي[1] هو المحلل الذي سيتم استخدامه للعمود الثاني، ...إلخ.
سيتم استخدام الأخير (parsers[parsers.length-1]) لجميع الأعمدة الأخرى التي تبدأ من parsers.length-1.
إذا كان أحد العناصر فارغًا، فسيتم تحليل العمود المقابل بواسطة المحلل اللغوي الافتراضي Aspose.Cells.
###  تعريف:
```python
@property
def preferred_parsers(self):
    ...
@preferred_parsers.setter
def preferred_parsers(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`TxtLoadOptions`](/cells/python-net/ar/aspose.cells/txtloadoptions)
