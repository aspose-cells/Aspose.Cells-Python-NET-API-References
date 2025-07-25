---
title: VbaProjectReferenceCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 50
url: /it/aspose.cells.vba/vbaprojectreferencecollection/
is_root: false
---
##  VbaProjectReferenceCollection classe
Rappresenta tutti i riferimenti del progetto VBA.



Il tipo VbaProjectReferenceCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.vba/vbaprojectreferencecollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells.vba/vbaprojectreferencecollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells.vba/vbaprojectreferencecollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells.vba/vbaprojectreferencecollection/index_of/#aspose.cells.vba.vbaprojectreference-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.vba/vbaprojectreferencecollection/index_of/#aspose.cells.vba.vbaprojectreference-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#aspose.cells.vba.vbaprojectreference) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#aspose.cells.vba.vbaprojectreference-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#aspose.cells.vba.vbaprojectreference-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`add_registered_reference(self, name, libid)`](/cells/python-net/it/aspose.cells.vba/vbaprojectreferencecollection/add_registered_reference/#str-str) | Aggiungere un riferimento a una libreria di tipi di automazione.|
| [`add_control_refrernce(self, name, libid, twiddledlibid, extended_libid)`](/cells/python-net/it/aspose.cells.vba/vbaprojectreferencecollection/add_control_refrernce/#str-str-str-str) |Aggiungere un riferimento a una libreria di tipi modificata e alla sua libreria di tipi estesa.|
| [`add_project_refrernce(self, name, absolute_libid, relative_libid)`](/cells/python-net/it/aspose.cells.vba/vbaprojectreferencecollection/add_project_refrernce/#str-str-str) | Aggiunge un riferimento a un progetto VBA esterno.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells.vba/vbaprojectreferencecollection/binary_search/#aspose.cells.vba.vbaprojectreference) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



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
