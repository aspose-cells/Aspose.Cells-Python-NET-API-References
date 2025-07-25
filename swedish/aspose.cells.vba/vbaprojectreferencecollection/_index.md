---
title: VbaProjectReferenceCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 50
url: /sv/aspose.cells.vba/vbaprojectreferencecollection/
is_root: false
---
##  VbaProjectReferenceCollection klass
Representerar alla referenser till VBA-projektet.



Typen VbaProjectReferenceCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells.vba/vbaprojectreferencecollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells.vba/vbaprojectreferencecollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells.vba/vbaprojectreferencecollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.vba/vbaprojectreferencecollection/index_of/#aspose.cells.vba.vbaprojectreference-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.vba/vbaprojectreferencecollection/index_of/#aspose.cells.vba.vbaprojectreference-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#aspose.cells.vba.vbaprojectreference) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#aspose.cells.vba.vbaprojectreference-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#aspose.cells.vba.vbaprojectreference-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`add_registered_reference(self, name, libid)`](/cells/python-net/sv/aspose.cells.vba/vbaprojectreferencecollection/add_registered_reference/#str-str) | Lägg till en referens till ett bibliotek för automationstyper.|
| [`add_control_refrernce(self, name, libid, twiddledlibid, extended_libid)`](/cells/python-net/sv/aspose.cells.vba/vbaprojectreferencecollection/add_control_refrernce/#str-str-str-str) |Lägg till en referens till ett twiddled-typbibliotek och dess utökade typbibliotek.|
| [`add_project_refrernce(self, name, absolute_libid, relative_libid)`](/cells/python-net/sv/aspose.cells.vba/vbaprojectreferencecollection/add_project_refrernce/#str-str-str) | Lägger till en referens till ett externt VBA-projekt.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells.vba/vbaprojectreferencecollection/binary_search/#aspose.cells.vba.vbaprojectreference) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

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

###  Se även
* modul [`aspose.cells.vba`](..)
