---
title: height_ratio_to_chart عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 200
url: /ar/aspose.cells.charts/plotarea/height_ratio_to_chart/
is_root: false
---
##  height_ratio_to_chart عقار

يحصل على أو يضبط ارتفاع مربع تحديد منطقة الرسم البياني بوحدات نسبة مساحة الرسم البياني.

###  ملاحظات

يشتمل المربع المحيط بمنطقة الرسم على منطقة الرسم وعلامات التحديد (علامات التحديد) وحدود صغيرة حول علامات التحديد.
 إذا لم يتم إنشاء القيمة بواسطة MS Excel، فيرجى استدعاء طريقة Chart.Calculate() قبل استدعاء هذه الطريقة.


 ال**نسبة XR إلى الرسم البياني** , **نسبة Y إلى الرسم البياني** , **نسبة العرض إلى الرسم البياني** و**نسبة الارتفاع إلى الرسم البياني** ل**منطقة الرسم** يمثل مساحة الرسم البياني
 مربع محيطي يتضمن منطقة الرسم البياني وعلامات التحديد (علامات التحديد) وحدود صغيرة حول علامات التحديد.
 إذا كنت تريد الحصول على الحجم الفعلي لمساحة الأرض، يجب عليك الاتصال**نسبة X الداخلية إلى الرسم البياني** , **النسبة الداخلية للمخطط** , **نسبة العرض الداخلي إلى الرسم البياني** و
**نسبة الارتفاع الداخلي إلى الرسم البياني** ملكيات.


بالنسبة لبرنامج Excel 2007 أو الإصدارات الأحدث، القيمة الافتراضية هي صفر. يجب عليك استدعاء get القيمة بعد استدعاء Chart.Calculate().

 
HeightPixel = HeightRatioToChart * chart.ChartObject.Width.
###  تعريف:
```python
@property
def height_ratio_to_chart(self):
    ...
@height_ratio_to_chart.setter
def height_ratio_to_chart(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells.charts`](../../)
* فئة [`PlotArea`](/cells/python-net/ar/aspose.cells.charts/plotarea)
