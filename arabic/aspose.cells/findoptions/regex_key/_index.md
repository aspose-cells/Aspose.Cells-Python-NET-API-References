---
title: regex_key عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 110
url: /ar/aspose.cells/findoptions/regex_key/
is_root: false
---
##  regex_key عقار

يشير إلى ما إذا كان المفتاح الذي تم البحث عنه هو regex.
إذا كانت القيمة صحيحة، فسيتم اعتبار المفتاح الذي تم البحث عنه بمثابة تعبير عادي وتحليله.
وإلا فسيتم تحليل المفتاح وفقًا للقواعد في برنامج Excel.

###  ملاحظات

على الرغم من أن مفتاح البحث تم تحديده كتعبير عادي،
يمكن إعادة صياغته وفقًا للمواصفات المحددة [`FindOptions.look_at_type`](/cells/python-net/ar/aspose.cells/findoptions#look_at_type).
على سبيل المثال، عندما يكون النوع هو [`LookAtType.CONTAINS`](/cells/python-net/ar/aspose.cells/lookattype#CONTAINS) (هذه هي القيمة الافتراضية لهذه الخيارات)،
سيتم إضافة الأحرف البدل في بداية ونهاية مفتاح البحث تلقائيًا لضمان التطابق
تم تحديد "يحتوي على". في هذه الحالة، ستصبح التعبيرات العادية أكثر تعقيدًا.
وسوف ينخفض الأداء أيضًا.
لذا، من أجل مراعاة الأداء، إذا حدد المستخدم القاعدة الدقيقة للتعبير العادي، فلا داعي لـ
استخدم [`FindOptions.look_at_type`](/cells/python-net/ar/aspose.cells/findoptions#look_at_type) كقيد إضافي ويمكن للمستخدم تعيينه على [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/ar/aspose.cells/lookattype#ENTIRE_CONTENT)
للحصول على أداء أفضل.
###  تعريف:
```python
@property
def regex_key(self):
    ...
@regex_key.setter
def regex_key(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`FindOptions`](/cells/python-net/ar/aspose.cells/findoptions)
