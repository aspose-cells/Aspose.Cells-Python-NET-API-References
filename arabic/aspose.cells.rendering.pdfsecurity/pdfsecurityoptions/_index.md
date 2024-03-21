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
| [__init__](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) | منشئ PdfSecurityOptions|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [user_password](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) | الحصول على أو تعيين كلمة مرور المستخدم المطلوبة لفتح مستند PDF المشفر.|
| [owner_password](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) | الحصول على أو تعيين كلمة مرور المالك للمستند المشفر PDF.|
| [print_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) | يشير إلى ما إذا كان سيتم السماح بطباعة المستند.|
| [modify_document_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) |يشير إلى ما إذا كان سيتم السماح بتعديل محتويات الوثيقة عن طريق عمليات أخرى غير تلك التي يتم التحكم فيها<br/> بواسطة [`PdfSecurityOptions.annotations_permission`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission) و [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) و [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission).|
| [extract_content_permission_obsolete](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) | إذن نسخ أو استخراج المحتوى المهمل حسب مرجع PDF.|
| [annotations_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) | يشير إلى ما إذا كان سيتم السماح بإضافة أو تعديل التعليقات التوضيحية النصية، وملء حقول النموذج التفاعلية.|
| [fill_forms_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) | يشير إلى ما إذا كان سيتم السماح بملء حقول النموذج التفاعلي الموجودة (بما في ذلك حقول التوقيع)،<br/> حتى لو كان [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) واضحا.|
| [extract_content_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) | يشير إلى ما إذا كان سيتم السماح بنسخ النص والرسومات من المستند أو استخراجها بطريقة أخرى<br/> بعمليات غير تلك التي يسيطر عليها [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content).|
| [accessibility_extract_content](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) | يشير إلى ما إذا كان سيتم السماح باستخراج النصوص والرسومات (لدعم إمكانية الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى).|
| [assemble_document_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) | يشير إلى ما إذا كان سيتم السماح بتجميع المستند (إدراج الصفحات أو تدويرها أو حذفها وإنشاء إشارات مرجعية أو صور مصغرة)،<br/> حتى لو كان [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) واضحا.|
| [full_quality_print_permission](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) | يشير إلى ما إذا كان سيتم السماح بطباعة المستند إلى نسخة منه<br/>والتي يمكن إنشاء نسخة رقمية صحيحة من محتوى PDF.|



###  أنظر أيضا
* الوحدة [`aspose.cells.rendering.pdfsecurity`](..)
