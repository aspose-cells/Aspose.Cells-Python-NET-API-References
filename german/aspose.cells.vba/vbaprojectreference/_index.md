---
title: VbaProjectReference Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells.vba/vbaprojectreference/
is_root: false
---
##  VbaProjectReference Klasse
Stellt die Referenz des VBA-Projekts dar.



Der Typ VbaProjectReference macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [type](/cells/python-net/de/aspose.cells.vba/vbaprojectreference/type) |Ruft den Typ dieser Referenz ab.|
| [name](/cells/python-net/de/aspose.cells.vba/vbaprojectreference/name) | Ruft den Namen der Referenz ab und legt ihn fest.|
| [libid](/cells/python-net/de/aspose.cells.vba/vbaprojectreference/libid) | Ruft die Libid der Referenz ab und legt sie fest.|
| [twiddledlibid](/cells/python-net/de/aspose.cells.vba/vbaprojectreference/twiddledlibid) | Ruft die verdrehte Libid der Referenz ab und legt sie fest.|
| [extended_libid](/cells/python-net/de/aspose.cells.vba/vbaprojectreference/extended_libid) | Ruft die erweiterte Libid der Referenz ab und legt sie fest.|
| [relative_libid](/cells/python-net/de/aspose.cells.vba/vbaprojectreference/relative_libid) | Ruft die Kennung des referenzierten VBA-Projekts mit einem relativen Pfad ab und legt sie fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/de/aspose.cells.vba/vbaprojectreference/copy/#aspose.cells.vba.vbaprojectreference) |  |



###  Beispiel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add vba project reference
vbaProject.references.add_registered_reference("stdole", "*\\G{00020430-0000-0000-C000-000000000046}#2.0#0#C:\\Windows\\system32\\stdole2.tlb#OLE Automation")
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Siehe auch
* Modul [`aspose.cells.vba`](..)
