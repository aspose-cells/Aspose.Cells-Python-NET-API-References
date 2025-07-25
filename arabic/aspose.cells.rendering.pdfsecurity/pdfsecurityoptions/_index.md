---
title: PdfSecurityOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 10
url: /ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/
is_root: false
---
##  PdfSecurityOptions صف
خيارات التشفير وأذونات الوصول لمستند PDF.
PDF/A لا يسمح بإعدادات الأمان.



يكشف النوع PdfSecurityOptions عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) |منشئ PdfSecurityOptions|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [user_password](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) | يحصل على كلمة مرور المستخدم المطلوبة لفتح المستند المشفر PDF أو يعينها.|
| [owner_password](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) | يحصل على كلمة مرور المالك للمستند المشفر PDF أو يعينها.|
| [print_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) | يشير إلى ما إذا كان سيتم السماح بطباعة المستند.|
| [modify_document_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) | يشير إلى ما إذا كان سيتم السماح بتعديل محتويات المستند من خلال عمليات أخرى غير تلك التي يتم التحكم فيها<br/> بواسطة [`PdfSecurityOptions.annotations_permission`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission)، [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) و [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission).|
| [extract_content_permission_obsolete](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) | مسموح بنسخ أو استخراج المحتوى غير صالح وفقًا للمرجع PDF.|
| [annotations_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) | يشير إلى ما إذا كان سيتم السماح بإضافة تعليقات نصية أو تعديلها، وملء حقول النموذج التفاعلي.|
| [fill_forms_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) | يشير إلى ما إذا كان سيتم السماح بملء حقول النموذج التفاعلي الموجودة (بما في ذلك حقول التوقيع)،<br/> حتى لو كان [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) واضحا.|
| [extract_content_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) | يشير إلى ما إذا كان سيتم السماح بنسخ أو استخراج النصوص والرسومات من المستند<br/> من خلال عمليات أخرى غير تلك التي يتم التحكم فيها بواسطة [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content).|
| [accessibility_extract_content](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) |يشير إلى ما إذا كان سيتم السماح باستخراج النصوص والرسومات (لدعم إمكانية الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى).|
| [assemble_document_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) | يشير إلى ما إذا كان سيتم السماح بتجميع المستند (إدراج أو تدوير أو حذف الصفحات وإنشاء إشارات مرجعية أو صور مصغرة)،<br/> حتى لو كان [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) واضحا.|
| [full_quality_print_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) | يشير إلى ما إذا كان سيتم السماح بطباعة المستند إلى تمثيل من<br/> حيث يمكن إنشاء نسخة رقمية دقيقة من المحتوى PDF.|



###  أنظر أيضا
* الوحدة [`aspose.cells.rendering.pdfsecurity`](..)
