---
title: linked_data_sources proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 60
url: /it/aspose.cells/calculationoptions/linked_data_sources/
is_root: false
---
##  linked_data_sources proprietà

Specifica le origini dati per i collegamenti esterni utilizzati nelle formule.

###  Osservazioni

Come [`Workbook.update_linked_data_source`](/cells/python-net/it/aspose.cells/workbook/update_linked_data_source), qui puoi specificare
fonti di dati per i collegamenti esterni utilizzati nelle formule da calcolare, in particolare quelle
utilizzato nella funzione INDIRETTO. Per i link esterni utilizzati nella funzione INDIRETTO,
non vengono considerati parte dei link esterni della cartella di lavoro e non possono essere aggiornati
tramite [`Workbook.update_linked_data_source`](/cells/python-net/it/aspose.cells/workbook/update_linked_data_source).
La corrispondenza di queste cartelle di lavoro con i link esterni è determinata da [`Workbook.file_name`](/cells/python-net/it/aspose.cells/workbook#file_name)
e [`ExternalLink.data_source`](/cells/python-net/it/aspose.cells/externallink#data_source). Quindi assicurati che [`Workbook.file_name`](/cells/python-net/it/aspose.cells/workbook#file_name) abbia
è stato specificato con il valore corretto (generalmente dovrebbe essere lo stesso del corrispondente
[`ExternalLink.data_source`](/cells/python-net/it/aspose.cells/externallink#data_source)) per ogni cartella di lavoro in modo che possano essere collegate come previsto.
###  Definizione:
```python
@property
def linked_data_sources(self):
    ...
@linked_data_sources.setter
def linked_data_sources(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CalculationOptions`](/cells/python-net/it/aspose.cells/calculationoptions)
