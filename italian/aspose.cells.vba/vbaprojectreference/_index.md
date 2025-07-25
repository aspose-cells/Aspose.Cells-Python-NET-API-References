---
title: VbaProjectReference classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 40
url: /it/aspose.cells.vba/vbaprojectreference/
is_root: false
---
##  VbaProjectReference classe
Rappresenta il riferimento del progetto VBA.



Il tipo VbaProjectReference espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [type](/cells/python-net/it/aspose.cells.vba/vbaprojectreference/type) |Ottiene il tipo di questo riferimento.|
| [name](/cells/python-net/it/aspose.cells.vba/vbaprojectreference/name) | Ottiene e imposta il nome del riferimento.|
| [libid](/cells/python-net/it/aspose.cells.vba/vbaprojectreference/libid) | Ottiene e imposta il Libid del riferimento.|
| [twiddledlibid](/cells/python-net/it/aspose.cells.vba/vbaprojectreference/twiddledlibid) | Ottiene e imposta il Libid modificato del riferimento.|
| [extended_libid](/cells/python-net/it/aspose.cells.vba/vbaprojectreference/extended_libid) | Ottiene e imposta il Libid esteso del riferimento.|
| [relative_libid](/cells/python-net/it/aspose.cells.vba/vbaprojectreference/relative_libid) | Ottiene e imposta l'identificatore del progetto VBA referenziato con un percorso relativo.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/it/aspose.cells.vba/vbaprojectreference/copy/#aspose.cells.vba.vbaprojectreference) |  |



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells.vba`](..)
