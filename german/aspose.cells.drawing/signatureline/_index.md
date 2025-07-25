---
title: SignatureLine Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 610
url: /de/aspose.cells.drawing/signatureline/
is_root: false
---
##  SignatureLine Klasse
Stellt die Signaturzeile dar.



Der Typ SignatureLine macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells.drawing/signatureline/__init__/#) | Erstellt eine neue Instanz von SignatureLine|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [id](/cells/python-net/de/aspose.cells.drawing/signatureline/id) | Ruft die Kennung für diese Signaturzeile ab oder legt sie fest.|
| [provider_id](/cells/python-net/de/aspose.cells.drawing/signatureline/provider_id) | Ruft die ID des Signaturanbieters ab oder legt sie fest.|
| [signer](/cells/python-net/de/aspose.cells.drawing/signatureline/signer) | Ruft den Unterzeichner ab oder legt ihn fest.|
| [title](/cells/python-net/de/aspose.cells.drawing/signatureline/title) | Ruft den Titel des Sängers ab oder legt ihn fest.|
| [email](/cells/python-net/de/aspose.cells.drawing/signatureline/email) | Ruft die E-Mail-Adresse des Sängers ab oder legt sie fest.|
| [is_line](/cells/python-net/de/aspose.cells.drawing/signatureline/is_line) | Gibt an, ob es sich um eine Signaturzeile handelt.|
| [allow_comments](/cells/python-net/de/aspose.cells.drawing/signatureline/allow_comments) | Gibt an, ob Kommentare angehängt werden können.|
| [show_signed_date](/cells/python-net/de/aspose.cells.drawing/signatureline/show_signed_date) | Gibt an, ob das Datum der Unterschrift angezeigt wird.|
| [instructions](/cells/python-net/de/aspose.cells.drawing/signatureline/instructions) | Ruft den Text ab, der dem Benutzer beim Signieren angezeigt wird, oder legt ihn fest.|
| [signature_line_type](/cells/python-net/de/aspose.cells.drawing/signatureline/signature_line_type) | Ruft den Signaturtyp ab oder legt ihn fest.<br/>Standard: Wenn der Standardwert festgelegt ist, wird der entsprechende ProviderId-Wert auf {0000000000-0000-0000-0000-0000000000} festgelegt.<br/>Stempel: Wenn der Wert „Stempel“ lautet, ist der entsprechende ProviderId-Wert normalerweise {000CD6A4-0000-0000-C000-000000000046}.<br/> Benutzerdefiniert – Wenn der Wert „Benutzerdefiniert“ ist, muss der entsprechende ProviderId-Wert normalerweise vom Benutzer festgelegt werden. Er sollte der mit dem Anbieter gelieferten Dokumentation entnommen werden.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.drawing`](..)
