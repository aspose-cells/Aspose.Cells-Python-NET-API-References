---
title: طريقة get_display_style
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 110
url: /ar/aspose.cells/cell/get_display_style/
is_root: false
---
##  get_display_style(self) {#}
يحصل على نمط العرض لهذه الخلية.


###  عائدات

أسلوب عرض هذه الخلية


```python

def get_display_style(self):
    ...
```


###  ملاحظات

نفس الشيء مع استخدام [`BorderType.SIDE_BORDERS`](/cells/python-net/ar/aspose.cells/bordertype#SIDE_BORDERS)
لرقم [`Cell.get_display_style`](/cells/python-net/ar/aspose.cells/cell/get_display_style).
أي أن هذه الطريقة سوف تقوم بفحص وتعديل الحدود العلوية/السفلية/اليسرى/اليمنى لهذه الخلية
وفقًا لنمط ([`Cell.get_style`](/cells/python-net/ar/aspose.cells/cell/get_style)) الخلايا المجاورة لها،
ولكن لا تتحقق من الخلايا المدمجة، ولا تتحقق من نمط عرض الخلايا المجاورة.

##  get_display_style(self, include_merged_borders) {#bool}
يحصل على نمط العرض لهذه الخلية.


###  عائدات

أسلوب عرض هذه الخلية


```python

def get_display_style(self, include_merged_borders):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| include_merged_borders | bool | يشير إلى ما إذا كان يتم التحقق من حدود الخلايا المندمجة.|
###  ملاحظات

إذا كان العلم المحدد خاطئًا، فهو نفس [`Cell.get_display_style`](/cells/python-net/ar/aspose.cells/cell/get_display_style).
وإلا فالأمر نفسه ينطبق على الاستخدام
[`BorderType.SIDE_BORDERS`](/cells/python-net/aspose.cells/bordertype#SIDE_BORDERS)|[`BorderType.DYNAMIC_STYLE_BORDERS`](/cells/python-net/aspose.cells/bordertype#DYNAMIC_STYLE_BORDERS)
لرقم [`Cell.get_display_style`](/cells/python-net/ar/aspose.cells/cell/get_display_style).

##  get_display_style(self, adjacent_borders) {#aspose.cells.BorderType}
يحصل على نمط العرض لهذه الخلية.


###  عائدات

أسلوب عرض هذه الخلية


```python

def get_display_style(self, adjacent_borders):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| adjacent_borders | [`BorderType`](/cells/python-net/ar/aspose.cells/bordertype) | يشير إلى الحدود التي تحتاج إلى التحقق منها وتعديلها<br/> وفقا لحدود الخلايا المجاورة.|
###  ملاحظات

إذا كانت هذه الخلية تتأثر أيضًا بإعدادات أخرى مثل التنسيق الشرطي وكائنات القائمة وما إلى ذلك،
ثم قد يكون نمط العرض مختلفًا عن [`Cell.get_style`](/cells/python-net/ar/aspose.cells/cell/get_style).

بالنسبة لأعلام ضبط الحدود وفقًا للخلايا المجاورة،
[`BorderType.TOP_BORDER`](/cells/python-net/aspose.cells/bordertype#TOP_BORDER)/[`BorderType.BOTTOM_BORDER`](/cells/python-net/aspose.cells/bordertype#BOTTOM_BORDER)
/[`BorderType.LEFT_BORDER`](/cells/python-net/aspose.cells/bordertype#LEFT_BORDER)/[`BorderType.RIGHT_BORDER`](/cells/python-net/aspose.cells/bordertype#RIGHT_BORDER)
الإشارة إلى ما إذا كان يجب التحقق من الحدود السفلية/العلوية/اليمنى/اليسرى ودمجها
الخلايا اليسرى/اليمنى/العلوية/السفلية المجاورة لهذه الخلية.

من أجل مراعاة الأداء والتوافق،
يتم استخدام بعض التعدادات للإشارة إلى بعض العمليات الخاصة:

[`BorderType.HORIZONTAL`](/cells/python-net/aspose.cells/bordertype#HORIZONTAL)/[`BorderType.VERTICAL`](/cells/python-net/aspose.cells/bordertype#VERTICAL)
قم بالإشارة إلى ما إذا كان يجب التحقق من الحدود السفلية/اليمنى للخلايا المندمجة ودمجها مع هذه الحدود.

[`BorderType.DIAGONAL`](/cells/python-net/ar/aspose.cells/bordertype#DIAGONAL)(أي كل من [`StyleModifyFlag.DIAGONAL_UP_BORDER`](/cells/python-net/ar/aspose.cells/stylemodifyflag#DIAGONAL_UP_BORDER) و
(تم تعيين [`StyleModifyFlag.DIAGONAL_DOWN_BORDER`](/cells/python-net/ar/aspose.cells/stylemodifyflag#DIAGONAL_DOWN_BORDER)) يشير إلى التحقق من الحدود ودمجها
من نمط عرض الخلايا المجاورة.

يرجى ملاحظة التحقق من حدود/أنماط الخلايا المجاورة، وخاصة أنماط العرض،
عملية تستغرق وقتًا طويلاً. إذا لم تكن هناك حاجة للحصول على حدود النمط المُعاد،
استخدام [`BorderType.NONE`](/cells/python-net/ar/aspose.cells/bordertype#NONE) لتعطيل عملية الخلايا المجاورة
سوف يعطي أداء أفضل.
عند الحصول على حدود الخلايا المجاورة من الأنماط المحددة على تلك الخلايا فقط (بدون إعداد
[`BorderType.DIAGONAL`](/cells/python-net/ar/aspose.cells/bordertype#DIAGONAL))، قد يكون الأداء أفضل أيضًا بسبب التحقق
إن أسلوب عرض خلية واحدة يستغرق وقتًا طويلاً أيضًا.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
