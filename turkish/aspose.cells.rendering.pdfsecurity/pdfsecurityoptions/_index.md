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
PDF numaralı belge için şifreleme ve erişim izinleri seçenekleri.
PDF/A güvenlik ayarına izin vermiyor.



PdfSecurityOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) |PdfSecurityOptions'ın kurucusu|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [user_password](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) | Şifrelenmiş PDF belgesini açmak için gereken kullanıcı parolasını alır veya ayarlar.|
| [owner_password](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) | Şifrelenmiş PDF belgesinin sahip parolasını alır veya ayarlar.|
| [print_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) | Belgenin yazdırılmasına izin verilip verilmeyeceğini belirtir.|
| [modify_document_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) | Belgenin içeriğinin, kontrol edilenler dışındaki işlemler tarafından değiştirilmesine izin verilip verilmeyeceğini belirtir<br/> [`PdfSecurityOptions.annotations_permission`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission), [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) ve [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission) tarafından.|
| [extract_content_permission_obsolete](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) | İçeriğin kopyalanması veya çıkarılmasına izin verilmiştir. PDF referansı uyarınca geçersizdir.|
| [annotations_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) | Metin açıklamalarının eklenmesine veya değiştirilmesine, etkileşimli form alanlarının doldurulmasına izin verilip verilmeyeceğini belirtir.|
| [fill_forms_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) | Mevcut etkileşimli form alanlarının (imza alanları dahil) doldurulmasına izin verilip verilmeyeceğini belirtir,<br/> [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) temiz olsa bile.|
| [extract_content_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) | Belgeden metin ve grafiklerin kopyalanmasına veya başka bir şekilde çıkarılmasına izin verilip verilmeyeceğini belirtir<br/> [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content) tarafından kontrol edilenin dışındaki işlemlerle.|
| [accessibility_extract_content](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) |Engelli kullanıcıların erişilebilirliğini desteklemek veya diğer amaçlar için metin ve grafiklerin çıkarılmasına izin verilip verilmeyeceğini belirtir.|
| [assemble_document_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) | Belgenin birleştirilmesine (sayfaların eklenmesine, döndürülmesine veya silinmesine ve yer imleri veya küçük resim görüntülerinin oluşturulmasına) izin verilip verilmeyeceğini belirtir.<br/> [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) temiz olsa bile.|
| [full_quality_print_permission](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) | Belgenin bir gösterime yazdırılmasına izin verilip verilmeyeceğini belirtir<br/> PDF içeriğinin sadık bir dijital kopyasının oluşturulabilmesi.|



###  Ayrıca bakınız
* modül [`aspose.cells.rendering.pdfsecurity`](..)
