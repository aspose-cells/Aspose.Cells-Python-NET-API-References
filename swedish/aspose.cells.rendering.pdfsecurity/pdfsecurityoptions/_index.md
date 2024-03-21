---
title: PdfSecurityOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 10
url: /sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/
is_root: false
---
##  PdfSecurityOptions klass
Alternativ för kryptering och åtkomstbehörigheter för ett PDF-dokument.
PDF/A tillåter inte säkerhetsinställningar.



Typen PdfSecurityOptions avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [__init__](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) | Konstruktören av PdfSecurityOptions|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [user_password](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) | Hämtar eller ställer in användarlösenordet som krävs för att öppna det krypterade PDF-dokumentet.|
| [owner_password](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) | Hämtar eller ställer in ägarlösenordet för det krypterade PDF-dokumentet.|
| [print_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) | Indikerar om dokumentet ska skrivas ut.|
| [modify_document_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) |Anger om innehållet i dokumentet ska tillåtas ändras genom andra åtgärder än de som kontrolleras<br/> via [`PdfSecurityOptions.annotations_permission`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission), [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) och [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission).|
| [extract_content_permission_obsolete](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) | Tillstånd att kopiera eller extrahera innehåll Föråldrad enligt PDF referens.|
| [annotations_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) | Anger om det ska tillåtas att lägga till eller ändra textkommentarer, fyll i interaktiva formulärfält.|
| [fill_forms_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) | Anger om man ska tillåta att fylla i befintliga interaktiva formulärfält (inklusive signaturfält),<br/> även om [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) är klart.|
| [extract_content_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) | Anger om man vill tillåta kopiering eller på annat sätt extrahera text och grafik från dokumentet<br/> av annan verksamhet än den som kontrolleras av [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content).|
| [accessibility_extract_content](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) | Anger om text och grafik ska tillåtas extrahera (till stöd för tillgänglighet för användare med funktionshinder eller för andra ändamål).|
| [assemble_document_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) | Indikerar om dokumentet ska tillåtas att sätta ihop (infoga, rotera eller ta bort sidor och skapa bokmärken eller miniatyrbilder),<br/> även om [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) är klart.|
| [full_quality_print_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) | Anger om dokumentet ska skrivas ut till en representation från<br/>som en trogen digital kopia av PDF-innehållet skulle kunna genereras.|



###  Se även
* modul [`aspose.cells.rendering.pdfsecurity`](..)
