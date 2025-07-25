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
| [`__init__(self)`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/__init__/#) |Der Konstruktor von PdfSecurityOptions|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [user_password](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/user_password) | Ruft das zum Öffnen des verschlüsselten Dokuments PDF erforderliche Benutzerkennwort ab oder legt es fest.|
| [owner_password](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/owner_password) | Ruft das Besitzerkennwort für das verschlüsselte Dokument PDF ab oder legt es fest.|
| [print_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/print_permission) | Gibt an, ob das Drucken des Dokuments zulässig ist.|
| [modify_document_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/modify_document_permission) | Gibt an, ob die Änderung des Dokumentinhalts durch andere als die von<br/> unter [`PdfSecurityOptions.annotations_permission`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#annotations_permission), [`PdfSecurityOptions.fill_forms_permission`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#fill_forms_permission) und [`PdfSecurityOptions.assemble_document_permission`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#assemble_document_permission).|
| [extract_content_permission_obsolete](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission_obsolete) | Berechtigung zum Kopieren oder Extrahieren von Inhalten. Veraltet gemäß Referenz PDF.|
| [annotations_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/annotations_permission) | Gibt an, ob das Hinzufügen oder Ändern von Textanmerkungen und das Ausfüllen interaktiver Formularfelder zulässig ist.|
| [fill_forms_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/fill_forms_permission) | Gibt an, ob das Ausfüllen vorhandener interaktiver Formularfelder (einschließlich Signaturfelder) erlaubt sein soll.<br/> auch wenn [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) klar ist.|
| [extract_content_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/extract_content_permission) | Gibt an, ob das Kopieren oder anderweitige Extrahieren von Text und Grafiken aus dem Dokument erlaubt ist<br/> durch andere Vorgänge als den von [`PdfSecurityOptions.accessibility_extract_content`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#accessibility_extract_content) kontrollierten.|
| [accessibility_extract_content](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/accessibility_extract_content) |Gibt an, ob das Extrahieren von Text und Grafiken zulässig ist (zur Unterstützung der Zugänglichkeit für Benutzer mit Behinderungen oder für andere Zwecke).|
| [assemble_document_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/assemble_document_permission) | Gibt an, ob das Zusammenstellen des Dokuments (Einfügen, Drehen oder Löschen von Seiten und Erstellen von Lesezeichen oder Miniaturbildern) erlaubt ist.<br/> auch wenn [`PdfSecurityOptions.modify_document_permission`](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions#modify_document_permission) klar ist.|
| [full_quality_print_permission](/cells/python-net/de/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions/full_quality_print_permission) | Gibt an, ob das Drucken des Dokuments in eine Darstellung von<br/> wodurch eine originalgetreue digitale Kopie des Inhalts von PDF erstellt werden konnte.|



###  Siehe auch
* Modul [`aspose.cells.rendering.pdfsecurity`](..)
