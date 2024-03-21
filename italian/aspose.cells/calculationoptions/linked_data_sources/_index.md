---
title: linked_data_sources proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 80
url: /it/aspose.cells/calculationoptions/linked_data_sources/
is_root: false
---
##  linked_data_sources proprietà

Specifica le origini dati per i collegamenti esterni utilizzati nelle formule.

###  Osservazioni

Come [`Workbook.update_linked_data_source`](/cells/python-net/it/aspose.cells/workbook/update_linked_data_source), qui puoi specificare
fonti di dati per i collegamenti esterni utilizzati nelle formule da calcolare, in particolare quelli
utilizzato nella funzione INDIRETTO. Per i collegamenti esterni utilizzati nella funzione INDIRETTO,
non vengono presi come parte dei collegamenti esterni della cartella di lavoro e non possono essere aggiornati
tramite [`Workbook.update_linked_data_source`](/cells/python-net/it/aspose.cells/workbook/update_linked_data_source).
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
