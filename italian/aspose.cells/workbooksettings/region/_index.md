---
title: region proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 440
url: /it/aspose.cells/workbooksettings/region/
is_root: false
---
##  region proprietà

Ottiene o imposta le impostazioni regionali per la cartella di lavoro.

###  Osservazioni

1. Impostazioni regionali utilizzate dal componente Aspose.Cells per una cartella di lavoro caricata dal file modello:
i). Per un file XLS, sono definiti campi per le impostazioni regionali e MS Excel salva i dati delle impostazioni regionali nel file quando salva il file XLS.
Quindi, utilizziamo il codice region salvato nel file modello per la cartella di lavoro.
Se non si desidera utilizzare il codice region salvato nel file XLS, reimpostarlo sul valore previsto (ad esempio CountryCode.Default) dopo aver caricato il file modello.
Inoltre, salviamo il valore specificato dall'utente (con questo metodo) anche nel file quando salviamo un file XLS.
ii). Per altri formati di file, come XLSX, XLSB...ecc., non è stato definito alcun campo per le impostazioni regionali nella specifica del formato di file.
Pertanto, utilizziamo le impostazioni regionali dell'ambiente dell'applicazione per la cartella di lavoro.
Inoltre, il valore specificato dall'utente (con questo metodo) non può essere mantenuto per i file generati con quei formati di file.
2. Per l'effetto di visualizzazione in MS Excel:
Le impostazioni regionali applicate qui possono avere effetto solo in fase di esecuzione con il componente Aspose.Cells e non durante la visualizzazione del file generato con MS Excel.
Anche per il file generato XLS in cui sono stati salvati i dati delle impostazioni regionali specificate, quando lo si visualizza/modifica con MS Excel,
il region utilizzato per eseguire la formattazione da MS Excel è sempre l'impostazione regionale predefinita dell'ambiente in cui MS Excel è in esecuzione,
Non quello salvato nel file. È un comportamento tipico di MS Excel e non può essere modificato tramite codice.
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
* classe [`WorkbookSettings`](/cells/python-net/it/aspose.cells/workbooksettings)
