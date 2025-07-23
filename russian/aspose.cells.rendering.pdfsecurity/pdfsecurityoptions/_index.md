---
title: PdfSecurityOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 10
url: /ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/
is_root: false
---
##  PdfSecurityOptions класс
Варианты шифрования и прав доступа для документа PDF.
PDF/A не позволяет настраивать безопасность.



Тип PdfSecurityOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) |Конструктор PdfSecurityOptions|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [user_password](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) | Возвращает или задает пароль пользователя, необходимый для открытия зашифрованного документа PDF.|
| [owner_password](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) | Получает или задает пароль владельца для зашифрованного документа PDF.|
| [print_permission](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) | Указывает, разрешить ли печать документа.|
| [modify_document_permission](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) | Указывает, разрешено ли изменять содержимое документа с помощью операций, отличных от контролируемых<br/> по телефонам [`PdfSecurityOptions.annotations_permission`](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission), [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) и [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission).|
| [extract_content_permission_obsolete](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) | Разрешение на копирование или извлечение контента Устарело согласно ссылке PDF.|
| [annotations_permission](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) | Указывает, разрешить ли добавлять или изменять текстовые аннотации, заполнять поля интерактивных форм.|
| [fill_forms_permission](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) | Указывает, разрешать ли заполнение существующих полей интерактивной формы (включая поля подписи),<br/> даже если [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) свободен.|
| [extract_content_permission](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) | Указывает, разрешено ли копировать или иным образом извлекать текст и графику из документа.<br/> по операциям, отличным от контролируемых [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content).|
| [accessibility_extract_content](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) |Указывает, разрешать ли извлечение текста и графики (для обеспечения доступности для пользователей с ограниченными возможностями или для других целей).|
| [assemble_document_permission](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) | Указывает, разрешать ли компоновку документа (вставку, поворот или удаление страниц, а также создание закладок или миниатюрных изображений),<br/> даже если [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) свободен.|
| [full_quality_print_permission](/cells/python-net/ru/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) | Указывает, разрешить ли печать документа в представлении из<br/> в результате чего может быть создана точная цифровая копия контента PDF.|



###  Смотрите также
* модуль [`aspose.cells.rendering.pdfsecurity`](..)
