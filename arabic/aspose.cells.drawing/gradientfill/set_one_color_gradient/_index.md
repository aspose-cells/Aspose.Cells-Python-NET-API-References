---
title: طريقة set_one_color_gradient
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 30
url: /ar/aspose.cells.drawing/gradientfill/set_one_color_gradient/
is_root: false
---
##  set_one_color_gradient(self, color, degree, style, variant) {#aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}
تعيين التعبئة المحددة إلى تدرج لوني أحادي اللون.
ينطبق فقط على Excel 2007.



```python

def set_one_color_gradient(self, color, degree, style, variant):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| color | aspose.pydrawing.Color | لون متدرج واحد.|
| degree | float | درجة التدرج. يمكن أن تكون قيمة من ٠.٠ (داكن) إلى ١.٠ (فاتح).|
| style | [`GradientStyleType`](/cells/python-net/ar/aspose.cells.drawing/gradientstyletype) | نمط التظليل المتدرج.|
| variant | int | متغير التدرج. يمكن أن تكون قيمة من ١ إلى ٤، تتوافق مع أحد المتغيرات الأربعة في علامة تبويب "التدرج" ضمن مربع حوار "تأثيرات التعبئة". إذا كان النمط GradientStyle.FromCenter، فلا يمكن أن تكون وسيطة المتغير سوى ١ أو ٢.|



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`GradientFill`](/cells/python-net/ar/aspose.cells.drawing/gradientfill)
