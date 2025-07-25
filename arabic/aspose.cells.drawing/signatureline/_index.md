---
title: SignatureLine صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 610
url: /ar/aspose.cells.drawing/signatureline/
is_root: false
---
##  SignatureLine صف
تمثل خط التوقيع.



يكشف النوع SignatureLine عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells.drawing/signatureline/__init__/#) | إنشاء مثيل جديد لـ SignatureLine|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [id](/cells/python-net/ar/aspose.cells.drawing/signatureline/id) | يحصل على معرف أو يعينه لسطر التوقيع هذا.|
| [provider_id](/cells/python-net/ar/aspose.cells.drawing/signatureline/provider_id) | يحصل على معرف مزود التوقيع أو يعينه.|
| [signer](/cells/python-net/ar/aspose.cells.drawing/signatureline/signer) | يحصل على الموقع أو يعينه.|
| [title](/cells/python-net/ar/aspose.cells.drawing/signatureline/title) | يحصل على أو يحدد عنوان المغني.|
| [email](/cells/python-net/ar/aspose.cells.drawing/signatureline/email) | يحصل على البريد الإلكتروني للمغني أو يعينه.|
| [is_line](/cells/python-net/ar/aspose.cells.drawing/signatureline/is_line) | يشير إلى ما إذا كان هذا سطر توقيع.|
| [allow_comments](/cells/python-net/ar/aspose.cells.drawing/signatureline/allow_comments) | يشير إلى ما إذا كان من الممكن إرفاق التعليقات.|
| [show_signed_date](/cells/python-net/ar/aspose.cells.drawing/signatureline/show_signed_date) | يشير إلى ما إذا كان سيتم عرض تاريخ التوقيع.|
| [instructions](/cells/python-net/ar/aspose.cells.drawing/signatureline/instructions) | يحصل على النص الذي يظهر للمستخدم في وقت التوقيع أو يعينه.|
| [signature_line_type](/cells/python-net/ar/aspose.cells.drawing/signatureline/signature_line_type) | يحصل على نوع التوقيع أو يعينه.<br/>افتراضي - عند تعيين القيمة الافتراضية، يتم إصلاح قيمة ProviderId المقابلة إلى {0000000000-0000-0000-0000-0000000000}.<br/>الطابع - عندما تكون القيمة طابعًا، تكون قيمة ProviderId المقابلة عادةً {000CD6A4-0000-0000-C000-000000000046}.<br/> مخصص - عندما تكون القيمة مخصصة، فمن الضروري عادةً تعيين قيمة ProviderId المقابلة بواسطة المستخدم. ويجب الحصول عليها من الوثائق المرفقة مع المزود.|



###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.drawing import SignatureLine

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
#  Create signature line object
s = SignatureLine()
s.signer = "Simon"
s.title = "Development"
s.email = "simon@aspose.com"
s.instructions = "Sign to confirm the excel content."
#  Adds a Signature Line to the worksheet.
signatureLine = worksheet.shapes.add_signature_line(0, 0, s)
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](..)
