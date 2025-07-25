---
title: Metered صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 980
url: /ar/aspose.cells/metered/
is_root: false
---
##  Metered صف
توفر طرقًا لتعيين المفتاح المقاس.



يكشف النوع Metered عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells/metered/__init__/#) | يقوم بإنشاء مثيل جديد لهذه الفئة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/cells/python-net/ar/aspose.cells/metered/set_metered_key/#str-str) | تعيين المفتاح العام والخاص المقاس.<br/>إذا قمت بشراء ترخيص مقنن، عند بدء التطبيق، يجب عليك الاتصال بالرقم API، وعادةً ما يكون هذا كافياً.<br/> ومع ذلك، إذا فشلت دائمًا في تحميل بيانات الاستهلاك وتجاوزت 24 ساعة، فسيتم ضبط الترخيص على حالة التقييم،<br/> لتجنب مثل هذه الحالة، يجب عليك التحقق من حالة الترخيص بانتظام، إذا كانت حالة التقييم، فاتصل بالرقم API مرة أخرى.|
| [`get_consumption_quantity()`](/cells/python-net/ar/aspose.cells/metered/get_consumption_quantity/#) | يحصل على حجم ملف الاستهلاك|
| [`get_consumption_credit()`](/cells/python-net/ar/aspose.cells/metered/get_consumption_credit/#) | يحصل على ائتمان الاستهلاك|
| [`get_product_name(self)`](/cells/python-net/ar/aspose.cells/metered/get_product_name/#) | يحصل على اسم المنتج|
| [`is_metered_licensed()`](/cells/python-net/ar/aspose.cells/metered/is_metered_licensed/#) | تحقق مما إذا كان القياس مرخصًا|



###  مثال

في هذا المثال، سيتم إجراء محاولة لتعيين مفتاح عام وخاص مقيس


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
