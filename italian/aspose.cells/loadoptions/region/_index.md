---
title: region proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 210
url: /it/aspose.cells/loadoptions/region/
is_root: false
---
##  region proprietà

Ottiene o imposta le impostazioni regionali utilizzate per la cartella di lavoro che verrà caricata.

###  Osservazioni

Le impostazioni regionali possono essere utilizzate per inizializzare alcune funzionalità della cartella di lavoro
come caratteri, temi e così via.
Per i formati di file basati su testo, come CSV, HTML, ..., l'impostazione regionale
verrà utilizzato anche per rilevare i formati numerici e analizzare i valori di testo in numerici
o valori datetime per le celle.
Questa impostazione verrà mantenuta per la cartella di lavoro istanziata in seguito, vale a dire,
[`WorkbookSettings.region`](/cells/python-net/it/aspose.cells/workbooksettings#region) della cartella di lavoro utilizzerà lo stesso region
con questa proprietà.
###  Definizione:
```python
@property
def region(self):
    ...
@region.setter
def region(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CountryCode`](/cells/python-net/it/aspose.cells/countrycode)
* classe [`LoadOptions`](/cells/python-net/it/aspose.cells/loadoptions)
