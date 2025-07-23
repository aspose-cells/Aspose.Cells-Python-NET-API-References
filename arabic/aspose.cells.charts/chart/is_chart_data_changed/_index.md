---
title: طريقة is_chart_data_changed
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 80
url: /ar/aspose.cells.charts/chart/is_chart_data_changed/
is_root: false
---
##  is_chart_data_changed(self) {#}
يكتشف ما إذا كان مصدر بيانات الرسم البياني قد تغير.


###  عائدات

يعود صحيحًا إذا تغير الرسم البياني وإلا يعود خطأً


```python

def is_chart_data_changed(self):
    ...
```


###  ملاحظات

تكتشف الطريقة التغييرات في مصدر بيانات الرسم البياني قبل عرض الرسم البياني بتنسيق الصورة.
في أول استدعاء لـ Chart.toImage، سيتم تسجيل بيانات مصدر الرسم البياني (على سبيل المثال XValuesParseData، ValuesParseData).
قبل استدعاء طريقة Chart.toImage مرة أخرى، قم باستدعاء طريقة IsChartDataChanged للتحقق مما إذا كان Chart يحتاج إلى إعادة عرض.


###  أنظر أيضا
* الوحدة [`aspose.cells.charts`](../../)
* فئة [`Chart`](/cells/python-net/ar/aspose.cells.charts/chart)
