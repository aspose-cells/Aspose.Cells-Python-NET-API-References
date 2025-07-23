---
title: طريقة clear
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 30
url: /ar/aspose.cells/externallinkcollection/clear/
is_root: false
---
##  clear(self) {#}
إزالة كافة الروابط الخارجية.



```python

def clear(self):
    ...
```


###  ملاحظات

عند إزالة الروابط الخارجية، سيتم أيضًا إزالة جميع الصيغ التي تشير إليها لأن
تصبح المراجع غير صالحة.

##  clear(self, update_references_as_local) {#bool}
إزالة كافة الروابط الخارجية.



```python

def clear(self, update_references_as_local):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| update_references_as_local | bool |ما إذا كان تحديث كافة المراجع الخاصة بالروابط الخارجية في الصيغ إلى مراجع المصنف الحالي نفسه.|
###  ملاحظات

إذا كان من المطلوب تحديث المراجع، فيجب أن تكون تلك المراجع الخاصة بالروابط الخارجية في الصيغ
سيتم تغييره إلى المصنف الحالي عندما يكون ذلك ممكنًا.
على سبيل المثال، الصيغة الأصلية لخلية واحدة هي "='externalsource.xlam'!customfunction()"،
بعد إزالة الروابط الخارجية، ستصبح الصيغة "=customfunction()";
عندما تكون الصيغة الأصلية هي "='[externalsource.xlam]Sheet1'!$A$1"،
وفقًا لوجود ورقة واحدة باسم "Sheet1" في المصنف الحالي:
إذا كانت صحيحة، ستصبح الصيغة "=Sheet1!$A$1"؛
إذا كانت القيمة false، ستصبح الصيغة "=#REF!$A$1".

إذا لم تكن هناك حاجة إلى تحديث المراجع، فيجب تحديث جميع الصيغ التي تحتوي على مراجع إلى روابط خارجية
سيتم إزالتها أيضًا لأن هذه المراجع أصبحت غير صالحة.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`ExternalLinkCollection`](/cells/python-net/ar/aspose.cells/externallinkcollection)
