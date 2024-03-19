---
title: Metered صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1090
url: /ar/aspose.cells/metered/
is_root: false
---
##  Metered صف
يوفر طرقًا لضبط المفتاح المقنن.



يكشف النوع Metered عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells/metered/__init__/#) | تهيئة مثيل جديد من هذه الفئة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [set_metered_key](/cells/python-net/ar/aspose.cells/metered/set_metered_key/#str-str) | مجموعات قياس المفتاح العام والخاص.<br/> إذا قمت بشراء ترخيص مقنن، عند بدء تقديم الطلب، يجب الاتصال بالرقم API، وهذا يكفي عادةً.<br/> ومع ذلك، إذا فشل دائمًا في تحميل بيانات الاستهلاك وتجاوزت 24 ساعة، فسيتم ضبط الترخيص على حالة التقييم،<br/> لتجنب مثل هذه الحالة، يجب عليك التحقق بانتظام من حالة الترخيص، إذا كانت حالة التقييم، اتصل على API مرة أخرى.|
| [get_consumption_quantity](/cells/python-net/ar/aspose.cells/metered/get_consumption_quantity/#) | يحصل على حجم ملف الاستهلاك|
| [get_consumption_credit](/cells/python-net/ar/aspose.cells/metered/get_consumption_credit/#) | يحصل على ائتمان الاستهلاك|
| [get_product_name](/cells/python-net/ar/aspose.cells/metered/get_product_name/#) | يحصل على اسم المنتج|
| [is_metered_licensed](/cells/python-net/ar/aspose.cells/metered/is_metered_licensed/#) | تحقق مما إذا كان القياس مرخصًا|



###  مثال

في هذا المثال، سيتم إجراء محاولة لتعيين المفتاح العام والخاص


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
