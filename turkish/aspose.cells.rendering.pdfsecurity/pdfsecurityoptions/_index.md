---
title: PdfSecurityOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 10
url: /tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/
is_root: false
---
##  PdfSecurityOptions sınıfı
PDF belgesine ilişkin şifreleme ve erişim izinlerine ilişkin seçenekler.
PDF/A güvenlik ayarına izin vermiyor.



PdfSecurityOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) | PdfSecurityOptions'ın yapıcısı|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [user_password](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) | Şifrelenmiş PDF belgesini açmak için gereken kullanıcı parolasını alır veya ayarlar.|
| [owner_password](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) | Şifrelenmiş PDF belgesinin sahip parolasını alır veya ayarlar.|
| [print_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) | Belgenin yazdırılmasına izin verilip verilmeyeceğini belirtir.|
| [modify_document_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) |Belgenin içeriğinin, kontrol edilenler dışındaki işlemlerle değiştirilmesine izin verilip verilmeyeceğini belirtir.<br/> [`PdfSecurityOptions.annotations_permission`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission), [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) ve [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission) tarafından.|
| [extract_content_permission_obsolete](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) | İçeriği kopyalama veya çıkarma izni PDF referansına göre geçersizdir.|
| [annotations_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) | Metin açıklamalarının eklenmesine veya değiştirilmesine izin verilip verilmeyeceğini, etkileşimli form alanlarının doldurulup doldurulmayacağını belirtir.|
| [fill_forms_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) | Mevcut etkileşimli form alanlarının (imza alanları dahil) doldurulmasına izin verilip verilmeyeceğini belirtir.<br/> [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) açık olsa bile.|
| [extract_content_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) | Belgeden metin ve grafiklerin kopyalanmasına veya başka şekilde çıkarılmasına izin verilip verilmeyeceğini belirtir<br/> [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content) tarafından kontrol edilenler dışındaki operasyonlar tarafından.|
| [accessibility_extract_content](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) | Metin ve grafiklerin çıkarılmasına izin verilip verilmeyeceğini belirtir (engelli kullanıcıların erişilebilirliğini desteklemek amacıyla veya başka amaçlarla).|
| [assemble_document_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) | Belgenin birleştirilmesine (sayfa ekleme, döndürme veya silme ve yer imleri veya küçük resimler oluşturma) izin verilip verilmeyeceğini belirtir.<br/> [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) açık olsa bile.|
| [full_quality_print_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) | Belgenin bir temsile yazdırılmasına izin verilip verilmeyeceğini belirtir.<br/>PDF içeriğinin aslına uygun bir dijital kopyasının oluşturulabileceği.|



###  Ayrıca bakınız
* modül [`aspose.cells.rendering.pdfsecurity`](..)
