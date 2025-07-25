---
title: طريقة calculate_data
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells.pivot/pivottable/calculate_data/
is_root: false
---
##  calculate_data(self) {#}
حساب بيانات الجدول المحوري للخلايا.



```python

def calculate_data(self):
    ...
```


###  ملاحظات

Cell.لا يمكن للقيمة الموجودة في نطاق المحور إرجاع النتيجة الصحيحة إذا لم يتم استدعاء الطريقة.
تحسب هذه الطريقة البيانات باستخدام ذاكرة التخزين المؤقت المحورية الداخلية، وليس مصدر البيانات الأصلي.
لذا، إذا تم تغيير مصدر البيانات، فيرجى استدعاء طريقة RefreshData() أولاً.

##  calculate_data(self, option) {#aspose.cells.pivot.PivotTableCalculateOption}
حساب جداول المحور مع الخيارات



```python

def calculate_data(self, option):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| option | [`PivotTableCalculateOption`](/cells/python-net/ar/aspose.cells.pivot/pivottablecalculateoption) |  |



###  أنظر أيضا
* الوحدة [`aspose.cells.pivot`](../../)
* فئة [`PivotTable`](/cells/python-net/ar/aspose.cells.pivot/pivottable)
