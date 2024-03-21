---
title: PdfSecurityOptions Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 10
url: /de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/
is_root: false
---
##  PdfSecurityOptions Klasse
Optionen zur Verschlüsselung und Zugriffsberechtigungen für ein PDF-Dokument.
PDF/A erlaubt keine Sicherheitseinstellung.



Der Typ PdfSecurityOptions macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) | Der Konstruktor von PdfSecurityOptions|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [user_password](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) | Ruft das zum Öffnen des verschlüsselten Dokuments PDF erforderliche Benutzerkennwort ab oder legt es fest.|
| [owner_password](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) | Ruft das Besitzerkennwort für das verschlüsselte Dokument PDF ab oder legt es fest.|
| [print_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) | Gibt an, ob das Drucken des Dokuments zugelassen werden soll.|
| [modify_document_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) |Gibt an, ob die Änderung des Dokumentinhalts durch andere als die gesteuerten Vorgänge zulässig ist<br/> unter [`PdfSecurityOptions.annotations_permission`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission), [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) und [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission).|
| [extract_content_permission_obsolete](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) | Die Erlaubnis zum Kopieren oder Extrahieren von Inhalten ist laut Referenz PDF veraltet.|
| [annotations_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) | Gibt an, ob das Hinzufügen oder Ändern von Textanmerkungen und das Ausfüllen interaktiver Formularfelder zulässig ist.|
| [fill_forms_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) | Gibt an, ob das Ausfüllen vorhandener interaktiver Formularfelder (einschließlich Signaturfeldern) zulässig ist.<br/> auch wenn [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) klar ist.|
| [extract_content_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) | Gibt an, ob das Kopieren oder anderweitige Extrahieren von Text und Grafiken aus dem Dokument zulässig ist<br/> durch andere als die von [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content) kontrollierten Betriebe.|
| [accessibility_extract_content](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) | Gibt an, ob das Extrahieren von Text und Grafiken zugelassen werden soll (zur Unterstützung der Barrierefreiheit für Benutzer mit Behinderungen oder für andere Zwecke).|
| [assemble_document_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) | Gibt an, ob das Zusammenstellen des Dokuments zulässig ist (Seiten einfügen, drehen oder löschen und Lesezeichen oder Miniaturbilder erstellen).<br/> auch wenn [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) klar ist.|
| [full_quality_print_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) | Gibt an, ob das Drucken des Dokuments in einer Darstellung gestattet werden soll<br/>wodurch eine originalgetreue digitale Kopie des PDF-Inhalts erstellt werden konnte.|



###  Siehe auch
* Modul [`aspose.cells.rendering.pdfsecurity`](..)
