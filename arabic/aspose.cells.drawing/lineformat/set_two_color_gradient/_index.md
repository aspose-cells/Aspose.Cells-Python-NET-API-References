---
title: طريقة set_two_color_gradient
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells.drawing/lineformat/set_two_color_gradient/
is_root: false
---
##  set_two_color_gradient(self, color1, color2, style, variant) {#aspose.pydrawing.Color-aspose.pydrawing.Color-aspose.cells.drawing.GradientStyleType-int}
تعيين التعبئة المحددة إلى تدرج لوني ثنائي اللون.
ينطبق فقط على Excel 2007.



```python

def set_two_color_gradient(self, color1, color2, style, variant):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | لون متدرج واحد.|
| color2 | aspose.pydrawing.Color | لونين متدرجين.|
| style | [`GradientStyleType`](/cells/python-net/ar/aspose.cells.drawing/gradientstyletype) | نمط التظليل المتدرج.|
| variant | int | متغير التدرج. يمكن أن تكون قيمة من ١ إلى ٤، تتوافق مع أحد المتغيرات الأربعة في علامة تبويب "التدرج" ضمن مربع حوار "تأثيرات التعبئة". إذا كان النمط GradientStyle.FromCenter، فلا يمكن أن تكون وسيطة المتغير سوى ١ أو ٢.|


##  set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant) {#aspose.pydrawing.Color-float-aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}
تعيين التعبئة المحددة إلى تدرج لوني ثنائي اللون.
ينطبق فقط على Excel 2007.



```python

def set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color | لون متدرج واحد.|
| transparency1 | float | درجة شفافية اللون1 كقيمة من 0.0 (غير شفاف) إلى 1.0 (واضح).|
| color2 | aspose.pydrawing.Color | لونين متدرجين.|
| transparency2 | float | درجة شفافية اللون2 كقيمة من 0.0 (غير شفاف) إلى 1.0 (واضح).|
| style | [`GradientStyleType`](/cells/python-net/ar/aspose.cells.drawing/gradientstyletype) | نمط التظليل المتدرج.|
| variant | int | متغير التدرج. يمكن أن تكون قيمة من ١ إلى ٤، تتوافق مع أحد المتغيرات الأربعة في علامة تبويب "التدرج" ضمن مربع حوار "تأثيرات التعبئة". إذا كان النمط GradientStyle.FromCenter، فلا يمكن أن تكون وسيطة المتغير سوى ١ أو ٢.|



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`LineFormat`](/cells/python-net/ar/aspose.cells.drawing/lineformat)
