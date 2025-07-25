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
| [`__init__(self)`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) |Konstruktorn av PdfSecurityOptions|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [user_password](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) | Hämtar eller ställer in användarlösenordet som krävs för att öppna det krypterade dokumentet PDF.|
| [owner_password](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) | Hämtar eller ställer in ägarlösenordet för det krypterade dokumentet PDF.|
| [print_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) | Anger om utskrift av dokumentet ska tillåtas.|
| [modify_document_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) | Anger om det ska vara tillåtet att ändra dokumentets innehåll med andra åtgärder än de som kontrolleras.<br/> av [`PdfSecurityOptions.annotations_permission`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission), [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) och [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission).|
| [extract_content_permission_obsolete](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) | Tillstånd att kopiera eller extrahera innehåll. Föråldrat enligt referens PDF.|
| [annotations_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) | Anger om det är tillåtet att lägga till eller ändra textanteckningar och fylla i interaktiva formulärfält.|
| [fill_forms_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) | Anger om det ska vara tillåtet att fylla i befintliga interaktiva formulärfält (inklusive signaturfält),<br/> även om [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) är klart.|
| [extract_content_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) | Anger om det är tillåtet att kopiera eller på annat sätt extrahera text och grafik från dokumentet.<br/> genom andra verksamheter än de som kontrolleras av [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content).|
| [accessibility_extract_content](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) |Anger om det ska vara tillåtet att extrahera text och grafik (för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål).|
| [assemble_document_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) | Anger om dokumentet får sättas samman (infoga, rotera eller ta bort sidor och skapa bokmärken eller miniatyrbilder).<br/> även om [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) är klart.|
| [full_quality_print_permission](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) | Anger om det ska vara tillåtet att skriva ut dokumentet till en representation från<br/> vilket skulle kunna genereras en korrekt digital kopia av innehållet i PDF.|



###  Se även
* modul [`aspose.cells.rendering.pdfsecurity`](..)
