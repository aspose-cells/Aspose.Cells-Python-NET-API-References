---
title: preferred_parsers عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 330
url: /ar/aspose.cells/txtloadoptions/preferred_parsers/
is_root: false
---
##  preferred_parsers عقار

يحصل على محللات القيمة المفضلة ويقوم بتعيينها لتحميل ملف النص.

###  ملاحظات

parsers[0] هو المحلل الذي سيتم استخدامه للعمود الأول في ملف قالب النص،
parsers[1] هو المحلل الذي سيتم استخدامه للعمود الثاني، ...إلخ.
سيتم استخدام العنصر الأخير (parsers[parsers.length-1]) لجميع الأعمدة الأخرى بدءًا من parsers.length-1.
إذا كان أحد العناصر فارغًا، فسيتم تحليل العمود المقابل بواسطة المحلل الافتراضي Aspose.Cells.
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
