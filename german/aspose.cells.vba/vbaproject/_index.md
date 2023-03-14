---
title: VbaProject Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 30
url: /de/aspose.cells.vba/vbaproject/
is_root: false
---
##  VbaProject Klasse
Stellt das VBA-Projekt dar.



Der Typ VbaProject macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [is_valid_signed](/cells/python-net/de/aspose.cells.vba/vbaproject/is_valid_signed) | Gibt an, ob die Signatur des VBA-Projekts gültig ist oder nicht.|
| [cert_raw_data](/cells/python-net/de/aspose.cells.vba/vbaproject/cert_raw_data) | Ruft Rohdaten des Zertifikats ab, wenn dieses VBA-Projekt signiert ist.|
| [name](/cells/python-net/de/aspose.cells.vba/vbaproject/name) | Ruft den Namen des VBA-Projekts ab und legt ihn fest.|
| [is_signed](/cells/python-net/de/aspose.cells.vba/vbaproject/is_signed) | Gibt an, ob VBAcode signiert ist oder nicht.|
| [is_protected](/cells/python-net/de/aspose.cells.vba/vbaproject/is_protected) | Gibt an, ob dieses VBA-Projekt geschützt ist.|
| [islocked_for_viewing](/cells/python-net/de/aspose.cells.vba/vbaproject/islocked_for_viewing) | Gibt an, ob dieses VBA-Projekt für die Anzeige gesperrt ist.|
| [modules](/cells/python-net/de/aspose.cells.vba/vbaproject/modules) | Ruft alle [VbaModule](/cells/python-net/de/aspose.cells.vba/vbamodule)-Objekte ab.|
| [references](/cells/python-net/de/aspose.cells.vba/vbaproject/references) | Ruft alle Referenzen des VBA-Projekts ab.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [sign(digital_signature)](/cells/python-net/de/aspose.cells.vba/vbaproject/sign/#aspose.cells.digitalsignatures.DigitalSignature) | Signieren Sie dieses VBA-Projekt mit einer DigitalSignature|
| [protect(islocked_for_viewing, password)](/cells/python-net/de/aspose.cells.vba/vbaproject/protect/#bool-str) | Schützt dieses VBA-Projekt oder hebt den Schutz auf.|
| [copy(source)](/cells/python-net/de/aspose.cells.vba/vbaproject/copy/#VbaProject) | Kopieren Sie das VBA-Projekt aus einer anderen Datei.|
| [validate_password(password)](/cells/python-net/de/aspose.cells.vba/vbaproject/validate_password/#str) | Validiert das Schutzkennwort.|



###  Beispiel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Siehe auch
* Modul [aspose.cells.vba](..)
* Klasse [VbaModule](/cells/python-net/de/aspose.cells.vba/vbamodule)
