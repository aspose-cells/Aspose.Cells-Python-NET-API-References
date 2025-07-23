---
title: طريقة get_leafs
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 160
url: /ar/aspose.cells/cell/get_leafs/
is_root: false
---
##  get_leafs(self) {#}
احصل على جميع الخلايا التي تشير إلى هذه الخلية بشكل مباشر وتحتاج إلى التحديث عند تعديل هذه الخلية.


###  عائدات

عدّاد لإحصاء جميع المعالين (Cell)


```python

def get_leafs(self):
    ...
```


###  ملاحظات

ملاحظة: هذه الفئة أصبحت قديمة الآن. بدلاً من ذلك،
يرجى استخدام Cell.GetDependentsInCalculation(bool) للحصول على جميع التابعين في سلسلة الحساب.
سيتم إزالة هذه الخاصية بعد مرور 12 شهرًا منذ مايو 2022.
Aspose يعتذر عن أي إزعاج قد يكون واجهته.

##  get_leafs(self, recursive) {#bool}
احصل على جميع الخلايا التي سيتم تحديثها عند تعديل هذه الخلية.


###  عائدات

عدّاد لإحصاء جميع المعالين (Cell)


```python

def get_leafs(self, recursive):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| recursive | bool | ما إذا كان يتم إرجاع تلك الأوراق التي لا تشير إلى هذه الخلية بشكل مباشر<br/> لكن الإشارة إلى أوراق أخرى من هذه الخلية|
###  ملاحظات

ملاحظة: هذه الفئة أصبحت قديمة الآن. بدلاً من ذلك،
يرجى استخدام Cell.GetDependentsInCalculation(bool) للحصول على جميع التابعين في سلسلة الحساب.
سيتم إزالة هذه الخاصية بعد مرور 12 شهرًا منذ مايو 2022.
Aspose يعتذر عن أي إزعاج قد يكون واجهته.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
