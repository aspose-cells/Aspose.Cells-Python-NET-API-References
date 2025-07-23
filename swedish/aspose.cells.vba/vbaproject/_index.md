---
title: VbaProject klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells.vba/vbaproject/
is_root: false
---
##  VbaProject klass
Representerar VBA-projektet.



Typen VbaProject avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [is_valid_signed](/cells/python-net/sv/aspose.cells.vba/vbaproject/is_valid_signed) | Anger om VBA-projektets signatur är giltig eller inte.|
| [cert_raw_data](/cells/python-net/sv/aspose.cells.vba/vbaproject/cert_raw_data) | Hämtar rådata för certifikat om detta VBA-projekt är signerat.|
| [encoding](/cells/python-net/sv/aspose.cells.vba/vbaproject/encoding) |Hämtar och ställer in kodningen för VBA-projektet.|
| [name](/cells/python-net/sv/aspose.cells.vba/vbaproject/name) | Hämtar och anger namnet på VBA-projektet.|
| [is_signed](/cells/python-net/sv/aspose.cells.vba/vbaproject/is_signed) | Anger om VBA-koden är signerad eller inte.|
| [is_protected](/cells/python-net/sv/aspose.cells.vba/vbaproject/is_protected) | Anger om detta VBA-projekt är skyddat.|
| [islocked_for_viewing](/cells/python-net/sv/aspose.cells.vba/vbaproject/islocked_for_viewing) | Anger om detta VBA-projekt är låst för visning.|
| [modules](/cells/python-net/sv/aspose.cells.vba/vbaproject/modules) | Hämtar alla [`VbaModule`](/cells/python-net/sv/aspose.cells.vba/vbamodule) objekt.|
| [references](/cells/python-net/sv/aspose.cells.vba/vbaproject/references) | Hämtar alla referenser från VBA-projektet.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`sign(self, digital_signature)`](/cells/python-net/sv/aspose.cells.vba/vbaproject/sign/#aspose.cells.digitalsignatures.digitalsignature) | Signera detta VBA-projekt med en digital signatur|
| [`protect(self, islocked_for_viewing, password)`](/cells/python-net/sv/aspose.cells.vba/vbaproject/protect/#bool-str) | Skyddar eller avskyddar detta VBA-projekt.|
| [`copy(self, source)`](/cells/python-net/sv/aspose.cells.vba/vbaproject/copy/#aspose.cells.vba.vbaproject) | Kopiera VBA-projekt från en annan fil.|
| [`validate_password(self, password)`](/cells/python-net/sv/aspose.cells.vba/vbaproject/validate_password/#str) | Validerar skyddslösenord.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Se även
* modul [`aspose.cells.vba`](..)
* klass [`VbaModule`](/cells/python-net/sv/aspose.cells.vba/vbamodule)
